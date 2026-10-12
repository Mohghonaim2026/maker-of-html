# HTML Maker — Android App (خطوات التثبيت)

## الطريقة: ابنِ ملف APK من موبايلك بدون كمبيوتر

1. فك ضغط ملف `html-maker-android-source.zip` — ستجد مجلدين: `android/` و `.github/`.
2. اعمل حساب مجاني على https://github.com ثم مستودعاً جديداً (New repository).
3. ارفع محتويات المجلدين إلى جذر المستودع (Upload files من المتصفح).
4. افتح تبويب **Actions** ← اختر **Build APK** ← اضغط **Run workflow**.
5. انتظر 5–8 دقائق حتى تنتهي المهمة بنجاح.
6. من صفحة المهمة حمّل **Artifacts ← html-maker-apk** (ملف `app-debug.apk`).
7. انقل الملف إلى موبايلك وافتحه ← وافق على "التثبيت من مصادر غير معروفة" ← ثبّت.
8. ستجد أيقونة **HTML Maker** — يعمل أوفلاين.

## البديل (كمبيوتر + Android Studio)

افتح مجلد `android/` في Android Studio (Hedgehog أو أحدث) ← وصّل الموبايل ← Run.

## ملاحظات

- التطبيق: Kotlin + Jetpack Compose، معاينة WebView معزولة، حفظ عبر Storage Access Framework،
  المشاريع في DataStore، المفاتيح في EncryptedSharedPreferences (لا تخرج أبداً في ملفات التصدير).
- Gemini: ضع مفتاحك المجاني من https://aistudio.google.com داخل التطبيق ← اختبار الاتصال.
- ChatGPT / Claude: يعملان عبر المساعد الخارجي (فتح التطبيق الرسمي ← نسخ ← لصق) مجاناً.
