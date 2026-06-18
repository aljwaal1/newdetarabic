# OPPO ads update notes

## Version

1.0.7+8

## Store declaration

- Contains ads: Yes
- Ad format: Banner ad
- Ad network: Google AdMob
- Internet use: Required for loading ads only. The debt ledger features remain local/offline.

## GitHub Secrets for production ads

Add these repository secrets before building the production APK:

- `ADMOB_APP_ID`
- `ADMOB_BANNER_UNIT_ID`

If the secrets are not configured, the APK uses Google's official test ad IDs.

## English version description

Added a lightweight banner ad using Google AdMob. The main debt ledger features remain unchanged.

## Arabic version description

تمت إضافة إعلان بنر خفيف باستخدام Google AdMob مع بقاء وظائف دفتر الديون كما هي.

## Privacy note

Because the app now includes ads, the store listing and privacy policy should mention that Google AdMob may collect or process advertising-related data according to Google's advertising and privacy policies.
