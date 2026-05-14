Title: Camera Permission & QR Scanning — Optic Qr Effective date: May 13, 2026
Overview
Optic Qr uses your device camera exclusively to scan QR codes. This section explains what we use the camera for, what data (if any) we collect, how it is processed, and how you can control the permission.
Why we request Camera permission
Purpose: The camera is required to allow the app to read and decode QR codes (URLs, text, contact details, Wi-Fi network info, etc.). Without camera access, the real-time scanning feature cannot function.
Scope: Camera access is only requested while you are using the scanning feature. The app does not attempt to access the camera when the scanner is not active.
How camera data is handled
Local processing: Frames captured by the camera are processed locally on your device to detect and decode QR codes. We do not transmit raw camera frames to any server for scanning or processing.
No persistent upload: By default, camera images or video frames are not uploaded, stored remotely, or shared with third parties.
User-initiated saves: If you choose to save or export an image (for example, saving a generated or scanned QR image to your gallery), the saved image will be stored on your device. Any sharing of those saved images is done by you explicitly (share sheet, export, etc.).
Logs & metadata: We do not collect or associate camera images with a user account (there is no account system). Minimal non-identifiable usage telemetry (if enabled) may be collected for crash reporting or analytics; such telemetry does not include raw camera images or decoded content.
Permissions & control
Granting permission: The app requests the camera permission at the time you open the scanning feature. You can grant or deny it.
Revoking permission: You can revoke camera permission at any time through your device settings (Settings → Apps → Optic Qr → Permissions → Camera). If revoked, the scanner will not work until permission is restored.
Denial fallback: If camera permission is denied, you can still use other app features that do not require the camera (for example, create QR codes from text).
Third-party services and SDKs
We do not send camera frames to third-party services. If we add analytics, crash-reporting or cloud backup services in the future, we will disclose those services explicitly and ensure they do not receive camera frames.
Any third-party SDKs used will be evaluated to ensure they do not access camera frames or decode images off-device without explicit disclosure and consent.
Data retention and deletion
Camera frames are ephemeral: frames used for scanning are processed in memory and discarded once decoded. We do not retain raw camera images.
Saved images: Images you save explicitly to your gallery remain on your device until you delete them.
Support requests: If you submit a bug report that includes images or screenshots, those may be transmitted as part of the report and will be handled according to our support/privacy practices.
Security
We follow standard security practices to protect any data stored on the device.
The upload keystore, Play signing, and other sensitive app keys are kept separate from user data and are used only for app signing.
Legal & compliance
We request only the permissions necessary for the stated functionality. Camera access is the minimum required to provide scanning.
If you are subject to local privacy laws that require additional disclosures (e.g., EU GDPR), you may wish to include a link to this policy from your app and provide contact details for privacy requests.
Contact & requests
For questions, privacy requests, or to request deletion of any support-provided data, contact:
almamur.official@gmail.com
Play Store data safety declaration suggestion
Data: Device or other IDs — No
Data: Camera images — No (processed on device only)
Data: Photos or media — Only if user explicitly saves or shares
Data: Other user-provided content — Only if user chooses to save or share scanned/generated content
Sharing: None (unless user chooses to share saved content)
Purpose: App functionality (QR scanning), optional crash analytics (non-identifying)
Short FAQ (for users)
Q: Will my camera images be uploaded?
A: No. Camera frames are processed locally to detect QR codes and are not uploaded by default.
Q: What happens if I deny camera permission?
A: The scanner feature will not work; you can still create QR codes manually.
Q: How can I remove camera access?
A: Go to your device Settings → Apps → Optic Qr → Permissions → Camera and revoke access.
