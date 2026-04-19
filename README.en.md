# Expense Manager — Support

If you have any issue or suggestion about the **Expense Manager** app, please open an [issue](../../issues) in this repository.

🇪🇸 Versión en español: [README.md](README.md)

## FAQ

### Do I need to create an account?
No. The app works entirely locally on your device. You only need a name and a PIN.

### Is my data private?
Yes. All data is stored locally on your iPhone. Optional syncing uses your own iCloud Drive; there are no external servers or third parties involved.

### Does the app have in-app purchases or subscriptions?
No. Expense Manager has no in-app purchases and no subscriptions. Every feature is included.

### How is data synced between devices or with another person?
You choose a folder in your iCloud Drive and the app exports/imports a JSON file in that folder. If you share that folder with another person, both devices stay in sync. The app does not use any proprietary servers.

### Can I import or export my data?
Yes. From Settings you can export and import your expenses, payment methods and payrolls in CSV format.

### I forgot my PIN, what now?
The lock screen provides a recovery option. If you cannot recall any credential, the only way forward is reinstalling the app (local data will be lost; if sync was active you can recover it from iCloud Drive).

---

## Privacy Policy

**Last updated: April 19, 2026**

### Data we collect
Expense Manager **does not collect or send any personal data to external servers**. All information (expenses, payrolls, payment methods, settings) is stored exclusively on your device via SwiftData.

### Accounts and registration
The app does not require creating an account or signing up for any service. There is no remote authentication or user profile on servers.

### Optional iCloud Drive sync
If you enable sync, data is exported as a JSON file inside an iCloud Drive folder that you explicitly choose. That folder is managed by Apple under your iCloud account. We have no access to your iCloud account or to the synced data, and there is no intermediate proprietary server.

### Analytics, advertising and tracking
The app **does not use any analytics, telemetry, advertising or tracking services**. No device identifiers, usage events or other data are sent to third parties.

### In-app purchases
The app **has no in-app purchases and no subscriptions**. All features are available without any additional payment.

### Security and credentials
App access is protected by a local PIN (4-8 digits) and optionally Face ID / Touch ID. The PIN is stored as a cryptographic hash in the device's **Keychain**, never in plain text and never outside the device.

### Data export and import
CSV export and import is always user-initiated, and files are written to folders you choose. The app does not send those files anywhere automatically.

### Third-party data
We do not share data with third parties. The only external services that may be involved are Apple's own (iCloud Drive and Keychain), under your account and their own privacy policy.

### Changes to this policy
If the policy changes in the future, the date at the top of this section will be updated and the new version will be recorded in the history of this repository.

### Contact
If you have questions about this policy, open an [issue](../../issues) in this repository.
