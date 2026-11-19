# المذكرة اليومية — مشروع أندرويد

## بناء الـ APK
**أ) Android Studio:** File ▸ Open ▸ اختر هذا المجلد ▸ Build ▸ Build APK(s).
الملف في: app/build/outputs/apk/debug/app-debug.apk

**ب) GitHub (بدون تثبيت شيء):** ارفع المجلد كاملًا إلى مستودع جديد ▸ تبويب Actions ▸ Build APK ▸ حمّل app-debug.apk من Artifacts.

**ج) سطر الأوامر:** gradle assembleDebug  (يتطلب JDK 17 وAndroid SDK 34)

ثم انقل الملف إلى الهاتف وثبّته (فعّل "التثبيت من مصادر غير معروفة").
