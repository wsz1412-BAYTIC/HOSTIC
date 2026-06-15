# 🏢 Hostic

تطبيق ذكي لزيادة أرباحك من Airbnb في السعودية.

## ✨ الميزات

- 💰 **تسعير ديناميكي ذكي** - أسعار تتغير حسب الطلب
- 📊 **تحليلات عميقة** - فهم سوقك بدقة
- 💬 **تحليل التقييمات** - تحسين سمعتك تلقائياً
- 🔔 **تنبيهات WhatsApp** - إشعارات فورية وذكية
- 🎯 **مراقبة المنافسين** - تابع تحركات السوق
- 🤖 **توصيات AI** - قرارات محسوبة بدقة عالية

## 🚀 البداية السريعة

### متطلبات
- Node.js v16+
- PostgreSQL
- npm

### التثبيت
```bash
# استنسخ المستودع
git clone https://github.com/YOUR_USERNAME/hostic.git
cd hostic

# ادخل مجلد backend
cd backend

# ثبت المكتبات
npm install

# أضف ملف .env (انسخ من .env.example)
cp .env.example .env

# شغل الخادم
npm start
hostic/
├── backend/          # الخادم الرئيسي
│   ├── server.js
│   ├── package.json
│   └── routes/
├── frontend/         # الواجهة الأمامية
│   ├── index.html
│   ├── styles.css
│   └── script.js
└── database/         # قاعدة البيانات
    └── schema.sql
    
