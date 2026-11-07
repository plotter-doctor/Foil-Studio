# Foil Studio reviewer guide

Reviewed 7 November 2026. The app uses no application account or login. Installation is free; Basic and Pro are managed by Google Play. Use the entitlement appropriate to the feature being reviewed. This guide covers current development; the new Cut job selector is unreleased, so consult the version guide for an earlier installed build.

## Review without hardware

1. Open Design and create a small shape or a bundled example from Help and examples.
2. Inspect Layers, object properties and tool settings. Select a language from English, Polish, German and Spanish.
3. Open Prepare, choose the mat/material and inspect the Advanced production controls.
4. Open Connection setup and Start demo mode. Confirm that the DEMO banner is visible.
5. Load and align the virtual mat using the demo controls. Choose Review job.
6. For a configured production-job project in the upcoming workflow, choose the Production job in Cut and press Material installed · Review job. In the demo this confirms virtual stock only.
7. Inspect Operations and settings, confirm virtual alignment, start the demo job and follow the tool prompt. Exercise pause/resume and stop using the virtual controller.
8. For import review, compare printable image insertion, Trace instead and supported Editable cut paths. Separate colors is removed in current development.
9. Save/export/print using Basic or Pro. Restore purchases through the same Google Play test account. Box/Craft wizard creation and regeneration require Pro.
10. Exit demo mode before an explicit real connection. Demo position and alignment do not authorize physical production.

Demo and development simulator tests demonstrate workflow/protocol behavior. They do not validate blade depth, physical force, material quality, mechanical accuracy or a particular real plotter.

## Review with hardware

Select the exact model in Connection. Supported transports and operations depend on that profile. Bluetooth Classic serial, BLE, USB serial/printer interfaces and TCP are not interchangeable. Dedicated loading, optical registration, AutoBlade and completion confirmation vary by model.

Use appropriate material/tool setup, check the working origin and keep the machine supervised. Inspect interrupted work before recovery or restarting. Start and tool-change prompts authorize motion, so confirm them only after the physical setup is ready.

## Useful checks

Review a small multi-job design with separate stock and mixed tools. Verify that changing jobs requires fresh review/confirmation and that excluded artwork is absent from production. Test long names, landscape and enlarged Android text. Use independent sample projects for any screenshots or issue reports.

[User manual](user-manual.md) · [Version guide](release-notes.md) · [Support](mailto:pratanczuk@gmail.com)
