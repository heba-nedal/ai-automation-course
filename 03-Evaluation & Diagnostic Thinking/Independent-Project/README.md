# 🚀 U3 Build, Test & Prove Your Web App

> **Build it. Test it. Prove it works.**

---

# 🎯 المهمة

في هذه المهمة، ستقومين ببناء **Web App** من اختيارك باستخدام:

- **Lovable** لبناء التطبيق
- **Supabase** لإدارة البيانات والمستخدمين
- **Testing** للتحقق من أن التطبيق يعمل كما هو متوقع

الفكرة **من اختيارك**.

يمكنك بناء أي تطبيق بسيط يحل مشكلة حقيقية أو يقدم فائدة واضحة.

### أمثلة:

- Task Manager
- Expense Tracker
- Study Planner
- Habit Tracker
- Event Manager
- Book Tracker
- Job Application Tracker
- Small Business Dashboard
- Appointment Manager
- Personal Organizer

أو أي فكرة أخرى تختارينها.

> **لا نريد تطبيقًا ضخمًا.**
>
> اختاري فكرة صغيرة وواضحة، وابنيها بشكل جيد واختبريها.

---

# 🧠 المطلوب منك

المهمة تتكون من جزأين:

## Part 1 — Build

ابني الـ **Web App** باستخدام:

**Lovable + Supabase**

يجب أن يحتوي التطبيق على الأقل على:

- واجهة واضحة للمستخدم
- وظيفة أساسية مفيدة
- بيانات محفوظة في **Supabase**
- إمكانية إضافة / تعديل / حذف البيانات عند الحاجة
- **Authentication** إذا كانت فكرة التطبيق تحتاج مستخدمين وحسابات

---

# 🧪 Part 2 — Test

بعد بناء التطبيق:

> **لا تفترضي أنه يعمل فقط لأنه تم بناؤه.**

اختبريه.

حاولي اكتشاف:

- هل الوظائف الأساسية تعمل؟
- هل البيانات تُحفظ بشكل صحيح؟
- هل يمكن للمستخدم تنفيذ الـ main flow؟
- ماذا يحدث عند إدخال بيانات خاطئة؟
- ماذا يحدث عندما تكون البيانات ناقصة؟
- هل توجد حالات لا يعمل فيها التطبيق كما توقعتِ؟

---

# 🔍 Test Your App

اختاري أهم الوظائف في تطبيقك واختبريها.

على الأقل:

### ✅ Positive Test

اختبري حالة صحيحة.

مثال:

> إضافة Task جديدة ببيانات صحيحة.

**Expected:**  
يتم إنشاء الـ Task وحفظها.

**Actual:**  
ما حدث فعليًا.

---

### ❌ Negative Test

اختبري حالة غير صحيحة.

مثال:

> محاولة إضافة Task بدون عنوان.

**Expected:**  
يمنع التطبيق العملية أو يعرض رسالة مناسبة.

**Actual:**  
ما حدث فعليًا.

---

### ⚠️ Edge Case

اختبري حالة غير معتادة.

مثال:

> إدخال قيمة طويلة جدًا أو بيانات غير متوقعة.

**Expected:**  
التطبيق يتعامل معها بشكل آمن.

**Actual:**  
ما حدث فعليًا.

---

# 🐛 Fix & Re-test

إذا اكتشفتِ مشكلة:

**Don't just report it. Fix it.**

استخدمي **Lovable / Supabase** لمعالجة المشكلة.

ثم:

> **Test Again**

للتأكد أن المشكلة تم حلها.

---

# 📋 المطلوب تسليمه

لا نريد تقريرًا طويلًا.

سلّمي **ملفًا واحدًا فقط**:

`README.md`

ويحتوي على:

```text
# Project Name

## 1. Project Idea

What does the app do?

## 2. Main Feature

What is the main thing the user can do?

## 3. Tech Stack

- Lovable
- Supabase

## 4. Testing

### Test 1
- Scenario:
- Expected:
- Actual:
- Result: PASS / FAIL

### Test 2
- Scenario:
- Expected:
- Actual:
- Result: PASS / FAIL

### Test 3
- Scenario:
- Expected:
- Actual:
- Result: PASS / FAIL

## 5. Bugs Found

What problems did you discover?

## 6. Improvements

What did you fix?

## 7. Evidence

Add screenshots showing important test results.

## 8. Project Link

Live App:

GitHub:
```

---

# 📸 Evidence

Testing لا يعني فقط أن تقولي:

> "It works."

نريد **Evidence**.

أضيفي Screenshots بسيطة توضح بعض الاختبارات المهمة، مثل:

- Test ناجح
- Validation أو Error
- البيانات داخل Supabase
- نتيجة بعد إصلاح Bug

لا تحتاجين إلى Screenshot لكل خطوة.

> **Show evidence for the important things you tested.**

---

# ⭐ Minimum Requirements

قبل التسليم، تأكدي أن تطبيقك:

- [ ] تم بناؤه باستخدام **Lovable**
- [ ] يستخدم **Supabase**
- [ ] يحتوي على وظيفة أساسية واضحة
- [ ] يخزن البيانات في Supabase
- [ ] تم اختباره
- [ ] تم تنفيذ Positive Test
- [ ] تم تنفيذ Negative Test
- [ ] تم تجربة Edge Case
- [ ] تم إصلاح المشاكل التي اكتشفتِها قدر الإمكان
- [ ] تم إعادة الاختبار بعد الإصلاح
- [ ] توجد Evidence
- [ ] يوجد رابط للتطبيق

---

# 🧠 السؤال الأهم

لا تسألي نفسك فقط:

> **"هل بنيت التطبيق؟"**

اسألي:

> **"How do I know it works?"**

هذه هي الفكرة الأساسية في U3.

---

# 🌱 U3 Mindset

في U2:

> **Build the System.**

في U3:

> **Prove It Works.**

التطبيق الذي تم بناؤه ليس بالضرورة تطبيقًا يعمل بشكل صحيح.

المهندسة الجيدة لا تكتفي بأن ترى النظام يعمل مرة واحدة.

بل:

**Test → Find → Fix → Re-test → Prove**

> **Don't just build it. Test it, improve it, and prove it works.**
