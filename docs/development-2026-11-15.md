# Changes prepared for 0.1.145

Submitted to Google Play for production review on 15 November 2026, with full rollout requested after approval. Play Console shows changes in review. Approval and public availability of 0.1.145 are not yet confirmed. The last confirmed available production version is 0.1.129 (150), available since 9 November 2026.

This release combines independently authored calibration, editing, VEVOR USB/serial and GCC work since 0.1.129. The shared manual-control distance row includes six standard choices through 100 mm and preserves custom values. Default step remains 5 mm. Language and Help are in Project.

USB printer discovery uses supported interface class/protocol and endpoints, with optional input and explicit alternate selection. Optional reported Device ID is stored locally and displayed as advisory information. Unsupported IEEE 1284.4 is rejected; vendor-specific raw USB is limited to explicitly supported GCC devices. Blocking transport reads are separated from write scheduling. Serial and direct USB remain distinct paths.

Non-Smart VEVOR uses framed DMPL, repeated absolute jog targets and logical origin return. A mechanism may lift at rest despite requested Tool down; actual behavior is firmware-dependent. GCC has 72 profile entries across five command variants. Tool mode, bounds query availability and connections remain model-specific; pressure/speed stay panel-controlled.

[Release notes](releases/0.1.145.md) · [Validation](validation-2026-11-15.md)
