# Validation for 0.1.129

Reviewed 9 November 2026. Submitted for Google Play production on 9 November 2026. Google Play shows the changes in its checking workflow; automated checks and approval are pending. Managed publishing is off, with full rollout requested after approval. Current production remains 0.1.127 (148), available since 7 November 2026.

## Application and phone

The exact runtime passes 3365 native-enabled host tests with 51 documented skips and no failures. Static analysis is clean. Skipped external, optional-platform or supervised-hardware cases are not reported as passed physical tests. Release CI for this exact candidate passed all five jobs: Flutter/web and the four Rust packages.

The signed universal APK was updated in place on a Samsung at 1080 × 2340, DPR 3 and font scale 1.15. Launch, current version/plan, Prepare entry, Cut Start, the full Design/Edit action and knife-calibration entry were visually inspected. No overlap or clipping was found in the changed controls. Project labels and the app pixels excluding system bars matched the pre-update empty Design view after QA. No project/library record was edited and no physical plotter movement occurred.

Populated preparation, calibration selection/save receipts, narrow portrait/landscape, keyboard and enlarged-text states are covered by rendered real-theme tests in English, Polish, German and Spanish. These include the Samsung display profile, 320 px width at 200% text and tablet layouts. Corrections for an ellipsized tolerance label and reduced compact Prepare viewport have regressions.

## Geometry and independent knife model

Circle/partial-arc fitting and corner-preserving simplification certify the accepted candidate against source segments; uncertain/topologically close contours remain unchanged. Checks cover closed winding/area, open paths, duplicate contours, transforms, serialization, undo, stale workers, bounded work and process-setting preservation.

Nine new prepared-curve cases pass the independent ideal knife model at nominal 0.05 mm across FilmCut, Smart and Silhouette. Their worst target deviations are approximately 0.0040, 0.0230 and 0.0313 mm respectively. The complete historical sweep contains 174 jobs and 1065 strokes; its nominal classifications are 246 pass, 26 fail and 19 uncertain, including deliberate negative/coarse-grid cases. Do not treat the entire historical sweep as uniformly within tolerance.

A private diagnostic replay reduced a dense circular FilmCut contour from 558 to 14 commands with a certified preparation bound of 0.0043382 mm, retaining source artwork, 2500 mm/min, raw pressure 180 and one pass. The artwork is not published. This command count is specific to that FilmCut replay; it is not a measured physical cutting time or a universal backend count.

## Limits

Software/model checks do not measure blade exposure, actual force, material behaviour or mechanical accuracy. The phone QA did not perform a physical trial or save a winning sample. The current app/tablet layouts have synthetic and earlier device evidence; no new physical tablet update is claimed for this release. Device codec, printer, connection and individual model/firmware qualification remain specific to their recorded checks.

[Development changes](development-2026-11-09.md) · [Manual](user-manual.md) · [Release notes](release-notes.md)
