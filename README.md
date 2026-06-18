# دفتر الديون - fix14 real admob compat

تطبيق Flutter عربي يعمل أوفلاين لتسجيل الديون بين الأشخاص.

## ما الجديد في fix14

- إضافة إعلان Banner حقيقي من Google AdMob في أعلى الصفحات.
- استخدام App ID و Banner Unit ID الحقيقيين.
- تحميل الإعلان بعد ظهور الواجهة حتى لا يتأخر فتح التطبيق.
- إخفاء مساحة الإعلان إذا فشل التحميل.
- استخدام Flutter 3.24.5 بدل آخر stable لتجنب تعارضات Gradle/SDK.
- استخدام إصدار AdMob أقدم وأكثر توافقًا.
- الرجوع إلى minSdk 21.
- تحديث رقم النسخة إلى `1.0.14+15`.
- تحديث اسم Artifact في GitHub Actions إلى:
  `debt-pal-arabic-v1-fix14-real-admob-compat-apk`

## ملاحظة مهمة

هذه نسخة إعلانات حقيقية. عند رفعها إلى OPPO يجب تفعيل خيار أن التطبيق يحتوي على إعلانات.

## البناء عبر GitHub Actions

ارفع الملفات إلى GitHub ثم شغّل workflow من:

`.github/workflows/build-apk.yml`

سيتم إنشاء APK داخل Artifact باسم:

`debt-pal-arabic-v1-fix14-real-admob-compat-apk`
