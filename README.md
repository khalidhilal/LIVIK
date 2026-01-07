# LIVIK - Menu (React + Vite + Tailwind)

مشروع صغير لعرض المنيو بتاع LIVIK.

التشغيل محلياً:
1. npm install
2. npm run dev
3. افتح http://localhost:5173

بناء للإنتاج:
- npm run build
- npm run preview

نشر سريع:
- أنسب استضافة: Vercel أو Netlify (سحبي الريبو وفعّل build command: `npm run build`, output: `dist`).
- GitHub Pages: يلزم إعداد إضافي (build ثم رفع محتويات `dist` لgh-pages branch أو استخدام action).

تحسينات ممكنة لاحقاً:
- إضافة سلة شراء (cart) وحفظ الكميات في localStorage.
- ربط طلبات بالباك-إند + إدارة ستوك.
- دعم فلترة متقدمة (سعر، نوع لحم، توصيات).
