# Arabic Debt Ledger

تطبيق دفتر ديون عربي يعمل أوفلاين، مع إعلان AdMob حقيقي في أعلى الصفحات.

## New app identity

- Package name: `com.explapp.debt_ledger_ar`
- Version: `1.0.0+1`
- Direct APK path inside build: `apk/debt-ledger-ar-v1.apk`
- AdMob App ID: `ca-app-pub-3082968903080396~1164014211`
- AdMob Banner ID: `ca-app-pub-3082968903080396/5279353190`

## Important

This project requires fixed Android signing secrets in GitHub Actions.

Read:

`SIGNING_SETUP.md`

Do not publish or commit the keystore file or signing passwords.

## Build

Upload the project files to GitHub, add the required signing secrets, then run:

`.github/workflows/build-apk.yml`
