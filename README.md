# 🧠 ZIbda (زبدة) - Smart Academic Learning Platform

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-Hosting-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<p align="center">
  <b>منصة التعلم الذكي والمحتوى الأكاديمي لطلاب كلية الحاسبات والذكاء الاصطناعي (المستوى الثاني) بجامعة الدلتا. تجميع شامل للمقررات والمحاضرات والسكاشن والمواد التفاعلية في واجهة واحدة حديثة وسريعة.</b>
</p>

</div>

---

## 📚 Overview | نبذة عن المنصة

منصة **زبدة (ZIbda)** هي بوابة أكاديمية تفاعلية تم تصميمها لتسهيل وصول طلاب الذكاء الاصطناعي وعلوم الحاسب إلى المراجع والمحاضرات والعروض التقديمية والسكاشن العملية. تمتاز المنصة بتصميم عصري داعم للوضع الليلي (Dark Mode)، خطوط طبوغرافية عربية أنيقة (`IBM Plex Sans Arabic`)، وتنظيم منهجي لكل مادة ومخرجاتها التعليمية.

---

## 🎯 Covered Courses | المواد الأكاديمية المشمولة

- 📊 **تنقيب البيانات (Data Mining):** مقدمة في تحليل واستخراج الأنماط وقواعد البيانات الضخمة.
- ⚡ **المنطق الرقمي (Digital Logics):** الدوائر التوافقية والتتابعية والشيتات العملية.
- 🤖 **تعلم الآلة (Machine Learning):** مفاهيم خوارزميات التعلم الخاضع وغير الخاضع للإشراف، المعالجة المسبقة للبيانات، والموديلات الأساسية.
- 🌐 **شبكات الحاسب (Computer Networks):** طبقات نموذج OSI والبروتوكولات ونماذج المحاكاة والسكاشن.
- 📈 **بحوث العمليات (Operations Research):** البرمجة الخطية (Linear Programming)، الصياغة الرياضية، وحل المشكلات التخطيطية.

---

## ✨ Key Features | المميزات الأساسية

- 🌓 **Tailwind Dark Mode:** مظهر داكن أنيق ومريح للعين أثناء جلسات المذاكرة الطويلة.
- 📂 **Structured Course Materials:** تقسيم منظم للمحاضرات (PDFs)، العروض التقديمية (PPTX)، والملخصات (Markdown).
- ⚡ **High-Speed & Responsive:** تحميل فوري وتوافق تام مع شاشات الهواتف والأجهزة اللوحية والحواسيب المكتبية.
- 🔥 **Firebase Hosting Ready:** ملف إعدادات `firebase.json` مجهز مسبقاً مع إعدادات التخزين المؤقت وحماية الـ CORS.
- 🔄 **GitHub Pages Compatibility:** توجيه تلقائي مباشر من الجذر لتشغيل المنصة بنقرة واحدة عبر صفحات GitHub.

---

## 📂 Project Structure | هيكل المشروع

```plaintext
ZIbda/
├── index.html                   # صفحة التوجيه التلقائي المباشر (GitHub Pages)
├── firebase.json                # إعدادات الاستضافة لـ Firebase Hosting
├── smart_learning_platform/
│   ├── index.html               # الواجهة التفاعلية الرئيسية للمنصة
│   ├── lecture_material.md      # ملخصات وشروحات المواد الأكاديمية
│   ├── open.bat                 # اختصار فتح المنصة في المتصفح بنقرة واحدة
│   └── materials/               # المجلد الأكاديمي المنظم
│       ├── datamining/          # سلايدات ومحاضرات تنقيب البيانات
│       ├── digitallogics/       # شيتات وتمارين المنطق الرقمي
│       ├── ml/                  # محاضرات وتطبيقات تعلم الآلة
│       ├── networks/            # مقررات وسكاشن شبكات الحاسب
│       └── or/                  # أوراق وبحوث العمليات
├── .gitignore                   # استبعاد الملفات المؤقتة
└── README.md                    # التوثيق الشامل للمشروع
```

---

## 🚀 How to Run | طريقة التشغيل

### تشغيل محلي:
افتح ملف `index.html` في أي متصفح، أو انقر نقراً مزدوجاً على `smart_learning_platform/open.bat`.

### النشر عبر Firebase Hosting:
```bash
firebase deploy --only hosting
```

---

## 👨‍💻 Developer & Author

Developed by **[Mohamed Shaaban (momoshworks)](https://github.com/momoshworks)**  
Faculty of Artificial Intelligence — Delta University for Science and Technology.

---

## 📄 License
This project is open-source under the MIT License.
