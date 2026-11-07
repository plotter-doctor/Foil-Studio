# Development validation 7 November 2026

This page describes validation of the current development changes after private phone candidate 0.1.123 (144). It is not a Google Play release announcement or physical-machine certification.

## UI windows and editing

The common-window matrix covers 44 dialog configurations in English, Polish, German and Spanish at three display profiles: 360 × 780 logical pixels at density ratio 3 and text scale 1.15, compact 320 × 640 portrait, and 640 × 320 landscape at 200 percent text. The phone profile also uses representative status/navigation insets. This gives 528 window/profile/language combinations, with expanded sections, scrolling, keyboard focus, visible action controls and painted text/field checks.

Additional suites cover the complete Design, Prepare and Cut shell, machine views, registration, printing, imports, purchases/access, wizards, help and examples. Long-name Cut jobs were reviewed in all twelve language/display combinations. Problems found in dropdown heights, floating labels, expanded-section insets, compact scrolling and field focus were corrected and retested. Sample artwork is independently authored; customer projects and private phone screenshots are not published.

## Actual simulator commands

Seventy-five feature variants were exercised against eight protocol/process fixtures: FilmCut G-code, Smart with app-controlled or panel-controlled process settings, Graphtec GPGL, Roland HPGL, Summa HPGL, Summa DMPL and Silhouette GPGL. There were 599 streamed jobs with motion and no simulator errors; one zero-force Smart job was intentionally rejected before transmission. A final replay preserved all 599 wire hashes.

Separate checks covered 35 named model fixtures, 13 Smart JSON/backend cases and 11 Silhouette cases across ten models. One named HP fixture is parser-only. These results describe the configured simulator contracts and do not establish a physical TCP interface or cut quality for every model.

The matrix checks job/layer inclusion, tools, object overrides, pass counts, transforms, repetition, copies/layout, weeding, marks, HTV, mirroring and registration offsets. Actual GUI save/reassignment checks verify the corresponding command changes. Stock identity and artwork colours deliberately preserve existing tool settings; view-only pan/zoom/grid changes do not themselves generate cutting geometry. Export header/footer behavior is checked separately from native-protocol output.

## Drag knife compensation and overcut

Thirty-one dedicated geometry checks include 360 convex-loop configurations, near-axis paths, rotations, sharp/reversed corners, open and closed paths, holes, repeated passes, overcut spanning several edges, exact accepted command bytes and compensated motion bounds. Numeric underflow and tiny-swivel rejection defects were reproduced before correction. Bounds remain checked even for omitted sub-resolution swivels. Calibration and tool-save/review workflows were also exercised.

The planner retains its specified 20-degree corner approximation and finite command/device resolution. Unrepresentable geometry still fails validation. Physical blade angle is tool identity rather than a geometric offset parameter; overcut applies to closed paths with compensation enabled. Choose the physical offset and smallest effective overcut with the app's calibration samples and your actual blade/material.

## Diverse imports

Coverage includes editable SVG/DXF and eligible PDF/EPS/AI/CDR paths, original colour/layer/holes/transforms, unsupported appearance fallback, malformed and bounded inputs, page selection, scale/placement, undo and saved-project round trips. Native parsers and the bridge from generated editable output into the application were exercised with original fixtures.

Eight encoded raster formats were checked for printing and contrast tracing, alongside PSD merged and supported pixel-layer behavior, animated GIF and multipage TIFF first-frame/page handling, JPEG orientation and desktop SVG entry. Checks cover resulting pixels, geometry, tools and inclusion in generated commands. Separate colors is absent; saved coloured paths remain editable.

## Device and physical limits

This audit uses rendered app widgets, native parsers, mocked platform contracts and the external protocol simulator. It does not operate a real plotter or measure force, blade exposure, mechanical accuracy or material behavior. Real Android PDF rendering, camera/document-picker interaction and device-specific HEIC/AVIF decoding require device qualification. The latest development changes were not installed on the phone as part of this audit.

[Development changes](development-2026-11-07.md) · [Manual](user-manual.md) · [Release notes](release-notes.md)
