MY EXPENSES — IPHONE APP

WHAT'S INCLUDED
- Add, edit and delete daily expenses
- Categories, payment methods, date and notes
- Monthly total, today's total and transaction count
- History filters and monthly category report
- Export full JSON backup and CSV spreadsheet
- Restore a JSON backup
- Local browser storage; no account or server database

IMPORTANT IPHONE SETUP
This is a Progressive Web App (PWA). To install it as an app icon and enable offline caching:
1. Upload the contents of this folder to a static HTTPS host (for example, your own website or a static hosting service).
2. Open the HTTPS address in Safari on your iPhone.
3. Tap Share, then Add to Home Screen, then Add.
4. Launch it from the new Home Screen icon.

PRIVACY AND BACKUP
Expenses are stored in localStorage in the browser on the iPhone. They are not uploaded by this app. Export a JSON backup regularly and save it in Files/iCloud Drive. If you clear Safari website data, change browser profiles, or remove website data, locally saved expenses may be erased. Restoring a JSON backup replaces the current expense list.

To test on a computer, open index.html. For reliable PWA installation and offline support, serve it over HTTPS.

VERSION 1.1 ADDITIONS
- Monthly Cash total and monthly UPI total are shown separately on the dashboard.
- Optional password lock with a locally stored PBKDF2 password hash.
- Optional iPhone platform-authenticator biometric unlock. On supported iPhones this may invoke Face ID; iOS/Safari may instead use the device passcode.
- Biometric setup requires HTTPS and compatible Safari/WebAuthn support. It is a local-device convenience lock, not a substitute for iOS device security.

VERSION 1.2 ADDITIONS
- Tap a category on the dashboard or monthly report to open its detailed expense history.
- Category detail view shows the filtered total and number of entries.
- Each expense shows its date, payment method, amount and optional note/description.
- Use the note field while adding an expense to write exactly what you spent money on.

VERSION 1.3 ADDITIONS
- Daily expense diary with a date picker.
- Selected date shows total spending, transaction count, Cash total and UPI total.
- Full itemized list for that date includes category, note, amount, date and payment method.
- Daily screen is available from the bottom navigation and updates when expenses are added, edited or deleted.


VERSION 1.4 ADDITIONS
- Added “Save backup to Files” for iPhone.
- On supported iOS Safari versions, this opens the iOS share sheet with the JSON backup attached. Choose “Save to Files”, then choose “On My iPhone” or iCloud Drive.
- If file sharing is not supported, the app downloads the JSON backup; use the iOS Share menu and choose “Save to Files”.
- iOS requires the user to confirm the save location. The app cannot silently write into the Files app.
