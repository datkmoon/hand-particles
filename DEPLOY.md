# Particle Universe — Hand & Eye Games + Futuristic Edition

## ما تمت إضافته (كل شي دفعة واحدة):

### 1. ألعاب عبر اليد (Hand-Only Game Mode)
- اضغط زر ✋ HAND GAME من اللوحة
- يتحكم المشهد بالكامل بحركة اليد عبر الكاميرا
- قبضة اليد (Fist) تتحكم في مقياس الجزيئات

### 2. ألعاب عبر العين (Eye Tracking)
- اضغط زر 👁 EYE TRACK من اللوحة
- يستخدم MediaPipe Face Mesh لتتبع حركة العين
- اتجاه نظرك يتحكم في دوران المشهد

### 3. تأثيرات المستقبل (Futuristic)
- زر 🚀 SPACE: تأثيرات فضاء + ضباب نيون
- زر 💡 NEON: ألوان نيون (وردي/أزرق فاتح) + واجهة هولوغرام
- زر ✋ HAND GAME + زر 👁 EYE TRACK موجودان في اللوحة

### 4. ربط وتشغيل الموقع

**تشغيل محلي:**
```bash
python3 -m http.server 8080
# افتح: http://localhost:8080
```

**نشر على Vercel:**
```bash
# إذا لم يكن vercel مثبت:
npm i -g vercel

# داخل مجلد المشروع:
vercel --prod
# أو عبر GitHub:
# 1. ارفع الكود لـ GitHub
# 2. اربط المستودع من dashboard.vercel.com
```

### 5. ميزات إضافية موجودة سابقاً:
- رفع نماذج 3D (GLB/GLTF/OBJ)
- تحويل صور إلى جزيئات
- تفاعل مع الصوت (Audio Reactive)
- تصدير PNG / SVG / OBJ / STL / GLB / CSV / فيديو
