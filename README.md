# Foil Studio

Create artwork, prepare material jobs and send them to a compatible plotter in the Android Design → Prepare → Cut workflow.

- [English workflow guide](docs/user-manual.md)
- [Full manuals in English, Polish, German and Spanish: PDF, Word and text](docs/manual/README.md)
- [Four-language quick start](docs/quick-start.md)
- [Release notes and version guide](docs/release-notes.md)
- [Reviewer guide and hardware-free demo](docs/reviewer-guide.md)
- [Screenshot versions](screenshots/README.md)
- [Store graphics and phone/tablet screenshots](store-assets/README.md)
- [Privacy policy](PRIVACY.md)
- [Report an issue](https://github.com/plotter-doctor/Foil-Studio/issues)
- [Support](mailto:pratanczuk@gmail.com)

## Versions

Reviewed 9 November 2026. The current guides describe **0.1.129 (150)**. Prepared for Google Play submission; approval and availability are not yet claimed. Current production is 0.1.127 (148), available since 7 November 2026. Check the installed version and [versioned release notes](docs/releases/0.1.129.md).

## Artwork, materials and jobs

Assign stock in **Layers → Edit layer → Material**. Objects inherit their layer's material; moving an object to another layer uses the destination stock. Materials remain reusable stock presets, while Object properties holds tool and process settings. New projects seed Default with the current material. Review warns when included cutting artwork has no material.

Use Production preview in Prepare for layout and Prepare jobs. In Cut, choose Job to preview only its artwork and assembly marks, then press Start cutting and complete the installed-stock, tool and mat checks. Review jobs stays in Prepare. The compact controls leave more space for the preview. Wide screens offer a layer/object tree with properties, adding layers and moving objects.

The active project is saved on this device for background return and app restart. After restarting, review and confirm the physical stock and mat again. Export important work as a separate backup. [The guide](docs/user-manual.md#projects-languages-and-purchases) explains migration from versions that did not record the active project.

Supported SVG/DXF and eligible PDF/EPS/AI/CDR inputs preserve supported original paths, solid colours and source layers. Images can be printed or traced from contrast; PSD offers supported aligned pixel layers. Review the import preview and reported limitations. Knife calibration uses the selected stock, asks when a choice is needed, and leaves the source unchanged on cancellation.

## Prepare paths and calibrate the knife

Open Design → Edit → Prepare for plotter, or the wand beside Production preview in Prepare. Compare Before/After, set the geometric tolerance and apply reversible cut preparation while retaining the original artwork. Circular arc recovery and path simplification protect uncertain contours and nearby details.

Knife calibration uses 30 × 30 mm squares: five offset columns and three pressure rows where the application controls pressure. Choose a sample after inspecting the cut, then check the saved-result receipt. Existing objects retain their tool snapshot; reselect the updated library tool to use its saved settings. About shows the current Free, Basic or Pro plan.

## Compatibility and access

Choose the exact plotter profile and supported transport. FilmCut/GRBL, supported Silhouette/VEVOR Smart and named raw-protocol profiles have different capabilities. USB, Bluetooth Classic, BLE and TCP support is model dependent. Simulator results do not establish physical cut quality or qualify every model/firmware. Use a trusted network for TCP and supervise real machines.

The app is free to install. Free supports design/editing, previews and active-design recovery; Basic unlocks named saves, export, printing and production. Optional Pro adds Box/Craft wizard creation and regeneration and includes Basic while active. Restore purchases with the same Google Play account. See the [guide](docs/user-manual.md#projects-languages-and-purchases).

## This repository

This repository contains public documentation and publication materials. The proprietary application source, signing credentials and customer projects are not published here. Existing screenshots retain their version context. Application and third-party component rights remain separate.
