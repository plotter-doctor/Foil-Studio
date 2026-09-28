# Foil Studio — review guide

The Android app does not require an app account or login credentials. A Google Play purchase may be required to install the paid release.

## Without a plotter

1. Open the app and select **Design**.
2. Use **Add** to create a rectangle, text, or clipart. Objects can be selected and edited on the mat.
3. Open **Edit → Layers** to inspect layer colours and tool assignments.
4. Open **Prepare** to view or edit mat, material, and current cutting settings.
5. Select **Review job** to inspect the job in **Cut**. With no controller connected, the app displays its disconnected state and prevents starting a physical job.
6. Use **Project** to save a sample project through Android's document picker.

## Hardware-dependent functionality

Physical cutting requires a compatible GRBL-based plotter. Supported connection types are Bluetooth Classic SPP, USB CDC serial, and TCP. BLE-only devices and proprietary vendor protocols are not supported by these connection types. The default TCP endpoint is `plotter.local:8888`, which must resolve to the reviewer's actual compatible controller; this is not an Internet demo server.

Firmware must support `$LOAD_MATERIAL=<distance>` and `$UNLOAD_MATERIAL` for the dedicated mat controls. The default load distance is 20 mm. Controller connection may automatically resume an initial fully held state, so ensure the machine is safe and no unwanted interrupted job is queued before connecting.

Do not start a physical job without suitable material, tool setup, alignment, and supervision. The app prompts for the first tool and subsequent tool changes. Its X return uses working X=0, not a full-machine homing cycle.

Support: [pratanczuk@gmail.com](mailto:pratanczuk@gmail.com).
