# Android signing setup

This app must always be built with the same signing key.

## Package name

`com.explapp.debt_ledger_ar`

## Required GitHub Secrets

Add these under:

`Settings > Secrets and variables > Actions > New repository secret`

- `ANDROID_KEYSTORE_BASE64`
- `ANDROID_KEYSTORE_PASSWORD`
- `ANDROID_KEY_ALIAS`
- `ANDROID_KEY_PASSWORD`

Do not commit the `.jks` file or passwords to the repository.

## Rule

Every store update must use the same package name and the same signing secrets. If either changes, app stores will reject the update.
