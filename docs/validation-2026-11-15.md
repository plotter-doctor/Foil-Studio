# Validation scope for 0.1.145

Prepared for Google Play production submission. Approval and availability of 0.1.145 are not yet claimed. Current production is 0.1.129 (150), available since 9 November 2026.

## Software and layout

The one-row correction passed the 75-test targeted regression run and the final 14-test layout suite, including custom saved distance. These overlapping runs are not added together. EN/PL/DE/ES renders cover narrow portrait, landscape, 200% text and the connected phone’s 360 × 780 logical viewport at 1.15 text scale. Chips remain separated and labels fit. The complete local Flutter suite passed 3913 tests with zero failures; 76 tests requiring optional fixtures or external environments were explicitly skipped. Format and static analysis passed. Android APK/AAB signatures, package/version, all bundled source assets and three CPU architectures were verified. The owner also confirmed the installed phone layout is correct; wider buttons are deferred to a future usability update.

## Protocol qualification

GCC app-adapter tests cover 282 supported model/transport cases. The external published simulator accepted 112 exact model/transport cases. Another 170 cases lack matching model or framing contracts and are recorded as blocked, not passed. Native USB admission, optional replies and permissions have separate checks. Physical GCC hardware has not been qualified.

Earlier VEVOR KH-1350A USB and serial checks were physically observed by the owner, including repeated jogs and cutting. They do not certify every VEVOR model, firmware, force or cutting quality. The latest UI correction sends no new machine command.

Demo, app transport fixtures, external protocol simulators and physical checks are separate evidence categories. Generated manuals are checked in all four languages; retained store images keep their original version labels.

[Release status](release-notes.md) · [Manuals](manual/README.md)
