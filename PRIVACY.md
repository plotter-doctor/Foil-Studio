# Foil Studio privacy policy — DRAFT

Prepared 28 September 2026. **Not yet the effective release policy.** Publisher identity, support retention terms, and the final distributed application must be confirmed before this policy is submitted to Google Play.

## Scope

This draft describes the Android Foil Studio application, package `com.foilstudio.independent.foil_mobile`. It does not describe GitHub, Google Play, a document-provider service, or the connected plotter's own independent practices.

## Artwork and local settings

Foil Studio processes artwork, project files, imported images, material/tool/mat presets, and connection settings to provide design and plotter-control features. Projects, recovery data, and settings may be stored in the application's private local workspace. The inspected application does not include an app account, advertising SDK, analytics SDK, or an application-operated cloud upload service.

Opening or saving a document uses the Android document picker. The app receives access to the document you select. If you choose a cloud-backed document provider, that provider may transfer and store the document according to its own policies and your settings. Camera import invokes an installed camera application and receives an image for your chosen design task.

## Plotter connections

The app accesses device names/identifiers and connection endpoints as needed to list, select, and communicate with supported Bluetooth or USB devices and TCP controllers. It sends toolpaths and machine-control commands to the controller you choose and receives status and error responses. These operations are not transfers to an application-operated analytics service.

Bluetooth access may require Android's Nearby devices permission. USB access requires permission for the selected device. Network permission enables TCP connections. Permission can be managed in Android settings, though disabling it may prevent the corresponding feature from working.

TCP connections are not authenticated or encrypted. Use only a trusted local network. Do not embed personal or sensitive information in designs sent over this connection, and do not expose the controller port to the Internet.

## Purchases and external services

Google Play handles app purchases and its platform services according to [Google's privacy policy](https://policies.google.com/privacy). The app does not request your payment-card details. Installed document providers, camera applications, controller firmware, and GitHub have their own practices outside this application's control.

## Retention and deletion

Local settings and recovery/project data remain until replaced or deleted, or until Android clears the application's data. Clearing storage or uninstalling removes private app data subject to Android behaviour. The app disables Android backup of its private data in its configuration. Exported documents, external-provider copies, and copies you made separately are not deleted by uninstalling: remove them through their respective file or service controls.

## Support and contact

For support or privacy questions, contact [pratanczuk@gmail.com](mailto:pratanczuk@gmail.com). Use this email rather than a public issue for privacy requests. Do not send passwords or payment-card details.

Public technical questions may also be submitted through [the repository's issue tracker](https://github.com/plotter-doctor/Foil-Studio/issues). GitHub issues are public; do not include personal or sensitive information. The publisher's handling and retention of support correspondence must be confirmed before this draft becomes effective.

## Changes

An effective release policy will carry an effective date. Material changes in app data handling must be reflected here and in the app's disclosures.

Publisher review must verify this draft against the final release bundle and Play services applied to it. The Google Play Data safety form remains a separate declaration; this draft is not a completed declaration or a legal compliance certification. See [Google Play's User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311?hl=en).
