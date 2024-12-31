# استخدم صورة أساسية
FROM node:16

# إنشاء مجلد داخل الصورة
WORKDIR /app

# نسخ ملفات المشروع
COPY . .

# تثبيت الحزم
RUN npm install

# تشغيل التطبيق
CMD ["node", "index.js"]

