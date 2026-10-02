# AI Workstation Android V1.1

تطبيق Android حقيقي لمحطة AI Workstation.

## الميزات
- WebView آمن للـWorkstation.
- حفظ رابط الخادم على الجهاز.
- جلسات Cookies وتسجيل الدخول.
- رفع الملفات من الهاتف إلى واجهة الويب.
- تنزيل ملفات النتائج إلى Downloads.
- زر الرجوع داخل التطبيق.
- HTTPS فقط.
- لا توجد مفاتيح Gemini/OpenRouter داخل التطبيق.

## البناء
افتح مجلد `android-app-build` في Android Studio ثم:
Build > Build APK(s)

الناتج:
`app/build/outputs/apk/debug/app-debug.apk`

ملاحظة: هذه البيئة لا تحتوي Android SDK/Gradle distribution، لذلك لا يمكن إخراج APK ثنائي هنا، لكن المشروع مكتمل من ناحية كود التطبيق ويحتاج Android Studio/SDK للبناء.
