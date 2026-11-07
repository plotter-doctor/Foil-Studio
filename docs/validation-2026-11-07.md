# Validation for 0.1.127 — 7 November 2026

This page separates final 0.1.127 (148) checks from the earlier cumulative UI/import/command audit. The version is in Google Play review; approval and rollout are pending. Results do not certify physical machines.

## Final application and phone checks

The final application suite passes 3,202 tests with 51 documented skips and no failures. Static analysis is clean. Skips retain explicit external-corpus, external-model, loopback-fixture or supervised-hardware requirements; a skipped test is not a passed physical check.

Actual-phone checks verify New → square → inherited Vinyl, valid Review, missing-material warning and assignment routing, cancelled calibration material choice, normal background return and active-project restoration after process restart. Tests cover a saved multilayer project and newly edited temporary artwork. Prepared plans and physical confirmations are not restored. Temporary QA content was removed; no physical plotter movement or cutting was performed.

The phone uses 1080 × 2340 pixels, density ratio 3 and text scale 1.15. Current material-warning renders cover all four languages at that logical profile and compact portrait/landscape at 200% text. Calibration material selection adds 24 inspected initial/bottom states, with long names, thickness, source/version labels and Cancel reachable. These changed views were visually checked for spacing and readable painted labels. Physical tablet hardware was unavailable.

## UI windows and editing

The earlier cumulative common-window matrix covers 44 dialog configurations in English, Polish, German and Spanish at three display profiles: 360 × 780 logical pixels at density ratio 3 and text scale 1.15, compact 320 × 640 portrait, and 640 × 320 landscape at 200 percent text. The phone profile also uses representative status/navigation insets. This gives 528 window/profile/language combinations, with expanded sections, scrolling, keyboard focus, visible action controls and painted text/field checks.

Additional suites cover the complete Design, Prepare and Cut shell, machine views, registration, printing, imports, purchases/access, wizards, help and examples. Long-name Cut jobs were reviewed in all twelve language/display combinations. Problems found in dropdown heights, floating labels, expanded-section insets, compact scrolling and field focus were corrected and retested. Sample artwork is independently authored; customer projects and private phone screenshots are not published.

## Actual simulator commands

Seventy-five feature variants were exercised against eight protocol/process fixtures: FilmCut G-code, Smart with app-controlled or panel-controlled process settings, Graphtec GPGL, Roland HPGL, Summa HPGL, Summa DMPL and Silhouette GPGL. There were 599 streamed jobs with motion and no simulator errors; one zero-force Smart job was intentionally rejected before transmission. A final replay preserved all 599 wire hashes.

Separate checks covered 35 named model fixtures, 13 Smart JSON/backend cases and 11 Silhouette cases across ten models. One named HP fixture is parser-only. These results describe the configured simulator contracts and do not establish a physical TCP interface or cut quality for every model.

The matrix checks job/layer inclusion, tools, object overrides, pass counts, transforms, repetition, copies/layout, weeding, marks, HTV, mirroring and registration offsets. Actual GUI save/reassignment checks verify the corresponding command changes. Stock identity and artwork colours deliberately preserve existing tool settings; view-only pan/zoom/grid changes do not themselves generate cutting geometry. Export header/footer behavior is checked separately from native-protocol output.

## Drag knife compensation and overcut

Thirty-one dedicated geometry checks include 360 convex-loop configurations, near-axis paths, rotations, sharp/reversed corners, open and closed paths, holes, repeated passes, overcut spanning several edges, exact accepted command bytes and compensated motion bounds. Numeric underflow and tiny-swivel rejection defects were reproduced before correction. Bounds remain checked even for omitted sub-resolution swivels. Calibration and tool-save/review workflows were also exercised.

New compensated production paths pivot at every nonzero turn, including the formerly skipped shallow turns. New calibration sheets separately orient the knife before each contour/pass; saved older sheets retain their geometry until regenerated. Finite command/device resolution remains, and unrepresentable geometry fails validation. Physical blade angle is tool identity rather than a geometric offset parameter; overcut applies to closed paths with compensation enabled. Choose the physical offset and smallest effective overcut with the app's calibration samples and your actual blade/material.

An independent ideal blade-contact model also checks the actual generated commands against separately supplied target contours. Its strict nominal 0.05 mm sweep contains 187 passes, 15 failures and 19 uncertain cases; the nonpassing nominal cases are on coarse Graphtec GPGL or Silhouette grids. This is a disclosed precision boundary, not a claim that those paths meet that tolerance. Starting orientation and the model's assumptions remain relevant. Wrong settings and reversal controls remain separate from matching-setting checks.

## Diverse imports

Coverage includes editable SVG/DXF and eligible PDF/EPS/AI/CDR paths, original colour/layer/holes/transforms, unsupported appearance fallback, malformed and bounded inputs, page selection, scale/placement, undo and saved-project round trips. Native parsers and the bridge from generated editable output into the application were exercised with original fixtures.

Eight encoded raster formats were checked for printing and contrast tracing, alongside PSD merged and supported pixel-layer behavior, animated GIF and multipage TIFF first-frame/page handling, JPEG orientation and desktop SVG entry. Checks cover resulting pixels, geometry, tools and inclusion in generated commands. Separate colors is absent; saved coloured paths remain editable.

## Device and physical limits

The cumulative audit uses rendered app widgets, native parsers, mocked platform contracts and the external protocol simulator. The final 0.1.127 phone installation and workflow/restoration checks are recorded above. Neither the audit nor those phone checks operate a physical plotter or measure force, blade exposure, mechanical accuracy or material behaviour. Real Android PDF rendering, camera/document-provider interaction and device-specific HEIC/AVIF decoding need their own device qualification; the focused phone checks do not establish a complete codec or hardware matrix.

[Development changes](development-2026-11-07.md) · [Manual](user-manual.md) · [Release notes](release-notes.md)
