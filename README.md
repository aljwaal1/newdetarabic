# دفتر الديون - fix7 admob banner

تطبيق Flutter عربي يعمل أوفلاين لتسجيل الديون بين الأشخاص.

## ما الجديد في fix7

- إضافة إعلان Banner خفيف عبر AdMob في أسفل الصفحات الرئيسية.
- الإعلانات الافتراضية في الكود هي إعلانات اختبارية آمنة للتجربة.
- يمكن وضع أرقام AdMob الحقيقية من GitHub Secrets بدون تعديل الكود.
- تحديث رقم النسخة إلى `1.0.7+8`.
- تحديث اسم Artifact في GitHub Actions إلى:
  `debt-pal-arabic-v1-fix7-admob-banner-apk`

## إعداد AdMob الحقيقي

قبل بناء نسخة النشر التي تريد رفعها على OPPO، أضف هذه القيم في GitHub:

`Settings > Secrets and variables > Actions > New repository secret`

أضف:

- `ADMOB_APP_ID`
- `ADMOB_BANNER_UNIT_ID`

إذا لم تضف هذه القيم، سيتم بناء التطبيق بإعلانات Google الاختبارية فقط.

## البناء عبر GitHub Actions

ارفع الملفات إلى GitHub ثم شغّل workflow من:

`.github/workflows/build-apk.yml`

سيتم إنشاء APK داخل Artifact باسم:

`debt-pal-arabic-v1-fix7-admob-banner-apk`
