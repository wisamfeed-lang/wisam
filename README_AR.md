# تطبيق احسبها بصوتك (EhsebhaBisawtak)

تطبيق آلة حاسبة صوتية ذكية لنظام أندرويد باللغة العربية.

## خطوات تحويل المشروع إلى ملف تثبيت APK:

### الخيار 1: البناء المجاني عبر الإنترنت (سحابياً عبر GitHub)
1. أنشئ مستودعاً جديداً على [GitHub](https://github.com/new).
2. ارفع مجلد المشروع كاملاً.
3. ادخل على تبويب **Actions**، ستجد البناء التلقائي بدأ.
4. بمجرد الانتهاء (حوالي دقيقتين)، حمّل ملف `EhsebhaBisawtak-debug-apk` وثبته على هاتفك فوراً!

### الخيار 2: عبر Android Studio على جهازك
1. افتح برنامج **Android Studio**.
2. اختر **Open** واختر مجلد `EhsebhaBisawtak`.
3. انتظر انتهاء المزامنة.
4. من القائمة: `Build -> Build Bundle(s) / APK(s) -> Build APK(s)`.
5. سيظهر لك إشعار به زر `locate` للوصول لملف الـ APK الناتج.

### الخيار 3: عبر سطر الأوامر (Terminal)
```bash
./gradlew assembleDebug
```
ملف الـ APK الناتج يكون داخل:
`app/build/outputs/apk/debug/app-debug.apk`
