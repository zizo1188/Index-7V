ارفع الملفات الثلاثة معًا إلى GitHub Pages: index.html + sw.js + manifest.webmanifest.
مهم: استبدل الملفات القديمة، ثم افتح رابط الموقع وأضف ?v=7 في آخر الرابط مرة واحدة. النسخة دي تحفظ المحتوى في IndexedDB بدل الاعتماد على localStorage، وتزيل الـService Worker القديم وتثبت نسخة جديدة.
