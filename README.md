# Particle Universe — Ultimate Edition

## 🎮 ما هو هذا المشروع؟
تطبيق ويب تفاعلي 3D يعرض جزيئات ملونة تتحكم بها عبر:
- **اليد** (Hand Tracking — MediaPipe)
- **العين** (Eye Tracking — MediaPipe Face Mesh)
- **الصوت** (Audio Reactive)
- **المستقبل**: تأثيرات فضاء (🚀 SPACE) وألوان نيون (💡 NEON)

---

## ✅ كيف أعرف إذا تغير شيء؟

### 1. على Vercel (موجود بالفعل):
الرابط من الصورة الأولى:
```
https://hand-particles-xxxx.vercel.app
```
(افتحه من لوحة Vercel → Deployment → Visit)

### 2. على GitHub:
الرابط: `https://github.com/datkmoon/hand-particles`
- الفرع الحالي: `arena/019fbe9b-hand-particles`
- آخر commit: `2882155` — "Add hand/eye games, futuristic UI..."

### 3. محلياً:
```bash
python3 -m http.server 8080
# افتح: http://localhost:8080
```

---

## 🔧 ما تم إضافته (كل شي دفعة واحدة):

| الميزة | الزر في اللوحة |
|---|---|
| ✋ ألعاب اليد | `HAND GAME` |
| 👁 تتبع العين | `EYE TRACK` |
| 🚀 تأثيرات فضاء | `SPACE` |
| 💡 ألوان نيون مستقبلية | `NEON` |

---

## 📁 الملفات المهمة:
- `index.html` — الموقع الكامل (تم تعديله)
- `vercel.json` — إعدادات النشر
- `DEPLOY.md` — دليل التشغيل

---

## 🌐 نشر على Vercel (من اللوحة اللي في الصورة):
```bash
npm i -g vercel
vercel --prod
```
أو من GitHub → Import Project → ربط بـ Vercel.
