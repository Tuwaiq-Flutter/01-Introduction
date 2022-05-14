# Introduction

# نظرة عامة
![](https://lh6.googleusercontent.com/wF0_vrykRT1iXUg16qY9Kqez_MbZXDxO5KpjqjF11S34h71p3itAOrsrV65EscdDLWS_w24EyJPaHpxY9QbDxUzi2RpHG0wKyp_Bud_KY52fJTIL3j3phpR7IuZ9HRtI2uBxWsCEr9H2MvJqzA)


في هذا المحتوي سوف تتعلم ما هي لغة Dart ولماذا تم إنشاء Dart وأيضا المفاهيم المهمة والتي يجب على كل مبرمج أن يتعلمها. ويمكنك الاطلاع على الموقع الرسمي الخاص في Dart عن طريق الرابط التالي : 

https://www.dartlang.org/

# مقدمة

لماذا لغة Dart ؟
تعتبر لغة Dart لغة من لغات البرمجة مفتوحة المصدر، وتم تطويرها هذه اللغة من قبل شركة Google. ويمكن استخدام لغة Dart على نطاق واسع  في كلا الجانبين ( User and Server ). والهدف من هذه اللغة هو تمكين المطورين من إنشاء تطبيقات عالية الأداء بكتابة كود واحد يعمل علي اكثر من منصة مثل الاجهزه الذكيه والسيرفرات وايضا الويب دون ان تحتاج الى تعلم لغة أخرى  . ايضا هناك ميزة أخرى وهي  إمكانية تحويل كود لغة dart الي JavaScript.
 وتعتبر لغة Dart من اللغات التي تدعم مفهوم OPP اختصار مفهوم (Object-Oriented Programming) أي أنها تدعم مفاهيم [Class,object,interfaces, generics] وغيرها من مفاهيم البرمجة. وهي مشابه في طريقة الكتابة إلى لغات كثيرة مثل C و Java و أيضا لغة Swift وغيرها من اللغات .
 ومن الأشياء التي يجب ذكرها هي أن تعلم لغة Dart يعتبر من الاشياء الممتعه لسهولة تعلم اللغه 

## ظهور لغة Dart 

أول إعلان للغة دارت كان في سنة 2011  في مؤتمر Goto. من قبل المطورين Lars Bak and Kasper Lund. 


## مميزات لغة Dart 

1- لا تحتاج إلى تعلم لغة برمجية أخرى لتعلم لغة Dart. فهي لغة  سهلة التعلم
2-  تستخدم مترجم بخاصية Hot Reload الذي يقوم بعرض تغييرات الكود بشكل مباشر
3- مفتوحة المصدر وايضا تدعم مفهوم OPP 
4- يمكنك من خلال هذه اللغة تطوير تطبيقات الويب لأنها  تتوافق مع لغة JavaScript  وايضا تطوير تطبيقات ios و android
6- دعم كبير من شركة Google وأعلنت أنها تعتمد عليها في أعمالها ومشاريعها. 

## المترجم (Compiler)

ما هو المترجم أو Compiler ؟
المترجم أو Compiler بعمل دور الوسيط بين اللغة التي يستخدمها المبرمج باللغة التي يفهمها الحاسب (لغة الآلة).

![](https://lh4.googleusercontent.com/aXwAY30sHtEujCXZaddvyqqOYL_CBPuPZNvLeFwNUXAxC9DOJIQ9wUVtHj4xlXYzW032dXa-VmBLsTiKfqYyOgYWGyJ-Ai9MgtEOZ0PS06Ip-acNkHAjZWu3KEl7u1z9NKDjCXiLpLedy2Iu1Q)


فهو برنامج خاص يعالج الاكواد المكتوبة بلغة برمجة معينة عالية المستوى (High-level language) ويحولها إلى لغة آلة أو "رمز" (Machine language ) يمكن لمعالج الكمبيوتر فهمه. لدى بعض المترجمات امكانية التحقق من الأخطاء وايضاً وقدرات أخرى. يمكن البحث والتعلم الكثير حول Compiler لفهم كيفية عمله 


## المترجم (Compiler) في لغة Dart

تحتوي دارت علي نوعين من Compiler :
AOT -1 اختصار Ahead of Time :
 يعمل عن طريق تجميع الكود  قبل "تسليمها" إلى أي بيئة تشغيل تقوم بتشغيل هذا الكود. في اكثر الاحيان يتم استخدام AOT عندما يكون التطبيق جاهزًا للنشر. فهو يعمل وقت تشغيل ويدير الذاكرة باستخدام تخصيص سريع للأ Object ويكون لديه بدء تشغيل سريع وأداء وقت تشغيل متسق 
JIT -2 اختصار Just-In-Time :
يقوم بتحويل الكود إلى كود native قبل تنفيذ البرنامج مباشرة.وهو أحد العوامل المساعدة في سرعة التطبيق في التطوير. لذى يتم استخدام JIT لتحسين سرعة الأداء.



# اشياء مهم معرفتها قبل البدء في لغة Dart 


**مكونات البرنامج :**
يتم إنشاء كل برنامج من شيئان أساسيان وهما :
**١-  البيانات (Data)**
لا يخلو أي برنامج من بيانات يتم تزويدها داخل البرنامج ليتم عرضها أو معالجتها وتكون البيانات أو نصوص أو صور أو غيرها فبدون البيانات لا يستفاد من البرنامج 
**٢- العمليات (Operations)**
هي الأشياء التي يتم كتابتها داخل البرنامج ليتم التعامل مع البيانات ومعالجتها مثل استعراضها أو تحديثها أو حذفها وغيرها من العمليات 


**التسلسل في الاكواد (Sequence) :**
يتم التسلسل في الاكواد داخل دالة Main فعند تنفيذ الاكواد سوف يتم المرور على السطر الاول ثم السطر الذي يليه حتى يصل الى السطر الاخير 

![](https://lh6.googleusercontent.com/1ppuLQ7xagVOtFVTG30LIw0Yo7GvRZg9SkFaXmWLJwr4U7cl9qJmVebLfIiHneuwckBy00RcB35A3YfUEPa07_pcptXM_oqxig0gG8cZQ6FzEuRPVzzPAIAe480MHalB0hqs0cpi0cRPxzUCoQ)





## **محرر النصوص البرمجية  او مايسمى IDE:**

**لماذا نحتاج محرر اكواد لكتابة الأكواد البرمجية في أي لغة ؟**
تعمل IDEs على زيادة إنتاجية المبرمج من خلال الجمع بين الأنشطة الشائعة لكتابة البرامج والتطبيقات  في مكان واحد:مثل :
كتابة وتعديل على الاكواد ، عملية تشغيل الملفات  او ماتسمى عملية build & run  ، تصحيح الأخطاء أو  debugging. وغيرها من العمليات التي يحتاجها المبرمج 

## **بإمكانك استخدام أحد IDE التالية لكتابة اكواد Dart :**
![](https://lh3.googleusercontent.com/2K5NQlX-T1lIrW11ob5orRUjKx45Jlk69vxQNXF1ISuRU3NAkP1i47M04r9gA1pgG05_3a0clTAKCaqIeoRxF_RYF6mNV_OoXp3N7Z7wQ_AjjFMiITBRsZBHOCl48e2QLVNjJ8Fz-U5Xsto_0A)
![](https://lh4.googleusercontent.com/6iyKh3hcywuuZmReSWVZUjukoSyz0jjVXgVEC0stxl-Nf6bA2QR0AS8OEJIGo6rQQdGrtmBH_g1QcxdluakCoRVwznNm5fa4JCxkHASTweUs5iV_TgKMyKr_-N35SzeyUs6bS9kE9AJsopNBlQ)
![](https://lh4.googleusercontent.com/IkLZ6eLKYLOeeA_zM1a2eBtPOALinunFTLdTnIjksmxhQ9DoZd7LIh1sIELe8FQzZRyr4EklWYWo4k8-gl3G91IFDXCU_ZUzUv3bANIDCgJOYJ3Ssk4HQS0bOI9rxn9yVbSuvrhAGwl98Z5ppQ)


          
         
       **Visual Studio Code                                       IntelliJ IDEA                                   Android Studio**
       
       
 او استخدام Online editor for dart عن طريق الرابط التالي :
[**https://dartpad.dartlang.org/**](https://dartpad.dartlang.org/)

