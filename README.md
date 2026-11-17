# Microfinance Manager (Android)

Starter Android app for recording microfinance customer and finance details.

## Included
- Customer and co-applicant details
- Manual CIBIL/credit-check status and score field
- Finance name, loan amount, interest percentage
- Demand amount/date, EMI and outstanding
- Local record list; data is stored on this Android device

## Build APK using GitHub
1. Create a new repository on GitHub.
2. Upload all files and folders from this project (keep `.github/workflows/build-apk.yml`).
3. Open the repository's **Actions** tab.
4. Select **Build Android APK** and click **Run workflow** (or push to `main`).
5. Open the completed workflow run, find **Artifacts**, and download `MicrofinanceManager-debug-apk`.
6. Extract the ZIP; it contains `app-debug.apk`. Install it on your Android phone.

## Important limitations
- This is a starter app, not a production lending/loan-servicing system.
- CIBIL is not queried automatically. Real bureau checks require authorized bureau access, customer consent, and an approved API/provider.
- Records are stored locally on one phone; there is no cloud sync, staff login, backup, or encryption in this starter version.
- Do not enter real customer financial or identity data until proper security, consent, access control, encryption, and backup are implemented.
- Debug APK is for testing. A production release should be signed with a protected release key.
