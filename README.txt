PATILS FITNESS CENTRE — ANDROID WEB APP STARTER

FILES
- index.html: app interface and member management
- manifest.webmanifest: installable web app metadata
- sw.js: basic offline caching

HOW TO USE ON ANDROID
1. Upload the contents of this folder to an HTTPS static host (for example, your own hosting).
2. Open the hosted index.html URL in Chrome on your Android phone.
3. Use Chrome menu > Install app (or Add to Home screen).
4. On first launch, create your admin password.

FEATURES
- Admin password set on first use
- IndexedDB member database on this device/browser
- Add, edit, delete, search members
- Active / expired / expiring within 3 days
- WhatsApp manual reminder links (review and press Send in WhatsApp)
- JSON export and restore backup

IMPORTANT LIMITATIONS
- This is an installable PWA starter, not a signed APK.
- Member records are stored locally in the browser on this device. They persist across normal app closes/restarts, but can be lost if browser/site data is cleared, the app is uninstalled with its data, or the device is lost.
- Export backups regularly and store them somewhere safe.
- Admin password is a local app gate, not enterprise-grade security; anyone with access to the device/browser profile may be able to inspect local app data.
- For true cloud persistence, multi-device sync, secure server-side authentication and automated scheduled reminders, deploy a backend and WhatsApp Business Platform integration.
