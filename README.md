# دفتر الديون - fix13 real admob top

تطبيق Flutter عربي يعمل أوفلاين لتسجيل الديون بين الأشخاص.

## ما الجديد في fix13

- إضافة إعلان Banner حقيقي من Google AdMob في أعلى الصفحات.
- استخدام App ID و Banner Unit ID الحقيقيين.
- تحميل الإعلان بعد ظهور الواجهة حتى لا يتأخر فتح التطبيق.
- إخفاء مساحة الإعلان إذا فشل التحميل.
- رفع minSdk إلى 23 حسب متطلبات Google Mobile Ads.
- تحديث رقم النسخة إلى `1.0.13+14`.
- تحديث اسم Artifact في GitHub Actions إلى:
  `debt-pal-arabic-v1-fix13-real-admob-top-apk`

## ملاحظة مهمة

هذه نسخة إعلانات حقيقية. عند رفعها إلى OPPO يجب تفعيل خيار أن التطبيق يحتوي على إعلانات.

## البناء عبر GitHub Actions

ارفع الملفات إلى GitHub ثم شغّل workflow من:

`.github/workflows/build-apk.yml`

سيتم إنشاء APK داخل Artifact باسم:

`debt-pal-arabic-v1-fix13-real-admob-top-apk`
