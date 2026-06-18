# دفتر الديون - fix11 ad preview no sdk

تطبيق Flutter عربي يعمل أوفلاين لتسجيل الديون بين الأشخاص.

## ما الجديد في fix11

- حذف Google Mobile Ads SDK مؤقتًا لعزل سبب الإغلاق.
- إضافة مساحة إعلان تجريبية داخل الواجهة لمعاينة مكان وشكل البنر.
- الرجوع إلى minSdk 21.
- تحديث رقم النسخة إلى `1.0.11+12`.
- تحديث اسم Artifact في GitHub Actions إلى:
  `debt-pal-arabic-v1-fix11-ad-preview-no-sdk-apk`

## ملاحظة مهمة

هذه النسخة مخصصة للتجربة فقط لأنها تعرض مساحة إعلان شكلية وليست إعلانًا حقيقيًا. لا ترفعها كنسخة ربح نهائية على المتجر.

بعد التأكد من أن التطبيق يفتح وأن مكان الإعلان مناسب، يمكن بناء نسخة أخرى بإعلانات AdMob الحقيقية.

## البناء عبر GitHub Actions

ارفع الملفات إلى GitHub ثم شغّل workflow من:

`.github/workflows/build-apk.yml`

سيتم إنشاء APK داخل Artifact باسم:

`debt-pal-arabic-v1-fix11-ad-preview-no-sdk-apk`
