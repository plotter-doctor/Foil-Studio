# Changes prepared for 0.1.129

Prepared 9 November 2026. Prepared for Google Play submission; approval and availability are not yet claimed. Current production is 0.1.127 (148), available since 7 November 2026.

## Prepare for plotter

Reversible object preparation recovers certified circular arcs and simplifies redundant straight sections. Original drawing paths and process settings remain. The preview reports before/after counts, a geometric error bound and protected/skipped contours. Nearby contours and holes receive conservative protection. Work runs locally with cancellation and stale-result guards; no learned model or network processing is involved.

The default tolerance is 0.01 mm. Device rounding and backend curve approximation add their own error. Native-arc output and continuous compensated circular knife motion are used where supported; other backends approximate the prepared geometry for their coordinate grid. This is not a uniform physical-accuracy or cutting-speed guarantee.

## Calibration and cutting

The main knife trial compares 30 × 30 mm squares in five offset columns and three pressure rows where the app controls pressure. Panel-controlled pressure uses one row. The selection matches the sheet labels and shows both winning values. Saving identifies the tool offset and material/plotter pressure scope and explains existing-object tool snapshots.

Jobs are reviewed in Prepare. In Cut, choose Job and press Start cutting; installed-stock, HTV, tool, mat and connection checks remain. About displays the current Free, Basic or Pro access plan.

## Documentation

The four-language shared help and examples, full Markdown/Word/PDF manuals, concise workflow guide, reviewer steps, release notes, store copy and current sample captures are maintained together. Earlier dated reports, releases and images retain their original context.

[Validation](validation-2026-11-09.md) · [Manual](user-manual.md) · [Release notes](release-notes.md)
