# Foil Studio user manual

English · Updated 22 November 2026 · Version 0.1.150 (171)

[Home](../README.md) · [Release notes](release-notes.md) · [Four-language quick start](quick-start.md) · [Download PDF](manual/FoilStudio-User-Manual.pdf) · [Download Word](manual/FoilStudio-User-Manual.docx)

## Versions covered

This manual covers 0.1.150 (171). Check the [version guide](release-notes.md) for Google Play submission, approval and rollout status, and check the version installed on your device. Earlier versioned release records retain their original context.

## First project

1. In Design, choose Project → New and draw a small rectangle, or open an example from Help and examples. A new project's Default layer starts with the current material; Vinyl is the initial default.
2. Open Edit → Layers → Edit layer to check or change that layer's material. Objects inherit their layer's stock. Position the artwork on the mat and keep an exported backup of important work.
3. In Prepare, check Material, Cutting mat and the exact plotter model. Expand a card for its options. Production preview opens layout and Prepare jobs directly.
4. Open Connection setup. Use demo mode to practise without hardware, or explicitly connect your compatible plotter.
5. Review jobs in Prepare. Included cutting artwork needs an assigned layer material; otherwise a warning offers Layers and keeps you in Prepare. Choose the intended Job in Cut to preview only its artwork and assembly marks.
6. Inspect the preview, then press Start cutting. Complete the requested material/HTV, tool and mat checks. Edit tools and pass counts in Object properties or Tool library.
7. Start the job and follow the tool-installation prompts. Supervise the machine until completion.

Use a small test piece when choosing pressure, speed, blade depth or pass count. Pressure units and supported settings depend on the plotter. A material record describes stock and thickness. Choose the tool/process settings explicitly and test them on your actual stock.

## Design and selection

Tap artwork to select it. Use the selection controls to add or remove objects; drag from unused space for an area selection. Two fingers pan and zoom the view. Undo and Redo let you inspect a change and return to the earlier design.

Create shapes, outlined text, clipart and freehand paths using the design tools. Numeric dimensions and transforms provide precise placement. Alignment and distribution compare selected objects; layout tools can repeat artwork or fill a sheet. Review their preview before applying it.

Object properties hold the tool and process settings that determine production. Tools can include knife, pen, scoring, engraving and Printer, where supported. Printer artwork is for printed output rather than blade motion. Colours identify artwork visually; changing a colour alone does not choose pressure or tool type.

Objects keep the tool snapshot assigned to them. Editing a library record does not rewrite existing objects. To use the edited record, select it again in Object properties; Current object tool identifies a stored snapshot when it shares a name with an updated library record.

Path editing, offsets and Boolean operations require suitable geometry. Closed contours, holes, open strokes and very small details behave differently. Inspect generated contours after union, subtraction, offsets, tracing or simplification. The weeding tools add waste-removal paths, so include them in the preview check.

Box and Craft wizards create editable projects with fold/cut operations. Preserve the wizard's generated object relationships when regenerating. Test fit with your actual material thickness. Pro is required for wizard creation and regeneration; already-open artwork remains subject to the normal editing and output access rules.



Long-press selected artwork for the compact object menu, including Group and Ungroup. Ungroup separates actual groups. Split contours separates eligible ungrouped drawings into individual contours while retaining positions and tools. Filled artwork, text, QR, wizard, image and linked sticker objects are excluded. Use Undo to restore the original. Mixed-tool selections remain selected in Object properties; assigning one common tool is explicit.

## Layers materials and production jobs

Layers organize artwork and hold material assignments. Open Edit → Layers → Edit layer → Material. A material is a stock preset from the Materials library; a layer is an artwork group. Objects inherit the material of their layer, and moving an object to another layer gives it the destination layer's material. To use different stock for part of a design, place those objects on a separate layer. Object properties retains tools and process settings, rather than a second material override.

New projects put the current material on Default. New layers and editable imports use the current material where a new layer is needed. An explicitly cleared material remains unassigned; opening an existing project does not guess its stock. If an older project's layers show No material, assign them through Edit layer before reviewing cutting artwork.

A production job describes the artwork prepared on one sheet or material placement. It can include more than one design layer and more than one tool. Separate jobs do not merge just because their colours or materials match. Review layer stock and job membership together when preparing a multilayer sticker.

Material records contain stock identity, thickness and notes. Assigning a material does not replace an object's independently selected tool, pressure, speed or pass count. Stored material snapshots remain distinguishable from edited same-name library records.

Layer inclusion and visibility affect production eligibility. Excluded or print-only artwork does not become a cut merely because it belongs to a job. Review again after changing membership, tools, geometry or settings.

On a tablet or wide screen, the Design inspector shows a layer/object tree. Expand a layer to find its objects. Layer and object menus open their properties; Add layer creates a group, and Move to layer changes membership. Hold an object name and drag it onto the destination layer, or use the explicit move action. Undo and Redo retain the normal editing workflow.

## Prepare jobs and assembly marks

Open Production preview → Prepare jobs to inspect the short job list and assembly-mark settings. Each row has Details for the longer settings, assignments, order and placement. Set the artwork stock in Edit layer. Use Preview jobs to inspect the result, then Save jobs to retain the configuration. A preview does not confirm installed material or start a machine.

Assembly marks are auxiliary cut squares repeated on the material jobs. Use them to align separately cut pieces during assembly. They are distinct from optical or manual Print & Cut registration marks. Leave sufficient sheet clearance for artwork and marks; an outside-sheet warning must be resolved before production.

Assembly order describes how pieces are combined. Cut order controls preparation order. Sheet translation moves a job on the cutting sheet; the saved inverse translation relates it back to the assembly position. Review copies, weeding paths and marks together.

For heat-transfer vinyl, enable HTV and explicitly confirm the mirrored orientation. Check the intended face and final assembly before cutting. Mirroring is part of production preparation rather than a reason to alter the original artwork permanently.

## Choose and run a job in Cut

For a project with production jobs, Cut keeps the Job selector, the material name and a large preview visible. Choosing a job immediately filters the preview to its artwork and assembly marks. This preview choice does not confirm that its stock is installed and does not start motion.

Load the intended stock and press Start cutting. Complete the material confirmation; HTV also requires the orientation confirmation. The app prepares the current selected job and retains its tool, connection and mat checks. Review jobs remains in Prepare. If cutting artwork lacks a layer material, assign it through Layers first; selecting a job alone cannot bypass this check. Another unassigned job does not block a valid selected cutting job.

Changing jobs clears the previous review and mat-alignment acknowledgement. Editing or reopening a project requires fresh preparation. If an assignment or placement is invalid, open Prepare jobs, correct it and review again. Saving job settings or opening a preview does not authorize an old job to run.

Change tools, pressure, speed and pass counts in Object properties or Tool library. The main Cut view does not repeat blade settings or an Operations and settings summary. Device-specific options remain under Advanced settings where supported. The former Tool passes dropdown has been removed; it did not select execution scope.

A physical start requires the supported connection, current review and machine-specific checks. Fit and secure the requested tool before confirming its start prompt. Follow later tool-change prompts only after motion has stopped. Keep access to the machine's physical stop control.

Pause, resume, stop and recovery availability depend on the protocol and machine state. A lost connection or uncertain completion requires inspection and recovery; do not assume that a sent command proves the cut finished. Keep the application foregrounded during production.

## Drag knife compensation and overcut

Enable Knife compensation in the knife tool's advanced settings to use its offset and overcut. Offset is the distance between the holder's swivel axis and the blade tip, in millimetres. The blade's physical angle identifies the fitted blade; it does not change this compensation geometry or act as a kerf offset.

Overcut follows the beginning of a closed contour again to finish its closure seam. It is ignored for open paths. Offset and overcut remain stored when compensation is disabled, and apply when it is enabled again. Review the complete compensated motion bounds, including clearance outside the original artwork.

Use Calibrate knife in Tool library. A selected job or a design with one material supplies its actual stock; mixed or unassigned stock requires a material choice. Cancel preserves the source. The main trial sheet contains 30 × 30 mm squares: five columns vary offset and three rows vary pressure where the app controls it. With panel-controlled pressure, compare five offsets at one manually set panel pressure instead. Check blade exposure, the displayed parameter ranges, labels and complete sheet bounds before preparing the trial.

Prepare the sheet in Cut and start it explicitly. Use fresh uncut stock for every trial, including refinement and retries. After the plotter stops, return to calibration, confirm inspection and choose the labelled sample. First choose sufficient pressure for the intended cut, then the cleanest corners in that row. Review both selected values before saving.

The save receipt states the updated Tool library knife offset and the material/plotter scope of the saved pressure. Existing objects keep their tool snapshots. Reselect the updated library tool in Object properties with Knife compensation enabled; pressure applies only to the matching material, plotter and setup when settings are inherited from the tool. An explicit object pressure remains explicit. Check the effective pressure in Cut before starting. Overcut is still a separate tool setting for closed contours; use the smallest effective value on the actual material.

New calibration sheets include separate orientation strokes before each contour and pass. Leave their fresh trial area clear and review the complete sheet before cutting. New compensated production paths account for every nonzero turn, including shallow corners. Previously saved calibration sheets retain their geometry; regenerate a trial to use the current pattern.

Offsets and overcuts smaller than the selected machine’s coordinate step may produce identical moves. Coarse device grids and uncertain starting blade orientation can limit the result. Choose calibration settings at a meaningful scale and test the fitted blade on the actual stock; no uniform physical accuracy is promised.

## Prepare artwork for the plotter

Open Design → Edit → Prepare for plotter, or tap the wand beside Production preview in Prepare. Choose selected objects or all included artwork. Tolerance (mm) defaults to 0.01 mm and accepts 0.001–0.1 mm. Recover circular arcs replaces eligible dense circular contours with arcs; Simplify straight sections removes redundant points while retaining corners and endpoints.

Compare Before and After, the segment counts, error bound and protected/skipped contours. Apply saves preparation intent to the chosen artwork; it does not replace the original drawing. The next compiled cut uses those settings on the current geometry. Undo or Use original cut paths removes the preparation. Save the project to retain the setting across reopening.

Nearby details and holes are protected; uncertain contours stay unchanged. Open paths remain open and duplicate whole contours are retained. Images, guides, assembly marks and calibration samples are skipped. Trace a bitmap first when editable contours are needed. No cloud processing or learned model is used.

The displayed error bound compares prepared geometry with the original artwork. Device coordinate rounding and curve approximation add their own error. Supported native-arc outputs can reduce command counts; other protocols approximate arcs for their device grid. With knife compensation enabled, eligible recovered circular paths use continuous holder motion while real corners keep their swivels. These software bounds do not measure blade exposure, actual force or physical cutting quality.

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

Prepare the sheet at actual size and verify printer margins. Print the artwork and registration marks at 100 percent scale. Manual Print & Cut uses the supported four-mark workflow for FilmCut, Smart, the included Silhouette/Craft Robo profiles and compatible raw profiles, including GCC, with a calibrated pointer. Optical registration, AutoBlade and available tool stages depend on the exact model.

Use the app's registration workflow for the current sheet. Changing artwork, job, tool settings or the printed sheet invalidates earlier approvals. Assembly marks used for layered vinyl do not substitute for these registration checks.

## Plotters and connections

Select the exact vendor and model in Connection. The catalogue includes FilmCut/GRBL, supported Silhouette and VEVOR Smart devices, and named GCC, non-Smart VEVOR, Graphtec, Roland, Summa, Skycut, USCutter, Teneth and HP profiles. The selected profile determines the protocol, connection types, work area and available operations. For production, match the exact model, firmware configuration and connection.

Bluetooth Classic serial, supported USB serial adapters, one-way and two-way raw USB printer interfaces, BLE and TCP are available only where the selected profile supports them. A BLE device cannot be used as Bluetooth Classic serial. Approve the Android permission for the selected device. Use a data-capable cable and a suitable phone adapter.

TCP endpoints must match the actual controller or transparent bridge. Use a trusted local network; TCP controller connections are not authenticated or encrypted. A local hostname may require a working local resolver. Bluetooth discovery on older Android versions can depend on Android location-related permission settings.

Load and unload actions are model/firmware dependent. Some machines require panel operations or explicit completion confirmation. On VEVOR Smart, manual Tool up includes a short left-and-return carriage movement; clear the area before using it. The manual pressure control uses its displayed range, independently of object cutting settings. Check the material position and working origin before alignment confirmation. Do not infer motion completion solely from a connection or command acknowledgement.


## Manual control and device information

Machine control uses the same arrow pad for all plotters. Choose a jog distance: 0.1, 1, 5, 10, 50 or 100 mm, or the saved distance. Distance options stay in one row. Confirm the first manual action, then jog or lift/lower the tool without repeating that confirmation. FilmCut homing and work-origin changes always require separate confirmation. FilmCut pressure uses PWM, VEVOR Smart uses grams, Silhouette uses its native force scale, and HPGL/DMPL plotters use their panel settings. Manual pressure for VEVOR Smart 1–4 starts at 250 g and is adjustable within 250–500 g. On VEVOR Smart, Tool up requests a 0.025 mm carriage step left and an equal step right. Keep clearance on both sides of the carriage. On VEVOR models other than Smart, tool buttons request a small carriage step and return. Tool down may lift again at rest; later jogs use the requested tool state. After moving this plotter from its panel, reconnect before using app controls. Later jogs retain the tool state. FilmCut and Silhouette wait for controller readiness; VEVOR Smart and HPGL/DMPL require standstill confirmation when leaving a manual session. After Stop or an error, check the plotter before continuing. Stop sending cannot stop buffered HPGL/DMPL motion. Load material using the plotter panel.

Home raises the tool and returns to the logical origin established for this connection. This can differ from the artwork corner. It does not seek a limit switch or restore an origin from before reconnecting. Home becomes available after a normal move or job establishes the frame and you confirm standstill. Confirm the plotter is stationary after Home.

Review the tool sequence before starting. Fit and confirm the first tool. After each stage, wait until all movement stops and confirm completion. The next tool stays visible in Cut: choose Change tool, fit it and confirm before starting its stage. Uploading data does not confirm finished motion. Keep the material in place during tool changes.

USB printer interface supports one-way and two-way raw connections. One-way connections disable XON/XOFF and buffer queries. If a device offers several interfaces, select the one documented for the plotter. Match its language; USB detection does not identify HPGL or DMPL. IEEE 1284.4 is unavailable; vendor-specific USB is limited to explicitly supported GCC devices. Use USB–serial for serial adapters.

After connecting through a USB printer interface, open USB device information to read the reported product, manufacturer, model and command languages. The optional IEEE 1284 Device ID query may be unavailable; the connection still works. These details do not uniquely identify a unit or verify its plotter language. Choose the model and language yourself.

USB serial adapters use serial settings; direct USB printer connections do not use a baud rate. Non-Smart VEVOR models use the consolidated DMPL profiles; Smart keeps its distinct protocol. Connection fixes separate blocking reads from writes and avoid unsolicited printer-input polling. Device ID remains advisory and never automatically chooses a language.

## GCC profiles

Choose the exact GCC model and verify the coordinate axes with a small raised-tool move. Machine control supports repeated jogs, tool up/down and Return to origin. This returns to the prepared origin; it does not find a limit switch or restart the electronics. Reconnect after moving the head from the plotter panel.

GCC jobs use separate stages for different tools. Install and confirm each tool before its stage. Knife and pen select their own tool mode. For scoring or engraving, select the matching mode on the plotter panel. Force, speed and acceleration stay panel-controlled. Keep firmware blade offset and overcut off when the app compensates the knife.

Read material bounds is an optional idle query, available once per connection. It reports command-axis X and Y spans, not head position. Compare them with your selected coordinate axes and loaded mat; the query never changes the project. If the plotter does not reply, enter the usable mat size manually.

GCC uses manual Print & Cut with a calibrated pointer. Automatic AAS marks, segment scanning, automatic dual-holder switching, cut-off and hardware reset are not available. i-Craft and Nautilus use distinct command framing. These profiles still need a physical raised-tool check on your machine. A completed transfer does not confirm stopped motion.

## Machine geometry calibration

Draw a rectangle with a pen, measure X and Y between line centres, then enter both measurements. Keep controller scaling at 100%. Use the previous correction only if it was used for this test. New correction = test correction × requested / measured.

Measure X across the mat width and Y along its length. These are application axes; controller letters may differ.

FilmCut X/Y calibration starts at pen pressure 180. Adjust it for your pen and material before drawing.

Use the available mat controls here. Finish the test and wait for standstill before unloading to measure. After loading, check the origin and confirm the pen and sheet again.

Use a pen in the cutting holder to draw the cross. Without moving the sheet or changing the origin, raise the pen and move the laser pointer to the cross centre. Confirm standstill after moving. The saved pointer offset is used only for manual laser alignment; ordinary cuts are not shifted.

Calibration is saved per selected profile. Review the saved values in Plotter calibration before drawing another test.

Native optical alignment supplies the axis transform. Saved X/Y correction is used for ordinary and manually aligned cuts.

## Plotter setup in 0.1.150

For a GCC Puma II, choose the exact profile and its supported direct USB interface. New setups default to X forward and Y left. Verify the directions with the tool raised and the head at the prepared origin. The direct route sends jobs and manual commands.

On Graphtec CE LITE-50, enable the optional return in Cut if the plotter should move back to the reviewed origin with the tool raised. Check the return path and confirm completion after the plotter stops.

Check a cutting mat width warning against the profile and the loaded material. For Box Wizard work, matching knife operations can share one stage. The job review shows each stage and the corresponding tool confirmation.

Session diagnostics can include the model, transfer progress and USB–serial modem inputs such as CTS when the port opens. Device addresses, raw traffic and artwork are excluded.

## Practise without a machine

Open Prepare, Connection setup and Start demo mode for the supported virtual workflow. The DEMO banner identifies it. Practise review, alignment confirmation, progress and tool prompts using independent sample artwork. Exit demo mode before explicitly connecting real hardware.

## Projects languages and purchases

The app checkpoints the active project on this device when you edit, open a project or send the app to the background. Returning normally keeps the current design. If Android restarts the app, it restores the saved active artwork and its local-library identity, including changes checkpointed before the ordinary autosave delay. An explicit New establishes a blank active project. Prepared plans, installed-stock confirmations and mat alignment are not restored: review and confirm them again.

Basic and Pro save named projects in the private local library. Free can recover the active design without creating a named library save. Keep exported backups of important work; app-local recovery is not a cloud backup. Import/export can use Android's document picker and any installed document provider. Clearing app data or uninstalling can remove private projects, settings and recovery files.

The earlier app did not record the last-active project. After updating from it, open the desired saved project once to establish the active document. Existing library content remains available. Artwork restoration is separate from canvas pan/zoom and other transient view state. A corrupt session is preserved with a visible warning; starting a new project explicitly replaces that session slot.

Choose English, Polish, German or Spanish from Project → Language, or follow the device language. Help & examples is also in Project. These two entries are no longer duplicated in Advanced settings. Shared help and examples follow the interface language. User text, filenames and serialized project identifiers retain their original content.

The app is free to install. Free supports design/editing and previews. Basic is a permanent one-time purchase for named saves, export, printing and production. Optional monthly/yearly Pro includes Basic while active and adds Box/Craft wizard creation and regeneration. Restore purchases using the same Google Play account. Prices shown by Google Play depend on your account and region. About application shows Current plan: Free, Basic or Pro for the current access state.

Earlier paid-download buyers can contact pratanczuk@gmail.com privately with the original Google Play app-order number to request the documented Basic migration. This is not a repeat purchase after each update. Do not post order details publicly.

## Troubleshooting and support

| Problem | Check |
| --- | --- |
| Start is disabled | Connection, controller state, selected job, material confirmation, review, entitlement and alignment |
| Review warns that material is missing | Open Layers → Edit layer → Material for the included cutting artwork; older or explicitly cleared assignments are not guessed |
| App returned to an empty workspace | After upgrading from a version without active-project restoration, open the intended saved project once; active-project restoration applies to subsequent sessions. Check any recovery warning before starting New |
| Job or assembly mark is outside the sheet | Mat dimensions, marks, translation, copies and production layout |
| Editable import is unavailable | Use supported original content or Render for printing; inspect the reported limitation |
| Bluetooth or USB device is missing | Exact model, supported transport, permissions and cable/adapter |
| Command was sent but completion is uncertain | Inspect the machine and use its recovery/completion workflow |
| Review expires | Prepare and review again after changing source, settings, connection or job |
| Printed artwork does not align | Actual print scale, margins, sheet identity and current registration |

Contact [pratanczuk@gmail.com](mailto:pratanczuk@gmail.com), or report a reproducible technical issue in [GitHub Issues](https://github.com/plotter-doctor/Foil-Studio/issues). Include app/Android version, plotter model/firmware, connection type and a small non-sensitive example. Public issues should not contain personal projects, purchase details or network credentials.
