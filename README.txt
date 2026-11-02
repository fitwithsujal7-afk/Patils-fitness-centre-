PATILS FITNESS CENTRE – FINAL OFFLINE EDITION
=============================================

This version stores all member and payment records locally on ONE Android phone using IndexedDB. It does not connect to Firebase, cloud databases, analytics or a server.

FEATURES
- Register/edit/delete members with name, mobile, membership start/end, total fee and notes.
- Active, expired and expires-within-3-days lists.
- Cash and UPI payment records, partial payments, balance due and payment history.
- Individual payment receipt. On Android Chrome print dialog choose "Save as PDF".
- WhatsApp membership reminder and payment receipt text are MANUAL: WhatsApp opens with a prefilled message; user reviews and presses Send.
- Export JSON backup and restore JSON backup.
- Local offline app shell after it has been installed/opened once while online.

INSTALL / UPDATE EXISTING GITHUB PAGES APP
1. Download and extract this ZIP on your Android phone.
2. Open the existing GitHub repository you already created.
3. Replace the repository's index.html, manifest.webmanifest and sw.js with these versions.
4. Open the icons folder in the repository and replace icon-192.png and icon-512.png.
5. Commit changes to main. Wait for GitHub Pages to publish.
6. Open the same published Pages URL in Chrome while online. Refresh it; then use Chrome menu -> Install app / Add to Home screen.
7. Open the installed app once. It caches the app shell for offline use. Test airplane mode by closing and reopening the app.

IMPORTANT DATA SAFETY
- Member records are stored on this phone in the app's browser IndexedDB. They are not uploaded to GitHub or sent to any cloud.
- Do not clear Chrome site data, app storage, uninstall/reset the app, or clear browser data unless you have a backup.
- Use Backup & restore -> Download backup regularly and copy the JSON backup to a safe location (for example, phone Downloads and another secure drive).
- To move to a new phone: install/open the app there, use Restore backup and select your JSON backup.
- A website/PWA cannot guarantee data will survive every OS cleanup, browser reset, uninstall, or device failure. Backups are essential.
- The first installation/update needs internet to load the hosted app. After it has cached, member and payment management works offline. WhatsApp sending and initial website loading require internet.
- This is a PWA website installed to the Android home screen, not a Play Store APK.
- If old app data was in the previous localStorage version, this new IndexedDB version does not automatically migrate it. Export any old app backup first if the old version provides one; otherwise manually add members again.
