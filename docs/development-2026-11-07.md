# Changes prepared for 0.1.127 — 7 November 2026

**0.1.127 (148) is in Google Play review; approval and rollout are pending.** The cumulative changes below follow production 0.1.116 (137). See the [four-language release record](releases/0.1.127.md), [workflow guide](user-manual.md), [manual downloads](manual/README.md) and [quick start](quick-start.md).

## Layer stock and active projects

Material is assigned only in Layers → Edit layer. Objects inherit their layer's stock and take the destination layer's material when moved. Materials remain stock presets; tools, pressure, speed and passes stay with object/tool settings. New projects initialise Default with the current material. Existing missing or explicitly cleared assignments are not guessed.

Review now warns when included cutting artwork lacks material. Prepare stays open and the warning offers Layers; assignment requires another explicit Review. Direct Cut applies the check to the intended job, so an unrelated unassigned job does not block valid selected work.

A separate local active-project checkpoint retains the current artwork and its library identity after background return or app restart. Background flush covers changes before the normal save delay. An intentional New retains a blank active document. Restart restores artwork rather than prepared plans or physical stock/mat confirmations. Older versions had no last-active pointer: open the intended saved project once after upgrading. Exported backups remain important.

## Prepare, Cut and wide-screen editing

Prepare uses compact material, mat and plotter cards. Production preview opens layout and Prepare jobs directly. The short job list and assembly-mark settings are visible first; Details contains longer settings.

Cut keeps a smaller Job selector, material name and large preview. Choosing a job immediately filters its artwork and assembly marks. Review job separately asks for installed-stock and applicable HTV confirmation. Tool/pass edits stay in Object properties; repeated blade and Operations and settings panels are removed. Unique machine options remain under Advanced settings where supported.

Wide Design views use a layer/object tree with properties, Add layer, explicit moves and drag/drop. GUI corrections cover floating labels, long dropdown values, expanded sections, small windows and keyboard focus in English, Polish, German and Spanish.

## Imports and knife calibration

Supported solid colours, source layers, holes and original contours are retained for editable SVG/DXF and eligible PDF/EPS/AI/CDR inputs. Unsupported appearance uses the reported print-rendering fallback rather than partial invented paths. PSD supports eligible aligned pixel layers. Printable insertion and contrast tracing remain available; Separate colors is removed.

New knife compensation handles shallow turns instead of skipping their pivot. New calibration sheets provide separate orientation strokes before each contour and pass; saved earlier sheets retain their geometry until regenerated. Calibration uses actual selected/uniform stock and offers a cancellable material choice for mixed or unassigned sources. The choice does not rewrite source layers, the current default or library records.

Device grids, starting blade orientation and actual mechanics still limit results. Use meaningful offset/overcut steps and the smallest effective overcut, testing on the fitted blade and stock. The Smart manual Tool up correction uses a brief left-and-return movement; clear the working area before machine control. Manual pressure remains separate from object process settings.

## Documentation and validation

The current documentation inventory covers README, privacy, the English workflow guide, four-language complete manuals and quick start, reviewer/setup guidance, versioned release notes and screenshot/store captions. Historical releases and images retain their version context.

The [validation report](validation-2026-11-07.md) distinguishes final application tests, rendered layout checks, actual-phone restoration checks and external simulator results. Passing protocol tests is not physical-machine certification or a uniform cut-accuracy promise.
