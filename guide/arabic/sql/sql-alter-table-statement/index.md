---
title: SQL Alter Table Statement
localeTitle: SQL جدول الترتيب
---
## دليل SQL - ALTER TABLE

## المقدمة

سيقدم لك هذا الدليل شرحًا عن بعض أساسيات وظائف جدول التغيير في SQL ومحاولة شرحها داخل قاعدة بيانات علائقية. **تلميح أمان هام: قم دائمًا بنسخ بياناتك احتياطيًا قبل إجراء التغييرات!**

سنستخدم MySQL لكل الأمثلة في دليل SQL freeCodeCamp هذا. أسباب اختيار MySQL هي 1) وهي شائعة الاستخدام على المواقع الإلكترونية لقاعدة البيانات الخلفية ، 2) وهي مجانية ، وهي ممتعة وسهلة الاستخدام.

## مغطاة في هذا الدليل

سوف نستخدم الجداول التي تم إنشاؤها في دليل "CREATE TABLE". لا تتردد في مراجعة هذا الدليل إذا لم تكن معتادًا على إنشاء جدول.

*   سيؤدي تغيير الجدول الذي تم إنشاؤه إلى تغييره بعدة طرق مختلفة.
*   سنقوم بتغيير اسمها وتعديل الأعمدة
*   إضافة أعمدة (أثناء إضافة الأعمدة سنقوم أيضًا بمراجعة العديد من أنواع الأعمدة الأكثر أهمية واستخدامها).
*   إسقاط الأعمدة (يعني إزالة العمود).
*   إنشاء جدول عن طريق استيراد ملف CSV وتعديل هذا الجدول.
*   إنشاء وتعديل الجداول باستخدام أدوات طاولة MySQL.

سيتم تنفيذ معظم هذا باستخدام عبارات SQL في أداة البرمجة النصية لـ MySQL لكننا سنراجع أيضًا كيفية تغيير جدول باستخدام واجهة طاولة العمل بدلاً من عبارات SQL.

## الجدول قبل التعديلات:

![صورة 1](https://github.com/SteveChevalier/guide-images/blob/master/alter_table01a.JPG?raw=true)

إضافة أعمدة التاريخ وعنوان البريد الإلكتروني (تاريخ وعمود الحرف): ![صورة 1](https://github.com/SteveChevalier/guide-images/blob/master/alter_table01.JPG?raw=true)

إضافة عمود رقمي (لاحظ أنه تمت إضافته في موقع محدد في الجدول): ![صورة 1](https://github.com/SteveChevalier/guide-images/blob/master/alter_table02.JPG?raw=true)

إعادة تسمية بعض الأعمدة: ![صورة 1](https://github.com/SteveChevalier/guide-images/blob/master/alter_table03.JPG?raw=true)

إزالة عمود: ![صورة 1](https://github.com/SteveChevalier/guide-images/blob/master/alter_table04.JPG?raw=true)

يمكنك أيضا استخدام أداة طاولة العمل منضدة التغيير. فقط انقر على الطاولة التي تريد تغييرها وتغييرها كما تشاء. ![صورة 1](https://github.com/SteveChevalier/guide-images/blob/master/alter_table05.JPG?raw=true)

هناك الكثير مما يمكن القيام به ، والتحقق من دليل برنامج إدارة قاعدة البيانات لمعرفة المزيد.