# BTC Up/Down — Hybrid (PWA)

قالب جاهز للنشر على **GitHub Pages** والتثبيت كتطبيق على **جوجل كروم للأندرويد**.

## خطوات النشر
1) أنشئ مستودع جديد في GitHub (مثال: `btc-updown-hybrid`).  
2) ارفع الملفات التالية في جذر المستودع: `index.html`, `manifest.json`, `sw.js`, مجلد `icons/`.  
3) من Settings → Pages:
   - Source: **Deploy from a branch**
   - Branch: `main` و المسار `/ (root)`
4) افتح رابط Pages الناتج، وسترى زر **Install App** داخل الصفحة للتثبيت.

## تعديلك
- ضع كود التطبيق الخاص بك مكان القسم المعلّم داخل `index.html`.  
- الأيقونات في `icons/` يمكن استبدالها بما تريد (192px و512px).
