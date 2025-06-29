# دليل نشر الموقع 🚀

## الطرق المتاحة للنشر

### 1️⃣ **Netlify (الأسهل والأسرع) - مجاني**

#### الخطوات:
1. **اذهب إلى [netlify.com](https://netlify.com)**
2. **اضغط "Sign up" وسجل دخول بـ GitHub**
3. **اضغط "New site from Git"**
4. **اختر GitHub واختر repository: `medical-chatbot-website`**
5. **في إعدادات البناء:**
   - Build command: `npm run build`
   - Publish directory: `dist`
6. **اضغط "Deploy site"**

✅ **النتيجة:** هتحصل على رابط مثل: `https://amazing-name-123456.netlify.app`

---

### 2️⃣ **Vercel - مجاني**

#### الخطوات:
1. **اذهب إلى [vercel.com](https://vercel.com)**
2. **اضغط "Sign up" وسجل دخول بـ GitHub**
3. **اضغط "New Project"**
4. **اختر repository: `medical-chatbot-website`**
5. **اضغط "Deploy"**

✅ **النتيجة:** هتحصل على رابط مثل: `https://medical-chatbot-website.vercel.app`

---

### 3️⃣ **GitHub Pages - مجاني**

#### الخطوات:
1. **في repository بتاعك على GitHub**
2. **اذهب إلى Settings → Pages**
3. **في Source اختر "GitHub Actions"**
4. **أنشئ ملف `.github/workflows/deploy.yml`**

---

## 🎯 التوصية

**أنصحك بـ Netlify** لأنه:
- ✅ سهل جداً
- ✅ مجاني
- ✅ يدعم التحديث التلقائي
- ✅ يعطيك رابط جميل
- ✅ يمكن تغيير اسم الرابط

## 📱 بعد النشر

بعد ما تنشر الموقع، هتقدر:
- تشارك الرابط مع أي حد
- الموقع هيشتغل على الموبايل والكمبيوتر
- أي تحديث تعمله في الكود هيظهر تلقائياً

## 🔧 إعدادات إضافية

### تغيير اسم الرابط في Netlify:
1. اذهب إلى Site settings
2. اضغط "Change site name"
3. اكتب اسم جديد مثل: `medical-assistant-egypt`
4. الرابط هيبقى: `https://medical-assistant-egypt.netlify.app`

### إضافة دومين مخصوص (اختياري):
- يمكن تشتري دومين مثل `medical-assistant.com`
- وتربطه بالموقع من إعدادات Netlify