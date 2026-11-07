# Foil Studio user manual

English · Updated 7 November 2026 · Current development workflow

[Home](../README.md) · [Release notes](release-notes.md) · [Four-language quick start](quick-start.md) · [Download PDF](manual/FoilStudio-User-Manual.pdf) · [Download Word](manual/FoilStudio-User-Manual.docx)

## Versions covered

This manual describes the current development app, including changes after the private phone candidate 0.1.123 (144). The new Cut job selector and removal of Separate colors are unreleased. Your Google Play installation may show an earlier workflow. Check the version in the app and use the matching release notes. The latest version-specific public note in this repository is 0.1.116; that is not a statement about the version currently delivered by Google Play.

## First project

1. In Design, create a small rectangle or open an example from Help and examples.
2. Position the artwork on the mat and save a copy of the project.
3. In Prepare, select your material, mat and exact plotter model. Review the tool and its process settings.
4. Open Connection setup. Use demo mode to practise without hardware, or explicitly connect your compatible plotter.
5. Choose Review job to continue to Cut. For a project with production jobs, select the job and confirm that its material is installed.
6. Inspect the preview and Operations and settings. Check the physical mat alignment before confirming it.
7. Start the job and follow the tool-installation prompts. Supervise the machine until completion.

Use a small test piece when choosing pressure, speed, blade depth or pass count. Pressure units and supported settings depend on the plotter. A material record describes stock and thickness. Choose the tool/process settings explicitly and test them on your actual stock.

## Design and selection

Tap artwork to select it. Use the selection controls to add or remove objects; drag from unused space for an area selection. Two fingers pan and zoom the view. Undo and Redo let you inspect a change and return to the earlier design.

Create shapes, outlined text, clipart and freehand paths using the design tools. Numeric dimensions and transforms provide precise placement. Alignment and distribution compare selected objects; layout tools can repeat artwork or fill a sheet. Review their preview before applying it.

Object properties hold the tool and process settings that determine production. Tools can include knife, pen, scoring, engraving and Printer, where supported. Printer artwork is for printed output rather than blade motion. Colours identify artwork visually; changing a colour alone does not choose pressure or tool type.

Objects keep the tool snapshot assigned to them. Editing a library record does not rewrite existing objects. To use the edited record, select it again in Object properties; Current object tool identifies a stored snapshot when it shares a name with an updated library record.

Path editing, offsets and Boolean operations require suitable geometry. Closed contours, holes, open strokes and very small details behave differently. Inspect generated contours after union, subtraction, offsets, tracing or simplification. The weeding tools add waste-removal paths, so include them in the preview check.

Box and Craft wizards create editable projects with fold/cut operations. Preserve the wizard's generated object relationships when regenerating. Test fit with your actual material thickness. Pro is required for wizard creation and regeneration; already-open artwork remains subject to the normal editing and output access rules.

## Layers materials and production jobs

Layers organizes artwork and provides Material assignment. A design layer is an editing group. A material is a stock preset from the existing Materials library. A production job is the set of objects produced on one sheet or material placement.

These choices can differ: a job can contain objects from several design layers, and separate jobs can use the same material. Jobs do not merge just because their colours or material names match. Tool stages within one job keep mixed-tool sheets together.

Use Material assignment from Layers, Object manager or Object properties. Keep current assignments when you want to leave the existing setup alone. Select an existing production job to join it, or create a Separate job. Mixed selections show their mixed assignments instead of guessing one value.

New production jobs created by editable multicolour imports or Add job start with the current material. Set a different stock for each job when needed. Existing saved No material choices and explicit material snapshots remain unchanged. Choosing stock does not overwrite independently configured object tool/process settings.

Layer inclusion and visibility affect production eligibility. Excluded or hidden artwork does not become a cut simply because it has a job assignment. Review the effective job again after editing membership, tools, geometry or settings.

## Prepare jobs and assembly marks

Open Prepare jobs to edit the short job list, object assignments, material choices, order and placement. Each row has Details for the longer settings. Use Preview jobs to inspect the result, then Save jobs to retain the configuration. A preview does not confirm installed material or start a machine.

Assembly marks are auxiliary cut squares repeated on the material jobs. Use them to align separately cut pieces during assembly. They are distinct from optical or manual Print & Cut registration marks. Leave sufficient sheet clearance for artwork and marks; an outside-sheet warning must be resolved before production.

Assembly order describes how pieces are combined. Cut order controls preparation order. Sheet translation moves a job on the cutting sheet; the saved inverse translation relates it back to the assembly position. Review copies, weeding paths and marks together.

For heat-transfer vinyl, enable HTV and explicitly confirm the mirrored orientation. Check the intended face and final assembly before cutting. Mirroring is part of production preparation rather than a reason to alter the original artwork permanently.

## Choose and run a job in Cut

For a project with production jobs, Cut shows a Production job selector. Choose the intended job, install its material and press Material installed · Review job. HTV also requires the orientation checkbox. The selection prepares and reviews that job's geometry and settings; it does not start tool motion.

Changing jobs clears the previous review and mat-alignment acknowledgement. Opening or editing a project requires fresh preparation. Saving settings or opening a preview does not authorize an old job to run. If an assignment or placement is invalid, use Prepare jobs from Cut, correct it and review again.

Operations and settings shows the job's tools and pass counts. Change pass counts in Object properties. Materials hold stock identity, thickness and notes; choose tool/process settings explicitly for the actual machine and stock. The former Tool passes dropdown was a display-only choice and has been removed. It did not select execution scope.

A physical start requires the supported connection, current review and machine-specific checks. Fit and secure the requested tool before confirming its start prompt. Follow later tool-change prompts only after motion has stopped. Keep access to the machine's physical stop control.

Pause, resume, stop and recovery availability depend on the protocol and machine state. A lost connection or uncertain completion requires inspection and recovery; do not assume that a sent command proves the cut finished. Keep the application foregrounded during production.

## Drag knife compensation and overcut

Enable Knife compensation in the knife tool's advanced settings to use its offset and overcut. Offset is the distance between the holder's swivel axis and the blade tip, in millimetres. The blade's physical angle identifies the fitted blade; it does not change this compensation geometry or act as a kerf offset.

Overcut follows the beginning of a closed contour again to finish its closure seam. It is ignored for open paths. Offset and overcut remain stored when compensation is disabled, and apply when it is enabled again. Review the complete compensated motion bounds, including clearance outside the original artwork.

Use Calibrate knife in Tool library to compare offset samples, fix the best offset and then compare overcut. Check the final square, triangle and circle. Keep the fitted blade, force, speed and stock unchanged during a comparison, and use a fresh uncut area for every trial. Choose the smallest overcut that closes the shape cleanly. Software and simulator checks do not measure physical cut quality.

Offsets and overcuts smaller than the selected machine’s coordinate step may produce identical moves. Choose calibration settings at a meaningful scale for that plotter.

## Import artwork

| Input | Available result | What to check |
| --- | --- | --- |
| Foil Studio project | Editable project with saved settings and assignments | Version, mat and included objects |
| SVG | Supported original editable paths, solid colours and named layers, or print rendering | Units, holes, gradients, text and unsupported effects |
| DXF | Supported editable entities with source layers, RGB colours and an indexed palette | Units, source visibility and unsupported entities |
| PDF and compatible AI | Eligible original editable paths or rendered page for printing | Page selection, text, clipping and gradients |
| EPS and PostScript-compatible AI | Eligible original paths or print rendering | Fonts, unsupported operations and page geometry |
| CDR | Eligible editable curves or print rendering | Supported document content and page selection |
| PNG JPEG WebP GIF BMP ICO TIFF | Printable image or contrast tracing | Transparency, orientation, resolution and first frame |
| PSD | Merged printable image or supported aligned pixel layers | Layer effects, masks and compositing support |

Use Editable cut paths when the entire selected drawing can be preserved. Unsupported content can make this option unavailable. When the preview can be rendered, Render for printing keeps its appearance as printer artwork. A rendered image does not contain original editable vector contours.

Insert for printing preserves image colour and transparency. Use Trace instead to create paths from image contrast. Review smoothing, threshold, holes and small details before inserting traced geometry. Separate colors is no longer offered. Existing projects containing coloured paths remain editable.

Animated GIF and multipage TIFF imports use the first frame or page. PDF/drawing page selection is a separate import option. HEIC and AVIF depend on the Android device codec. If decoding is unavailable, export a supported image format. File extensions alone do not establish supported content.

Placement lets you retain original coordinates or fit artwork to the selected area. Verify scale against a known dimension. A source document never chooses arbitrary machine commands or overrides the selected app tool preset.

## Printing stickers and registration

Printer objects retain appearance for printing. Cutting contours must be explicitly provided or created; an image's white region does not automatically identify a removable background. Sticker offsets are cutting margins, not white ink.

Prepare the sheet at actual size and verify printer margins. Print the artwork and registration marks at 100 percent scale. Manual Print & Cut uses the supported four-mark workflow for FilmCut, Smart and the included Silhouette/Craft Robo profiles. Optical registration, AutoBlade and available tool stages depend on the exact model.

Use the app's registration workflow for the current sheet. Changing artwork, job, tool settings or the printed sheet invalidates earlier approvals. Assembly marks used for layered vinyl do not substitute for these registration checks.

## Plotters and connections

Select the exact vendor and model in Connection. The catalogue includes FilmCut/GRBL, supported Silhouette and VEVOR Smart devices, and named Graphtec, Roland, Summa, Skycut, USCutter, Teneth and HP profiles. The selected profile determines the protocol, connection types, work area and available operations. A catalogue entry or simulator test is not physical qualification of every model and firmware.

Bluetooth Classic serial, supported USB serial adapters, bidirectional USB printer interfaces, BLE and TCP are available only where the selected profile supports them. A BLE device cannot be used as Bluetooth Classic serial. Approve the Android permission for the selected device. Use a data-capable cable and a suitable phone adapter.

TCP endpoints must match the actual controller or transparent bridge. Use a trusted local network; TCP controller connections are not authenticated or encrypted. A local hostname may require a working local resolver. Bluetooth discovery on older Android versions can depend on Android location-related permission settings.

Load and unload actions are model/firmware dependent. Some machines require panel operations or explicit completion confirmation. Check the material position and working origin before alignment confirmation. Do not infer motion completion solely from a connection or command acknowledgement.

## Practise without a machine

Open Prepare, Connection setup and Start demo mode for the supported virtual workflow. The DEMO banner identifies it. Practise review, alignment confirmation, progress and tool prompts using independent sample artwork. Exit demo mode before explicitly connecting real hardware.

Demo mode and the external development plotter simulator serve different purposes. Demo is an in-app learning mode. External simulator tests check generated wire commands and state handling against protocol contracts. Neither measures cutting quality, real force, blade exposure or mechanical accuracy.

## Projects languages and purchases

Save important work explicitly. Android's document picker can use local storage or a document provider you installed. Recovery data helps restore interrupted work but does not replace exported backups. Clearing app data or uninstalling can remove private settings and recovery files.

Choose English, Polish, German or Spanish from Language, or follow the device language. Shared help and examples follow the interface language. User text, filenames and serialized project identifiers retain their original content.

The app is free to install. Free supports design/editing and previews. Basic is a permanent one-time purchase for named saves, export, printing and production. Optional monthly/yearly Pro includes Basic while active and adds Box/Craft wizard creation and regeneration. Restore purchases using the same Google Play account. Prices shown by Google Play depend on your account and region.

Earlier paid-download buyers can contact pratanczuk@gmail.com privately with the original Google Play app-order number to request the documented Basic migration. This is not a repeat purchase after each update. Do not post order details publicly.

## Troubleshooting and support

| Problem | Check |
| --- | --- |
| Start is disabled | Connection, controller state, selected job, material confirmation, review, entitlement and alignment |
| Imported job says No material | Existing null choice is preserved; choose stock explicitly in Material assignment or Prepare jobs |
| Job or assembly mark is outside the sheet | Mat dimensions, marks, translation, copies and production layout |
| Editable import is unavailable | Use supported original content or Render for printing; inspect the reported limitation |
| Bluetooth or USB device is missing | Exact model, supported transport, permissions and cable/adapter |
| Command was sent but completion is uncertain | Inspect the machine and use its recovery/completion workflow |
| Review expires | Prepare and review again after changing source, settings, connection or job |
| Printed artwork does not align | Actual print scale, margins, sheet identity and current registration |

Contact [pratanczuk@gmail.com](mailto:pratanczuk@gmail.com), or report a reproducible technical issue in [GitHub Issues](https://github.com/plotter-doctor/Foil-Studio/issues). Include app/Android version, plotter model/firmware, connection type and a small non-sensitive example. Public issues should not contain personal projects, purchase details or network credentials.
