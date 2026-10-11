# Foil Studio 0.1.72 — tool setup and pressure

Updated 11 October 2026.

Open **More → Application settings → Tool lowering** to save:

- **Initial PWM**: starting drive in the same S units as working pressure.
  The default value is 320.
- **Initial duration [ms]**: time at the starting drive. The default value is
  10 ms.

Existing saved pulse values are retained when updating. There is no PCB selector;
the app automatically applies the lower supported limit of 45% of live `$30`.

Default working pressure is **180 PWM for knives**, **150 PWM for pens**, and
**250 PWM for engraving and scoring tools**. Speed remains 2500 mm/min. These are
starting settings, not force measurements. Choose working pressure on the object
(or use its tool's saved setting). Untouched factory library profiles upgrade
once; customized tools and explicitly saved object settings are preserved.
The Pressure field in Machine control applies to that manual operation.
Directional jog buttons keep the state set by Tool down or Tool up, including
working pressure. They do not repeat the initial pulse. Homing lifts the tool;
a jog also releases it first if its state is unknown after reconnecting or an
interrupted operation.
Before a job or positive manual pressure, the app reads the controller's current
scale and checks its linear pressure configuration. Both phases respect this
limit, and the initial phase is raised to working pressure when needed.

Each lowering uses an ordered sequence such as:

```gcode
G1 M3 S320
G4 P0.010
G1 M3 S150
```

The firmware controls this dwell. The app sends the sequence together, before
XY motion. Connected cutting segments and pressure changes while already down
do not repeat the initial phase. A real G0 travel lifts the tool, so the next
contact starts a new sequence. Zero pressure uses M5 without an initial phase.

Values are PWM setpoints, not a measurement of force. Timing still needs to be
checked on the fitted head and material; protocol tests do not prove that the
head has physically reached the material.

## Tools and object overrides

Open More → Tool library to change a reusable tool. New knife, pen, engraving and
scoring tools begin with the defaults above. When adding a tool, changing its kind
updates pressure until you enter your own pressure. Editing or duplicating an
existing tool preserves its saved pressure.

Select an object and open Object properties to choose its named tool and override
speed, pressure or passes. Composite boxes and clipart allow selecting each tool
group. Materials remain reference labels and do not assign tools or process values.
Existing objects retain their saved tool snapshots and explicit overrides when a
library preset is updated.

New ordinary objects use Drag knife 45°. For the replacement-blade set described
in the app, yellow 30° is suggested for thin film, red 45° for everyday paper and
vinyl, and blue 60° for thicker materials. Starting offsets are 0.25 mm for 30°/45°
and 0.10 mm for 60°; these are not manufacturer-verified calibration values.

## Update behavior

An unchanged factory tool is upgraded once to the new working-pressure default.
Custom pressure, speed, offset, notes or names are preserved. A later deliberate
change back to an older value is also preserved. Existing saved Initial PWM and
Initial duration values remain yours; change them in Application settings if you
want to adopt 320 / 10.
