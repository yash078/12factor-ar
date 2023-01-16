# مقدمة



في العصر الحديث، يتم توزيع البرمجيات على شكل خدمة: تسمى *تطبيقات الويب*، أو *برمجيات كما خدمة*. تعتبر *تطبيقات العشرة عوامل* طريقة لبناء تطبيقات كما خدمة تستخدم:

* صيغ **التعريفية** لتلقي الإعدادات التلقائية، لتقليل الوقت والتكلفة للمطورين الجدد الذين ينضمون إلى المشروع؛

* لديها **عقد نظيف** مع نظام التشغيل الأساسي، وتقدم **الانتقالية القصوى** بين بيئات التنفيذ؛

* مناسبة للتوزيع على منصات السحابة الحديثة، والتي تجنب الحاجة إلى الخوادم وإدارة النظم؛

* **تقليل التشابه** بين التطوير والإنتاج، مما يسمح بتوزيع **التوزيع المستمر** للحصول على أعلى سرعة؛

* ويمكن أن تقوم بالتوسع **بدون** تغييرات ملحوظة في الأدوات، والهندسة، أو الممارسات التطويرية.


يمكن تطبيق طريقة تطبيقات العشرة عوامل على التطبيقات المكتوبة بأي لغة برمجة، والتي تستخدم أي تركيبة من الخدمات الخلفية (قاعدة البيانات، والطابور، وذاكرة التخزين المؤقت، إلخ).

[]: # Path: content/ar/codebase.md

Introduction
============

In the modern era, software is commonly delivered as a service: called *web apps*, or *software-as-a-service*.  The twelve-factor app is a methodology for building software-as-a-service apps that:

* Use **declarative** formats for setup automation, to minimize time and cost for new developers joining the project;
* Have a **clean contract** with the underlying operating system, offering **maximum portability** between execution environments;
* Are suitable for **deployment** on modern **cloud platforms**, obviating the need for servers and systems administration;
* **Minimize divergence** between development and production, enabling **continuous deployment** for maximum agility;
* And can **scale up** without significant changes to tooling, architecture, or development practices.

The twelve-factor methodology can be applied to apps written in any programming language, and which use any combination of backing services (database, queue, memory cache, etc).
