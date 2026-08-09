# قواعد اللغة 📖

دفتر القواعد الشامل للنحو العربي: خرائط ذهنية هرمية لكل درس، فيديوهات شرح، وعشرون نشاطًا تفاعليًا لكل درس (صواب/خطأ، اختيار من متعدد، وتحليل/إعراب)، بالإضافة إلى تتبع النتائج.

![قواعد اللغة](social-preview.png)

## محتوى المشروع
- `index.html` — التطبيق كاملاً (صفحة واحدة).
- `manifest.json` — إعدادات تثبيت التطبيق (PWA).
- `favicon-32.png`, `icon-180.png`, `icon-512.png` — أيقونات التطبيق.
- `social-preview.png` — صورة الغلاف (يمكن استخدامها كصورة معاينة للمستودع على GitHub).

## رفع المشروع إلى GitHub
لا تتوفر لديّ حاليًا صلاحية الاتصال المباشر بحساب GitHub الخاص بك، لكن يمكنك رفع المشروع بسهولة باتباع إحدى الطريقتين:

### الطريقة 1: عبر واجهة GitHub (بدون سطر أوامر)
1. اذهب إلى https://github.com/new وأنشئ مستودعًا جديدًا (مثلاً باسم `qawaid-allugha`).
2. اضغط "uploading an existing file".
3. اسحب جميع الملفات الموجودة في هذا المجلد وأفلتها.
4. اضغط "Commit changes".

### الطريقة 2: عبر سطر الأوامر (Git)
```bash
cd مسار-مجلد-المشروع
git init
git add .
git commit -m "إضافة تطبيق قواعد اللغة"
git branch -M main
git remote add origin https://github.com/USERNAME/qawaid-allugha.git
git push -u origin main
```

### تفعيل استضافة الصفحة (GitHub Pages) — اختياري
لعرض التطبيق كموقع مباشر:
1. من صفحة المستودع: **Settings → Pages**.
2. تحت **Source** اختر الفرع `main` والمجلد `/ (root)`.
3. احفظ، وسيصبح الرابط عادة على الشكل:
   `https://USERNAME.github.io/qawaid-allugha/`

### تعيين صورة المعاينة الاجتماعية (Social Preview)
1. من صفحة المستودع: **Settings**.
2. مرّر إلى قسم **Social preview** واضغط **Edit**.
3. ارفع ملف `social-preview.png`.
