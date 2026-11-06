مجلس - مشروع تجهيز APK

المحتويات:
- www/index.html: نسخة تطبيق مجلس الحالية.
- package.json و capacitor.config.json: إعدادات Capacitor.
- .github/workflows/build-apk.yml: بناء APK تلقائياً على GitHub Actions.

تنبيه:
حقلا SUPABASE_URL و SUPABASE_ANON_KEY داخل index.html فارغان حالياً؛ لذلك يعمل التطبيق بالوضع المحلي التجريبي، ولا تتزامن الحسابات والرسائل بين الأجهزة قبل إعداد Supabase وسياساته.

لبناء APK من الهاتف:
1) ارفع محتويات هذا المجلد إلى مستودع GitHub جديد باسم Majlis.
2) افتح تبويب Actions في المستودع.
3) اختر Build Majlis APK ثم Run workflow.
4) بعد نجاح البناء افتح نتيجة التشغيل (Run) ونزّل Artifact باسم Majlis-debug-apk.
5) فك ضغط Artifact وثبّت app-debug.apk على هاتف Android.
