# Foil Studio user manual

Android 0.1.127 (148)  ·  7 November 2026

Use this manual to take a project from editable artwork to cutting, pen drawing, passive engraving or scoring. It covers Foil Studio for Android 0.1.127 (148), including object settings, production layouts, Print & Cut and the current plotter connection workflows.

## 01 Your first project

1. Choose the target plotter before setting tools. Open a bundled example or create a small shape, set its exact size and assign its tool in Object properties.

2. In Prepare, check the loaded cutting mat, design bounds, tools and copies. Material belongs to a layer: open Layers, then Edit layer to assign it. New projects give Default the current material. Review job explains any missing assignment; test the actual stock before production.

3. In Cut, choose the intended Job when the project has several jobs. The preview shows that job and its assembly marks. Confirm the installed stock when requested, review the tool stages, fit the requested tool and start explicitly. Observe the plotter and confirm completion only when it has stopped.

4. Save your project and keep an exported backup. Open Help for interactive lessons and editable examples. The example names shown in this manual identify the matching in-app projects.

### Plans and purchases

Free includes editing and preview. Basic is a one-time purchase for saving, exporting, printing and starting plotter jobs. An active Pro subscription includes Basic features and creation or regeneration with Box wizard and Craft wizard. Open Plans to view offers or restore purchases.

## 02 In this manual

01  Your first project

03  Cut draw engrave and score

04  Tool settings and knife calibration

05  Select and draw shapes

06  Text layouts and wizards

07  Import save and reopen projects

08  Trace images and edit curves

09  Prepare and preview production

10  Layers materials and jobs

11  Stickers and QR labels

12  Print and Cut registration

13  Connect and control the plotter

14  HPGL and DMPL setup and operation

15  Silhouette and AutoBlade

16  VEVOR Smart workflows

17  Help and plotter support

## 03 Cut draw engrave and score

### Cutting

Assign a knife to the cutting contours. Drag knife 45° is the default for new shapes; choose the blade that suits the material. Set blade exposure, passes, force and speed for the selected plotter. Test a small contour, check its corners and closure, then review and start the job. Use knife calibration to refine offset and overcut.

### Drawing

Assign a pen to the lines or outlines you want to draw. Fit the pen in the holder required by the selected plotter, then test its contact and ink flow on the same material. Review the pen stage and start it. Image tracing follows outlines: a thick printed line can produce two drawn edges.

### Engraving

Assign an engraving tool to the paths to be marked. Use a compatible passive engraving tip and secure a suitable test piece. Check clearance and tool contact, then test the force, speed and passes supported by your model. Inspect the mark before reviewing and starting the full engraving stage.

### Scoring

Assign a scoring stylus to fold lines and a knife to the outer contour. Test the crease on matching cardstock and check that it folds cleanly. Keep the sheet fixed between stages. A box wizard can generate separate scoring and cutting paths; inspect its assembly instructions before folding.

### Combined jobs

A combined job runs pen drawing, engraving, scoring and then knife cutting. Review every stage and confirm each requested tool change. Printer artwork belongs to printed output; Guide objects are excluded from plotter output.

## 04 Tool settings and knife calibration

### Object tools and properties

Estimated pressure: 50–1000 g. All FilmCut variants use the same PWM mapping; actual force is not measured.

If Save does not close the editor, correct the highlighted pressure field. Its range follows the selected pressure units.

Pressure units remain selectable for FilmCut and VEVOR. Changing units does not convert the number; check the force before saving.

Objects use their assigned tool settings where supported by the selected model. Turn off Use tool defaults in Object properties to override them. Other models keep their saved values. HPGL/DMPL profiles use force and speed from the plotter panel; Object properties hides these values and the switch. Inspect or change assigned tool settings in Object properties.

Objects keep their assigned tool snapshot. After editing a library tool, select its updated record in Object properties.

On a tablet or wide screen, expand a layer in the Layers tree. Tap an object to select it; its selection button adds or removes it. Layer and object menus open properties. Use Add layer or Move to layer. Hold the object name to drag it onto a layer. Moving uses the destination layer material.

Choose the target model in Connection. Tools show only its settings and remember values separately for each model. Physical speed is shown in mm/s; Silhouette uses native force and speed scales. Old raw pressure values retain their meaning. FilmCut grams are an estimate, not measured force.

Select artwork and open Edit properties. Set its name, colour, tool and number of passes. Speed and pressure are available for models that accept them from the app.

Each object keeps its own tool settings. A colour helps organise the drawing; it does not assign a tool.

Printer objects belong to printed output. Guide objects do not cut. Check the preview and tool assignments before starting a job.

Example in Help: One more chapter

### Knife calibration

Open Tool library and choose Calibrate knife below the selected knife. Check blade exposure, force and speed on one sample first. Tip width is not used for knife compensation.

Enable Knife compensation to apply offset and overcut. Offset is the distance from the holder axis to the blade tip; overcut repeats the start of a closed contour. Open paths do not receive overcut. Blade angle does not change this geometry.

New calibration sheets orient the blade in fresh waste areas before every test contour and pass. Keep these areas clear and use fresh material for every trial. Saved older sheets keep their original layout; generate a new calibration to use orientation strokes.

Compare the numbered offset samples and choose the cleanest corners. Keep force, speed, blade depth and material unchanged. Refine the comparison or choose None is good to try another range.

With offset fixed, compare overcut samples at the marked closure seam. Choose the smallest overcut that closes the shape cleanly, then check the final square, triangle and circle.

Send each trial to the normal Cut screen and start it explicitly. After it finishes, return to calibration. Save the chosen offset and overcut to the tool only after checking the final sample. Export a trial to keep its exact settings; the original project is preserved.

Every trial uses the same positions. Load a fresh, uncut area or new material before each trial, including refinement and retries.

Choose the material for knife calibration. It stays fixed for all trials.

The bundled calibration sheet is a preview with guide objects. Use Calibrate knife to generate a cutting trial for your selected tool and plotter.

Example in Help: Knife calibration

## 05 Select and draw shapes

### Select move and resize

Tap an object to select it, then drag it to move it. Drag across unused mat space to select several objects.

Double-tap an object to reveal resize handles. Drag a handle, then choose Finish resizing to return to moving.

Use two fingers to pan and zoom. Zoom in before working on small details.

Hold the Edit points or Select area label for gesture guidance. With a mouse, hover over the label.

Enter a width or height to set the selection size. Keep proportions updates the other dimension. Open Scale factor for sliders and percentages. The selection centre stays fixed; groups resize together. Apply creates one undo step.

New configurations use a visible 1 mm line grid, stronger lines, slim rulers and 1 mm grid snapping. Open Grid & scale to change them. Saved preferences are preserved. Zoom may hide fine grid lines without changing snap spacing.

Open Shape tools with the small tab on the left frame: tap it or swipe right from it. Compact icons fit the mat height. On short screens, scroll the tool list; the close arrow stays at the top. Swipe left or tap the arrow to close the panel.

On a tablet or wide screen, expand a layer in the Layers tree. Tap an object to select it; its selection button adds or removes it. Layer and object menus open properties. Use Add layer or Move to layer. Hold the object name to drag it onto a layer. Moving uses the destination layer material.

Open Details for extra guidance. Help contains full lessons and editable examples.

Example in Help: A little thank you

### The object menu

The object menu groups properties and content editing first, then Move, Scale and Rotate, then Duplicate and stacking. Delete is last. Open Edit for Align and distribute or Fill sheet.

Select an object, then hold your finger on it without moving. With a mouse, press and hold.

In the object menu, choose Move for exact horizontal and vertical offsets or Scale for a width, height or scale factor. Grouped artwork changes together; ungroup it to edit individual parts.

You can also find editing commands in Edit. The down arrow at the edge of a long menu reveals more options.

Example in Help: A little thank you

### Shape tools

Arc draws a 90° elliptical quarter inside the dragged bounds. Use Add → Arc to enter another angle.

Freehand keeps drawing active and saves each stroke when you lift your finger. It follows your finger without grid snapping. Tap the active Freehand icon again or Exit drawing to finish.

Choose Rectangle, Circle, Ellipse, Line, Arc, Triangle or Star. The panel closes. Drag on the mat to preview the shape; release to add one object and return to selection. A tap alone adds nothing.

Grid snapping follows Grid & scale. Start inside the mat; the other end stays within its edges. Circles keep equal width and height. Hold the completed object and choose Scale or Move for exact dimensions and offsets.

Two fingers cancel an unfinished shape and pan or zoom the view. To cancel drawing, reopen Shape tools and tap the highlighted shape again. Undo removes a completed shape in one step.

Example in Help: Three shapes and a reference

## 06 Text layouts and wizards

### Edit text

Choose one parametric text object.

If you have edited the text contours manually, create new text to change the wording, or keep the existing contours.

Tracking requires a bundled font with shaping support.

Select one text object and choose Edit text. Capital height, width, cluster spacing and the nine anchors update one preview.

Apply creates one undo step. Cancel preserves the original text, tool and contours.

Open Details for extra guidance. Help contains full lessons and editable examples.

In a short window, scroll the form to reach its actions. Keyboard entry keeps the same draft.

Example in Help: Edit text

### Arrange and repeat

Select artwork, then use the Align icon beside Undo and Redo. The action bar stays within the canvas width and wraps when space is limited.

Choose Relative to, then tap an alignment or distribution icon. Hold an icon for its name; swipe the alignment strip to reveal more icons. Top means the largest project Y.

Use Layout options for usable-area margins or a fixed gap. Toggle the arrow icon for horizontal or vertical distribution. To choose a reference, select Reference object, tap the pointer icon and then an object in the preview; it stays still.

Inspect the large preview or open its full-screen icon. The check mark applies one undoable edit; the cross cancels without changing the project.

Select several objects and open Edit → Layout. Align, space or repeat artwork, then inspect the preview before applying.

Use Group to keep a composition together. Use Duplicate to make an editable copy. Undo restores the previous edit.

The Bloom example uses repeated, rotated petals. Try changing one petal, then compare it with the others.

Example in Help: Bloom

### Fill a sheet with one motif

The original counts as the first copy. Choose a total or calculate the maximum; gaps and four margins stay explicit.

Other included artwork blocks grid cells. Apply creates one undo step and keeps groups and linked artwork together.

Example in Help: Twenty-four labels

### Editable project wizards

Add → Box wizard and Craft wizard create parts with separate cutting, scoring, drawing or printing roles.

Select a generated part and reopen its wizard from Edit. Change dimensions, quantities or sheets and inspect the preview.

Regeneration can replace manual edits. Read the confirmation and assembly instructions before applying changes.

Open Details for setting explanations. In the box wizard, open Assembly for folding instructions.

Choose a no-glue box for captured corners and locking walls. Start with the lock-fit coupon, enter measured stock thickness and adjust lock clearance. Lock width controls the retaining tongues; lid clearance remains separate.

Four returned walls and folded gussets offer different corner constructions. The drawer uses two separate folded seam keys; fit them before inserting the tray. The organizer captures divider ends under its walls. The hexagonal box uses across-flats dimensions and has a separate lid.

Use the small fit sample to check folds and joints on the actual stock. Extra layers do not establish a load rating. The presentation wallet closes with a broad tuck tongue and is intended for light, flat contents.

The handle box is an open tray with a separate locking handle. Pass each handle tongue through both aligned wall slots and check its shoulders. Test your stock and contents before carrying; no load rating is specified.

Example in Help: A gift with a window

## 07 Import save and reopen projects

### Keep your own copy

Editable drawing import keeps supported solid colors, source layers and original contours. Review the assignments in Layers and prepare the jobs before cutting.

PDF, EPS, compatible AI and CDR offer editable paths when the whole selected page can be preserved. Unsupported text, images, clipping, gradients or effects keep Render for printing available. Stroke width is not a cutting offset.

DXF keeps source layers and colors using a fixed preview palette. CAD plot styles and unsupported entities are not reproduced.

Import PSD layers keeps supported pixel layers as separate aligned printable images, including their names and visibility. For unsupported layer effects, insert the merged image instead.

Insert for printing preserves image colors and transparency. Use Trace instead to create cutting or drawing contours from contrast.

Editable SVG import keeps solid RGB colors and named layers. Review the assignments in Layers and prepare the jobs before cutting.

SVG fills keep their holes and alignment as editable contours. If a shape has both fill and stroke, its fill color is used. Stroke widths, transparency, gradients and effects require Render for printing for their original appearance.

SVG previews include artwork beyond the source page. Object clipping and the original proportions are preserved.

Drawing previews use a white background. CDR includes printable artwork beyond the source page; DXF includes the full model-space drawing. The rendered image inserted for printing matches the preview.

Import image accepts PNG, JPEG, WebP, GIF, BMP, ICO, TIFF and PSD merged previews. Animations and multipage TIFF use the first frame or page. HEIC and AVIF depend on the device. Camera import uses the full-size photo.

Drawing files are selected without a file-type filter so Android can show CDR and AI files too. DXF print previews include geometry on both sides of the drawing origin.

For editable drawings outside the sheet, choose Fit drawing to sheet to keep every contour visible. This may reduce dimensions. Keep original coordinates preserves the source size and placement. A blank AI PDF preview needs a new export or another format.

Choose Editable cut paths to keep supported vectors, or Render for printing to insert the shown image. Set the image width, inspect small details, then insert.

Open an example to explore it. The bundled original stays available; save your edited version as your own project.

The project name is shown at the top. A check mark means saved; an asterisk means unsaved changes.

The app saves the active project on this device for returning from the background or restarting. After restarting, review the job and confirm the installed material and mat alignment again.

Opening another project asks about unsaved work. Use Project → Save or Save as when available for your plan.

Language changes affect the interface and help. Your text, object names and file names stay unchanged.

Example in Help: A little thank you

## 08 Trace images and edit curves

### Edit curves and nodes

For camera tracing, use even light, a contrasting background and face the design straight on. Start with Auto contrast, compare the image with its paths and pinch to inspect details. Use simpler detail if the cutting point limit is exceeded. Speck removal is optional and keeps holes. Choose Cut outlines for a knife or Draw outlines for a pen. Tracing follows outlines, so thick lines have two edges.

Tracing shows progress while preparing the preview. You can cancel or change the threshold; only the newest preview can be inserted.

Trace starts with smoothing enabled at 300%. Change Smoothing strength or turn Smooth outlines off; the preview updates before insertion. Compare Image with paths and check small details. Smooth curves in Edit also keeps the assigned tool, force and speed.

Image tracing smooths pixel stair-steps into cutting paths while retaining corners, holes and separate shapes. Review the traced preview before inserting; use print-only import to keep the image appearance. Large photos are resized automatically to fit the project.

Select editable artwork and choose Edit points. Drag a node to adjust the contour; zoom in for precise changes.

Hold the Edit points or Select area label for gesture guidance. With a mouse, hover over the label.

Curve approximation in Application settings controls new circles, ellipses and Bézier curves, and arc-to-line conversion for plotters. Default: 0.01 mm; smaller values produce more segments. Exact FilmCut arcs and existing line drawings stay unchanged. Changing accuracy requires reviewing the job again. Device rounding adds its own error.

Add → Bézier curve creates a curve from control points. Keep a copy before simplifying or smoothing a complex shape.

Open Details for extra guidance. Help contains full lessons and editable examples.

Example in Help: Bloom

## 09 Prepare and preview production

### Guided

Prepare uses compact material, cutting mat and plotter controls. Expand Material or Cutting mat for more settings. Open Production preview directly for layout, jobs and guided preparation.

Choose the artwork to prepare. Your design remains editable.

Select a material and check each object’s tool settings. Test the setup on a small piece of the actual stock.

Set total copies, orientation, margins and weed cuts in the shared production layout.

Check geometry and motion bounds. Review job retains all existing readiness and registration checks.

Review the job, change tools when prompted and start explicitly. Next never starts movement.

In a short window, scroll the form to reach its actions. Keyboard entry keeps the same draft.

Example in Help: Guided

### Production preview

Design remains unchanged until you choose Apply layout to design.

Check small details, edge clearance and tool settings on a test piece.

Open Details for extra guidance. Help contains full lessons and editable examples.

Example in Help: Production preview

## 10 Layers materials and jobs

### Layers and jobs

Assign a material in Edit layer. Every object inherits its layer material. Moving an object to another layer changes its material; tools and pass counts stay with the object.

Editable SVG import keeps solid RGB colors and named layers. Review the assignments in Layers and prepare the jobs before cutting.

SVG fills keep their holes and alignment as editable contours. If a shape has both fill and stroke, its fill color is used. Stroke widths, transparency, gradients and effects require Render for printing for their original appearance.

Editable drawing import keeps supported solid colors, source layers and original contours. Review the assignments in Layers and prepare the jobs before cutting.

Insert for printing preserves image colors and transparency. Use Trace instead to create cutting or drawing contours from contrast.

Assembly marks are auxiliary cut squares, not optical Print & Cut marks. Each material change requires confirmation.

Confirm the mirrored HTV orientation.

Assembly order and cut order are separate. Use the saved inverse sheet translation to align the layers.

New layers start with the current material. Change a layer material in Edit layer.

New projects start with the current material on the Default layer. Assign any missing material in Edit layer before reviewing the job.

Jobs inherit material from their layers. Change the material in Edit layer.

Prepare uses compact material, cutting mat and plotter controls. Expand Material or Cutting mat for more settings. Open Production preview directly for layout, jobs and guided preparation.

Save job settings in Prepare jobs. In Cut, choose a production job, confirm the installed material, review the job and check mat alignment before starting.

Cut keeps the Job selector, material name and a large preview visible. Change tools and pass counts in Object properties.

Choose a job in Cut to preview only its artwork and assembly marks. Confirm the installed material separately before reviewing and starting the cut.

Layers keeps artwork organization and material assignments together. Open Edit layer for material assignment. Prepare jobs controls assembly marks, job order and sheet placement.

On a tablet or wide screen, expand a layer in the Layers tree. Tap an object to select it; its selection button adds or removes it. Layer and object menus open properties. Use Add layer or Move to layer. Hold the object name to drag it onto a layer. Moving uses the destination layer material.

Artwork color, material and production job are independent. Several design layers can share a job, and the same material can be used in separate jobs.

Open Details for extra guidance. Help contains full lessons and editable examples.

In a short window, scroll the form to reach its actions. Keyboard entry keeps the same draft.

Example in Help: Layers and jobs

## 11 Stickers and QR labels

### Make a sticker

The selected objects form one sticker. Import artwork first, then select it here.

The offset is a cutting margin; it does not add white ink.

One sheet at 1:1. Paper size and margins are saved in Prepare; registration space is reserved. Recheck margins whenever you select a different printer.

Print artwork and alignment marks, then use the existing manual Print & Cut registration. Preview never starts a cut.

Silhouette masks are explicit; an opaque image does not identify its background.

Label and sticker wizards can apply their draft and continue to Make a sticker or QR label.

Use Preview & print, verify the sheet ID and 100% scale, then confirm printing and printer margins before continuing to alignment.

Printing requires Basic or Pro. Open Plans to restore your purchase or choose a plan.

Open Details for extra guidance. Help contains full lessons and editable examples.

In a short window, scroll the form to reach its actions. Keyboard entry keeps the same draft.

Example in Help: Make a sticker

### QR label

I checked the complete encoded payload.

Separate pieces and holes remain. Keep a light background and the full quiet zone during assembly.

Minimum detail is unvalidated for this material. Make a test and independently scan the produced QR.

The quiet zone is four modules on every side and stays inside the chosen size. Regeneration is explicit.

Size includes the quiet zone.

Example in Help: QR label

## 12 Print and Cut registration

### Manual Print Cut

For manual Print & Cut, print at actual size and confirm the margins. Load the sheet without a tool and align the holder centre to marks A, B, D and C. Small jogs refine each position; capture only after the plotter stops.

The fourth mark checks alignment within 0.50 mm. Fit the tool without moving the sheet, then confirm Start cutting. Use one holder; tool changes with different physical offsets require a new alignment.

Reconnecting, moving material, editing the project or leaving the app expires manual alignment. Start again instead of reusing old positions. Position tracking is based on commands and operator observation, not an optical sensor.

Example in Help: Manual Print & Cut

### Optical Print Cut

Mark settings are saved with the project. Reopening Cut requires printing and confirming the current sheet again; alignment and loading confirmations are never restored automatically.

Optical Print & Cut omits the blade-setting stroke at the mat origin and cut-only mirroring so paths match the printed sheet. Ordinary jobs keep their existing settings.

In Cut, open Advanced settings, then Silhouette options and enable Optical Print & Cut. Set mark positions, print the registered sheet at actual size, then confirm it is loaded. Editing the project or marks requires a new print. XY corrections apply only in the app, in printed-sheet coordinates.

Print the current sheet at 100%, aligned to the top-left paper corner. Printer margins must leave all marks visible. Keep artwork 22 mm inside the marks. A fresh three-mark scan runs before each stage; failed scans never authorize cutting.

Advance material moves the loaded sheet with the tool raised and sets a new origin. It requires a clear path and confirmation of standstill afterwards. Use the plotter panel to load or eject. Optional return to origin runs after the final stage.

By default, check physical standstill and choose Done after transfer. Complete on device-ready status can finish each stage automatically after the final ready reply; it does not independently measure motor movement. Failures and Stop always keep observation required.

Example in Help: Optical Print & Cut

## 13 Connect and control the plotter

### From design to output

Materials covers adhesive and heat-transfer films, sticker media, paper, board, fabric and specialty sheets. Nominal thickness describes a stock example; edit it to match your sheet. Thickness not set means measure the stock first. Film references exclude the liner and may exclude adhesive; include all layers when checking tool clearance.

Selecting a material does not set cutting force, speed or blade depth. Set these for the selected plotter in the tool or object settings, or on the plotter panel. Use a small test cut to choose passes and cut depth; keep the backing intact for a kiss cut. Check mirroring for heat-transfer film.

New projects start with the current material on the Default layer. Assign any missing material in Edit layer before reviewing the job.

In Plotter connection, choose vendor, model and connection, then select a device and Connect. Device lists refresh automatically while disconnected and the app is visible; Refresh devices starts another search. Grant Bluetooth access when requested. For USB, choose Connect and allow Android access; the connection continues automatically. Protocol settings and FilmCut connection options are grouped below. Disconnect before changing the plotter. Connected confirms the link, not completed movement. Auto-connect is available for FilmCut and VEVOR Smart Bluetooth and never resumes a job.

FilmCut job G-code applies only to FilmCut. Saved Header and Footer commands remain available when you switch back; other plotters do not send them.

Choose the loaded size in Prepare → Cutting mat. Work area presets cover registered plotter widths; change the length with Resize mat or save a custom mat. These sizes describe the usable design area, not the outside of a carrier mat.

In Mat library, tap a record to apply it. With large text or a short window, section icons switch between materials, tools and mats; the plus icon adds a custom record. Hold an icon for its name.

Machine control uses the same arrow pad for all plotters. Choose a jog distance; the saved distance is used within the selected plotter’s supported range. Confirm the first manual action, then jog or lift/lower the tool without repeating that confirmation. FilmCut homing and work-origin changes always require separate confirmation. FilmCut pressure uses PWM, VEVOR Smart uses grams, Silhouette uses its native force scale, and HPGL/DMPL plotters use their panel settings. Manual pressure for VEVOR Smart 1–4 starts at 250 g and is adjustable within 250–500 g. On VEVOR Smart, Tool up requests a 0.025 mm carriage step left and an equal step right. Keep clearance on both sides of the carriage. Later jogs retain the tool state. FilmCut and Silhouette wait for controller readiness; VEVOR Smart and HPGL/DMPL require standstill confirmation when leaving a manual session. After Stop or an error, check the plotter before continuing. Stop sending cannot stop buffered HPGL/DMPL motion. Load material using the plotter panel.

Design creates the artwork. Prepare checks layout and tools. Cut contains the job preview and controls.

Inspect every tool stage and choose settings suitable for your material. Practise with the virtual plotter before using hardware.

Examples are learning designs, not calibrated material presets. Test a small scrap and check printed alignment before production.

Open Details for extra guidance. Help contains full lessons and editable examples.

Example in Help: One more chapter

## 14 HPGL and DMPL setup and operation

### HPGL DMPL plotters

In Plotter connection, choose vendor, model and connection, then select a device and Connect. Device lists refresh automatically while disconnected and the app is visible; Refresh devices starts another search. Grant Bluetooth access when requested. For USB, choose Connect and allow Android access; the connection continues automatically. Protocol settings and FilmCut connection options are grouped below. Disconnect before changing the plotter. Connected confirms the link, not completed movement. Auto-connect is available for FilmCut and VEVOR Smart Bluetooth and never resumes a job.

USB printer interface connects directly to a standard bidirectional USB printer interface with bulk input and output. Vendor-specific USB interfaces still need their own driver. Match the plotter language and use USB–serial for serial adapters.

For CE LITE-50, choose its Graphtec profile and USB connection. Select HPGL and LOWER LEFT origin on the plotter. Keep the profile axes: X forward, Y right. USB transfer follows the free buffer space reported by the plotter. Set force and speed on its panel. Work area 498 mm covers the maximum cutting width; resize its length to match the loaded material, up to 3000 mm.

For HPGL/DMPL, the project mat sets the cutting and Machine control bounds and the width used for axis conversion. Connection keeps protocol and transport settings. Match the loaded usable area to the project mat. Model limits are checked before movement.

Choose the loaded size in Prepare → Cutting mat. Work area presets cover registered plotter widths; change the length with Resize mat or save a custom mat. These sizes describe the usable design area, not the outside of a carrier mat.

In Mat library, tap a record to apply it. With large text or a short window, section icons switch between materials, tools and mats; the plus icon adds a custom record. Hold an icon for its name.

Machine control uses the same arrow pad for all plotters. Choose a jog distance; the saved distance is used within the selected plotter’s supported range. Confirm the first manual action, then jog or lift/lower the tool without repeating that confirmation. FilmCut homing and work-origin changes always require separate confirmation. FilmCut pressure uses PWM, VEVOR Smart uses grams, Silhouette uses its native force scale, and HPGL/DMPL plotters use their panel settings. Manual pressure for VEVOR Smart 1–4 starts at 250 g and is adjustable within 250–500 g. On VEVOR Smart, Tool up requests a 0.025 mm carriage step left and an equal step right. Keep clearance on both sides of the carriage. Later jogs retain the tool state. FilmCut and Silhouette wait for controller readiness; VEVOR Smart and HPGL/DMPL require standstill confirmation when leaving a manual session. After Stop or an error, check the plotter before continuing. Stop sending cannot stop buffered HPGL/DMPL motion. Load material using the plotter panel.

Plotters without relative jog use X and Y target coordinates with Move; these fields are targets, not a position readout.

In Machine control, Target coordinates are X and Y destinations. Open Details for coordinate guidance.

Skycut, USCutter and Teneth presets support basic cutting and pen jobs. Set the active tool, force and speed on the plotter. Camera alignment and automatic tool changes require additional model-specific support.

For HPGL devices with documented ESC.B support, enable Buffer control in Protocol settings. The connection must return decimal free-byte counts ending in CR. This replaces timed pacing with queries before blocks of up to 256 bytes, for cutting and Machine control. XON/XOFF remains available when supported. A full buffer is polled every 100 ms, for up to 60 seconds; a missing reply stops transfer after 5 seconds. Errors close the connection without replay. Free buffer space never confirms motion completion. Leave this option off for other devices and DMPL.

In Generic Cut, the percentage measures data sent, not completed motion. After all data is sent, an activity bar stays visible while waiting for cutting to finish. Confirm completion only after the plotter has finished all motion. An interrupted or restored job is marked unconfirmed. No elapsed-time estimate or incoming byte automatically completes a job.

Choose the exact vendor and model, or Generic with HPGL or DMPL when no preset is listed. Named presets define language, scale and available connections; they do not identify the attached device. Graphtec includes Craft Robo with its own connection workflow. VEVOR Smart uses its own protocol; KH, KI and SK presets use the language shown for that model. Match the plotter panel settings shown in Protocol settings. Set the loaded working area, tool, force and speed on the plotter. USB availability depends on the selected model. Choose one of its available connections.

For named HPGL/DMPL profiles, check Coordinate axes before connecting. These are the positive command directions viewed from the front: forward means away along the feed axis. Presets use documented axes where available; otherwise choose explicitly. Match the origin on the device and turn off device rotation, mirroring and scaling. Check a small pen-up movement before a job. Serial requires a supported USB–serial adapter; other options use a transparent SPP adapter or raw TCP bridge.

For HPGL/DMPL, enable XON/XOFF or ESC.B only when the device and connection support it, and set the transfer rate for the buffer. Machine control uses the shared jog and tool-lift controls. Stop sending closes the link; stop buffered motion on the plotter panel. Confirm standstill after a job or when leaving manual control. Each tool stage starts separately; interrupted jobs never resume automatically.

Example in Help: HPGL / DMPL plotters

## 15 Silhouette and AutoBlade

### Silhouette Craft Robo first job

In Plotter connection, choose vendor, model and connection, then select a device and Connect. Device lists refresh automatically while disconnected and the app is visible; Refresh devices starts another search. Grant Bluetooth access when requested. For USB, choose Connect and allow Android access; the connection continues automatically. Protocol settings and FilmCut connection options are grouped below. Disconnect before changing the plotter. Connected confirms the link, not completed movement. Auto-connect is available for FilmCut and VEVOR Smart Bluetooth and never resumes a job.

Machine control uses the same arrow pad for all plotters. Choose a jog distance; the saved distance is used within the selected plotter’s supported range. Confirm the first manual action, then jog or lift/lower the tool without repeating that confirmation. FilmCut homing and work-origin changes always require separate confirmation. FilmCut pressure uses PWM, VEVOR Smart uses grams, Silhouette uses its native force scale, and HPGL/DMPL plotters use their panel settings. Manual pressure for VEVOR Smart 1–4 starts at 250 g and is adjustable within 250–500 g. On VEVOR Smart, Tool up requests a 0.025 mm carriage step left and an equal step right. Keep clearance on both sides of the carriage. Later jogs retain the tool state. FilmCut and Silhouette wait for controller readiness; VEVOR Smart and HPGL/DMPL require standstill confirmation when leaving a manual session. After Stop or an error, check the plotter before continuing. Stop sending cannot stop buffered HPGL/DMPL motion. Load material using the plotter panel.

Cut keeps a large preview visible. Edit tools and passes in Object properties. Advanced settings contains mat settings, optical registration, return to origin and device-ready completion.

For Bluetooth LE, enable Bluetooth in Android and choose Bluetooth LE in Connection. Device lists refresh automatically and keep your selection until you change the model or connection. Choose Refresh devices to grant access or search again. Choose USB in Connection to search USB devices only. Initial BLE error 133 allows up to three connection attempts. Later failures never replay commands or resume a job.

Mark settings are saved with the project. Reopening Cut requires printing and confirming the current sheet again; alignment and loading confirmations are never restored automatically.

Optical Print & Cut omits the blade-setting stroke at the mat origin and cut-only mirroring so paths match the printed sheet. Ordinary jobs keep their existing settings.

In Cut, open Advanced settings, then Silhouette options and enable Optical Print & Cut. Set mark positions, print the registered sheet at actual size, then confirm it is loaded. Editing the project or marks requires a new print. XY corrections apply only in the app, in printed-sheet coordinates.

Print the current sheet at 100%, aligned to the top-left paper corner. Printer margins must leave all marks visible. Keep artwork 22 mm inside the marks. A fresh three-mark scan runs before each stage; failed scans never authorize cutting.

Advance material moves the loaded sheet with the tool raised and sets a new origin. It requires a clear path and confirmation of standstill afterwards. Use the plotter panel to load or eject. Optional return to origin runs after the final stage.

By default, check physical standstill and choose Done after transfer. Complete on device-ready status can finish each stage automatically after the final ready reply; it does not independently measure motor movement. Failures and Stop always keep observation required.

Silhouette changes force and speed between objects in the same tool stage. Passes repeat each outline automatically. Tool, holder, depth and process-order changes can require separate stages.

Objects use their assigned tool settings where supported by the selected model. Turn off Use tool defaults in Object properties to override them. Other models keep their saved values. HPGL/DMPL profiles use force and speed from the plotter panel; Object properties hides these values and the switch. Inspect or change assigned tool settings in Object properties.

Objects keep their assigned tool snapshot. After editing a library tool, select its updated record in Object properties.

AutoBlade is available for knife stages on Cameo 3, 4, 5 and Portrait 2, 3, in holder 1 only. Enable it in the tool or object settings and choose depth 0–10. This scale is not millimetres.

Cameo 4, Cameo 5 and Portrait 3 must report AutoBlade before adjustment. Empty, unknown or different tools block the job. On Cameo 3 and Portrait 2, confirm that AutoBlade is installed before starting.

Blade adjustment is followed by a readiness check before cutting paths. Stop can interrupt this wait. After a lost connection the adjustment is never replayed automatically.

Silhouette / Craft Robo supports pens, manual blades and AutoBlade on selected models. Cameo and Portrait offer optical Print & Cut.

Choose the exact model in Connection. All listed models support USB; Cameo 3–5 and Portrait 2–3 also offer Bluetooth LE. Load and unload material using the plotter controls.

The app polls ready/busy/unloaded status between small batches. After the last ready reply, check the result and choose Done. An interrupted job is never resumed or resent automatically. Stop requests a reset; always verify physical standstill.

Example in Help: Silhouette / Craft Robo first job

## 16 VEVOR Smart workflows

### VEVOR Smart first job

Smart4 can use Bluetooth SPP or USB with an OTG connection. USB is a separate raw PLT connection: grant Android access, confirm the loaded mat and start explicitly. Written bytes do not confirm completed movement. Wait for the plotter to stop before confirming completion. USB support is limited to the identified Smart4 interface; Smart1–3 use Bluetooth.

In Cut, open Advanced settings for Use app force and speed and Unload mat.

In Plotter connection, choose vendor, model and connection, then select a device and Connect. Device lists refresh automatically while disconnected and the app is visible; Refresh devices starts another search. Grant Bluetooth access when requested. For USB, choose Connect and allow Android access; the connection continues automatically. Protocol settings and FilmCut connection options are grouped below. Disconnect before changing the plotter. Connected confirms the link, not completed movement. Auto-connect is available for FilmCut and VEVOR Smart Bluetooth and never resumes a job.

Machine control uses the same arrow pad for all plotters. Choose a jog distance; the saved distance is used within the selected plotter’s supported range. Confirm the first manual action, then jog or lift/lower the tool without repeating that confirmation. FilmCut homing and work-origin changes always require separate confirmation. FilmCut pressure uses PWM, VEVOR Smart uses grams, Silhouette uses its native force scale, and HPGL/DMPL plotters use their panel settings. Manual pressure for VEVOR Smart 1–4 starts at 250 g and is adjustable within 250–500 g. On VEVOR Smart, Tool up requests a 0.025 mm carriage step left and an equal step right. Keep clearance on both sides of the carriage. Later jogs retain the tool state. FilmCut and Silhouette wait for controller readiness; VEVOR Smart and HPGL/DMPL require standstill confirmation when leaving a manual session. After Stop or an error, check the plotter before continuing. Stop sending cannot stop buffered HPGL/DMPL motion. Load material using the plotter panel.

After the final tool stage, VEVOR receives PU0,0;PG; to return and eject the mat. Keep the mat clear and confirm Done only when movement has stopped.

VEVOR Bluetooth sends up to 30 commands per packet. CRC errors or missing replies allow three retries, after pauses of 0.5, 1 and 2 seconds. USB uses bounded raw writes and never repeats a block after an uncertain write. Transfer progress does not confirm finished motion; inspect the result after an interrupted transfer.

The outline has details smaller than the plotter resolution. Simplify or enlarge the artwork and review again.

After restarting with an unconfirmed operation, you can continue designing. Choose Check previous plotter operation, then Done in Cut after observing that the plotter is stationary. Cutting and changing plotters stay blocked until confirmation; no job is resumed.

To switch an idle connected VEVOR, choose Change plotter beside the vendor and model selectors. This disconnects and pauses auto-connect so you can select another plotter.

Use app force and speed in Cut is on by default. It sends object/tool force and speed. Turn it off to use the plotter settings; neither FS nor VS is sent. Speed is mm/min divided by 60, rounded to whole mm/s: 2500 becomes VS42. Allowed input is 600–18000 mm/min.

Connect once to remember the Bluetooth identity and model. Auto-connect works in the foreground and never restarts a job. Disconnect pauses automatic attempts.

Choose the original 12 × 12 or 12 × 24 inch VEVOR mat in Prepare. The profiles use 304.8 × 304.8 mm and 304.8 × 609.7 mm. Smaller custom work areas use the smallest original profile that contains them.

Cut shows the design before review and the prepared tool path after review. Start cutting stays unavailable until the job is reviewed.

Pressure and passes use object or tool settings. VEVOR rates the right holder at 10–500 gf and the left at 50–500 gf. FS values still require a material test.

Press Start cutting and confirm the tool, mat and origin. A material-test check appears only when the selected process requires it.

Smart 1 and 2 use physical feed and start keys. If prompted, press the key on the machine, then confirm in the app. Unknown material status never means unloaded.

If material status is unknown, check the machine and choose Check mat to query it again. The app does not repeat setup or send an automatic stop. A lost connection, timeout or rejected setup blocks the job and requires observation.

Load the mat using the plotter controls. To unload, connect while the plotter is stationary and choose Unload mat in Cut. Keep the mat clear, watch it move, then choose Done when it is out and the plotter is stationary.

Stop can interrupt cutting or mat ejection while movement may continue. Choose Done after checking the plotter is stationary. Healthy connections stay open; interrupted sessions reconnect only after observation.

The percentage shows acknowledged Bluetooth data or written USB data, not executed cutting. A full transfer does not prove the plotter has finished. Confirm completion after observing the machine.

Install knives in the right holder (R). Pens, scoring and engraving tools use the left holder (L). The app selects the holder automatically for each tool stage; confirm the fitted tool before starting that stage.

In a short window, scroll the form to reach its actions. Keyboard entry keeps the same draft.

Example in Help: VEVOR Smart first job

## 17 Help and plotter support

### Plotter support

Open More, then Report a plotter problem or Request a new plotter. Select the affected plotter before creating a problem report. Reports use the current app session; collect one soon after a failure.

Describe the problem, expected result and steps to reproduce it. The report can include the selected plotter and recent connection metadata. It does not run a device test.

Diagnostics cover this app session: model, protocol, transfer settings, progress, acknowledgements and error categories. They exclude device addresses, raw commands, replies and artwork.

Attaching the full project is off by default. The complete project may contain names, text, photos and imported artwork. Attach it only if you want support to receive it.

Enter the manufacturer and exact model from the label. Add available connections, firmware and a manual link if known. A request does not enable the plotter automatically.

Review the report, then save it or share it with support by email. Nothing is uploaded automatically. Choose your email app and check the recipient and attachment before sending.

For a repeatable test, open a bundled example on a clear mat and follow its lesson. Reporting itself never sends commands or restarts a job. A saved report has not been sent; sharing opens another app where you complete sending.

Example in Help: HPGL / DMPL plotters
