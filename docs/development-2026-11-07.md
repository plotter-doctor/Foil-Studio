# Development changes 7 November 2026

These are current development changes after private phone candidate 0.1.123 (144). This page does not announce Google Play availability. The [manual](user-manual.md) and [four-language quick start](quick-start.md) describe the new workflow.

## Layers and production

Layers, Object manager and Object properties share Material assignment using the existing Materials library. Production jobs remain explicit, so equal stock or colour does not merge separate sheets. Prepare jobs uses compact rows with Details and keeps order, placement, copies, assembly marks, weeding and HTV controls.

Cut now chooses the production job and requires installed-material confirmation. Prepare previews no longer activate a job. Changing a job invalidates the previous review and alignment confirmation. Actual passes appear under Operations and settings; the removed Tool passes dropdown only changed displayed text.

New editable multicolour imports and Add job take the current material. Existing explicit materials, No material choices, job IDs, unknown saved fields and project data keep their meaning. Assignment labels have visible spacing and long names wrap inside dropdowns.

## Imports

Supported solid colours, named layers, holes and original contours are retained for editable vector inputs. Rendered images remain printable and can be contrast-traced. PSD offers supported separate aligned pixel layers. Separate colors has been removed from raster and rendered-drawing import. Saved coloured contours remain editable.

## Knife precision and GUI corrections

Valid near-axis knife paths no longer fail merely because a tiny swivel rounds to the same command coordinate. Invalid numeric geometry is rejected with a normal validation message. Raw plotter output also handles repeated coordinates within a contour without merging separate contours or tool stages. Small settings can still round to identical moves at the machine's coordinate resolution; use the calibration workflow for the fitted blade and stock.

The UI review corrected floating-label collisions, long dropdown values, short-window clipart and tool editors, expanded-section insets and Craft field focus. The complete Cut screen now scrolls within its actual available space, with its start control included in scrolling when needed. Stored object tools are distinguishable from edited same-name library tools, and help explains how to assign the updated record.

## Documentation and validation

Current manuals, reviewer guidance, version notes, privacy version wording and screenshot/store captions have been reviewed. Historical releases remain archived. The release instructions require a complete documentation review for every Google Play release.

The UI, external simulator, knife geometry and diverse-input audit is described in the [validation summary](validation-2026-11-07.md). It includes 599 streamed simulated jobs, independent geometric checks, real-theme multilingual window reviews and original/native import fixtures. These results do not qualify physical cutting quality or every device/firmware combination.
