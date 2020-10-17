---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "@@Mobile Accessibility at W3C"
nav_title: "@@Mobile Accessibility at W3C"

description: 

lang: ar
last_updated: 2020-10-00
permalink: /standards-guidelines/mobile/ar

# translators:
# - name: "@@"
# contributors:
# - name: "@@"

github:
  repository: w3c/wai-mobile
  path: index.ar.md

feedbackmail: wai@w3.org
footer: >
  <p>@@
</p>
ref: /standards-guidelines/mobile/
---

## @@ CONTENT BELOW FROM OTHER PAGE FOR TESTING PURPOSES

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}
 
يقدم هذا التقرير بعض متطلبات نفاذية الويب؛ للمواقع، والتطبيقات، ومتصفحات الويب والأدوات الأخرى. و يوفر أيضاً مراجع للمعايير الدولية من مبادرة W3C لنفاذية الويب (WAI) و [قصص مستخدمي الويب]( /people-use-web/user-stories/)
 
**ملاحظة:** هذه القائمة لاتحتوي على كل متطلبات إمكانية الوصول.
 
{::nomarkdown}
{% include box.html type="end" %}
{:/}
 
 
{::options toc_levels="2,3" /}
 
{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}
 
-   TOC is created automatically.
{:toc}
 
{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}
 
 
{% include excol.html type="all" %}
 
## متطلبات وصول الويب{#standards}
 
نفاذية الويب تستند على عدة مكونات تعمل جنبًا الى جنب، وهي كالتالي:
 
-   **محتوى الويب**{:#webcontent} - ويعنى بأي جزء من الموقع الالكتروني، ويشمل ذلك النصوص، الصور، النماذج، الوسائط المتعددة، والكود البرمجي بما في ذلك التطبيقات البرمجية.
-   **وكيل الويب**{:#useragents} - وهو تطبيق يستخدمه الناس للوصول الى محتوى شبكة الويب، ويشمل ذلك متصفحات أجهزه سطح المكتب، المتصفحات الصوتية، المتصفحات الخاصة بالهواتف الذكية، مشغلات الوسائط المتعددة، وبعض [التقنيات المساعدة]( /people-use-web/tools-techniques/#at “definition”)

-   ** أدوات التأليف (البرمجة) **{:#authoringtools} - وهي برامج وتطبيقات تمكن الأشخاص من إنشاء محتوى في الويب، ويشمل ذلك محررات الكود البرمجي، أدوات تحويل المستندات، انظمة ادارة المحتوى، المدونات، نصوص قواعد البيانات، وبعض الأدوات الأخرى
 
{% include excol.html type="start" %}
 
### المزيد عن متطلبات وصول الويب
{:.no_toc}
 
{% include excol.html type="middle" %}

These components inter-relate and support each other. For instance, **web content** needs to include text alternatives for images. This information needs to be processed by **web browsers** and then conveyed to **assistive technologies**, such as screen readers. To create such text alternatives, authors need **authoring tools** that support them to do so. More background is provided in [[Essential Components of Web Accessibility]](/fundamentals/components/).
 
هذه المكونات مترابطة و تدعم بعضها البعض. على سبيل المثال, **محتوى الويب** يحتاج إلى تضمين بدائل نصية عوضاً عن الصور. هذه المعلومات تحتاج إلى المعالجة من قبل **متصفح الويب** و بعد ذلك تنقل إلى **التكنولوجيا المساعدة**, مثل قارئ الشاشة. لإنشاء بدائل نصية يحتاج المؤلفين إلى **أدوات تأليف** تدعمهم للقيام بذلك. المزيد من المعلومات متوفرة في [[المكونات الرئيسية للوصول الى الويب]]( /fundamentals/components)

Standards play a vital role in defining accessibility requirements for each of these components. Some accessibility requirements are easy to meet, yet understanding the basics of how people with disabilities use the Web helps implement them more effectively and efficiently. Some aspects of accessibility require more technical skills or advanced knowledge of how people use the Web. In all cases, [involving users early and throughout your web projects](/test-evaluate/involving-users/) will make your work better and easier.

تلعب المعايير دوراً رئيسياً في تحديد متطلبات النفاذية لكل من هذه المكونات. بعض متطلبات الوصول سهلة التحقيق, بينما فهم أساسيات كيفية استخدام الأشخاص ذوي الإعاقة للويب يساعد في تنفيذها بشكل أكثر فعالية وكفاءة. تتطلب بعض جوانب إمكانية الوصول مهارات تقنية أو معرفة متقدمة عن كيفية استخدام الأشخاص للويب. في كل الأحوال ، [إشراك المستخدمين مبكراً خلال مشاريع الويب الخاصة بك]( /test-evaluate/involving-users/)  سوف يساهم بجعل عملك أفضل وأسهل.


The W3C Web Accessibility Initiative (WAI) provides a set of guidelines that are internationally recognized as the standard for web accessibility. These include:

مبادرة W3C لنفاذية الويب (WAI) توفر مجموعة من الإرشادات المعترف بها دوليًا كمعيار لإمكانية الوصول إلى الويب وتشمل
 
-   **[إرشادات الوصول إلى محتوى الويب (WCAG)]( /standards-guidelines/wcag/)**
-   **[إرشادات الوصول إلى وكيل الويب (UAAG)]( /standards-guidelines/uaag/)**
-   **[إرشادات الوصول إلى أداة التأليف (ATAG)]( /standards-guidelines/atag/)**



There is also a WAI specification for **[Accessible Rich Internet Applications (WAI-ARIA)](https://www.w3.org/WAI/intro/aria.php)**, which include dynamic content and advanced user interface controls developed with Ajax, JavaScript, and related web technologies.
 
هناك أيضًا مواصفات WAI **[للوصول تطبيقات الإنترنت الغنية (WAI-ARIA) ]( https://www.w3.org/WAI/intro/aria.php)** التي يمكن الوصول إليها والتي تتضمن محتوى ديناميكيًا و عناصر تحكم متقدمة في واجهة المستخدم تم تطويرها باستخدام Ajax و JavaScript وتقنيات الويب آخري ذات صلة.

{% include excol.html type="end" %}
 
## المعلومات المحسوسة و واجهة المستخدم {#perceivable}
 
### بدائل النص للمحتوى الغير نصي {#alternatives}
 
بدائل النصوص هي مساوية للمحتوى غير النصي، مثال على ذلك :
- مرادفات الصور القصيرة، ويشمل ذلك الايقونات، والأزرار، والرسومات
- وصف للبيانات على شكل مخططات واشكال توضيحية
- وصف مختصر عن المحتوى غير النصي مثل المحتوى الصوتي والمرئي
- تسميات توضيحية لأدوات التحكم في النماذج مثل المدخلات وبقية مكونات واجهة المستخدم

Text alternatives convey the purpose of an image or function to provide an equivalent user experience. For instance, an appropriate text alternative for a search button would be "*search*" rather than "*magnifying lens*".
 
بديلات النصوص تعمل كبديل جيد لصورة او وظيفة لإيصال المستخدمين لتجربة مستخدم متوازية، كمثال: بديل نص مناسب لزر البحث سيكون كلمة "*بحث*" عوضاً عن "*عدسة مكبرة".


Text alternatives can be presented in a variety of ways. For instance, they can be read aloud for people who cannot see the screen and for people with reading difficulties, enlarged to custom text sizes, or displayed on braille devices. Text alternatives serve as labels for controls and functionality to aid keyboard navigation and navigation by voice recognition (speech input). They also act as labels to identify audio, video, and files in other formats, as well as applications that are embedded as part of a website.
 
بديلات النصوص من الممكن تمثيلها بطرق مختلفة ومتنوعة، كمثال من الممكن ان يتم قراءتها بصوت عالي للأشخاص الذين لا يستطيعون رؤية الشاشة او للأشخاص الذين يعانون من صعوبات بالقراءة، قد يشمل ذلك أحجام معدلة للنصوص، او اظهار نصوص مكتوبة على أجهزة برايل. بديلات النصوص تعمل كأدوات بديلة عن ازرار التحكم لتسهيل استخدام لوحة المفاتيح، او الوصول باستخدام الأوامر الصوتية، من الممكن كذلك ان تعمل على التعرف على الأصوات (Speech input) او الملفات المرئية او اي صيغة من الملفات المستخدمة في الحاسوب، كالبرامج والتطبيقات البرمجية التي تعد جزءً من المواقع الالكترونية.

{% include excol.html type="start" %}
 
#### متطلبات الوصول المتعلقة بـ بدائل النصوص(روابط للوصف التقني)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**

-   [إرشادات – 1.1 بدائل النص]( https://www.w3.org/WAI/WCAG21/quickref/#text-alternatives)


**UAAG**

-   [إرشادات – 1.1 محتوى البديل]( https://www.w3.org/TR/UAAG20/#gl-access-alternative-content)

  
**ATAG**
 
-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.1: (For the authoring tool user interface) Make alternative content available to authors](https://www.w3.org/TR/ATAG20/#gl_a21)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure that editing-view presentation can be programmatically determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.3.7: (For the authoring tool user interface) Ensure that previews are at least as accessible as in-market user agents](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)
 
-    [المبدأ أ.1: أدوات إنشاء واجهة المستخدم تتبع إرشادات وصول قابلة للتطبيق]( https://www.w3.org/TR/ATAG20/#principle_a1)
-    [المبدأ أ.1.2: (أدوات إنشاء واجهة المستخدم)  القيام بإتاحة المحتوى البديل للمؤلفين]( https://www.w3.org/TR/ATAG20/#gl_a21)
-    [المبدأ أ.2.2: (أدوات إنشاء واجهة المستخدم) التأكد من إمكانية تحديد طريقة عرض التحرير بطريقة برمجية]( https://www.w3.org/TR/ATAG20/#gl_a22)
-    [المبدأ أ.7.3: (أدوات إنشاء واجهة المستخدم) التأكد من أن طرق العرض يمكن الوصول إليها مثل وكلاء الويب المستخدمين]( https://www.w3.org/TR/ATAG20/#gl_b37)
-    [الجزء ب. دعم إنتاج محتوى قابل للوصول]( https://www.w3.org/TR/ATAG20/#part_b)


{% include excol.html type="end" %}
 
{% include excol.html type="start" %}
 
#### قصص ذات صلة ببدائل النصوص
{:#stories-related-to-text-alternatives.no_toc}
 
{% include excol.html type="middle" %}
 
-   [Alex, reporter with repetitive stress injury](/people-use-web/user-stories/#reporter)
-   [Martine, online student who is hard of hearing](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, senior staff member who is blind](/people-use-web/user-stories/#accountant)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia](/people-use-web/user-stories/#classroomstudent)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss](/people-use-web/user-stories/#retiree)
-   [Kaseem, teenager who is deaf and blind](/people-use-web/user-stories/#teenager)
 
 
-   [أليكس, مراسل مصاب بالضغط النفسي المتكرر](/people-use-web/user-stories/#reporter)
-   [مارتين,طالب عبر الإنترنت يعاني من ضعف السمع](people-use-web/user-stories/#onlinestudent/)
-   [ليا, موظف أول كفيف](people-use-web/user-stories/#accountant/)
-   [برييتي, طالب في المرحلة الإعدادية يعاني من اضطراب فرط الحركة وتشتت الانتباه وعسر القراءة](people-use-web/user-stories/#classroomstudent/)
-   [ين, متقاعد مع ضعف البصر ورعاش اليد وفقدان خفيف للذاكرة على المدى القصير](people-use-web/user-stories/#retiree/)
-   [قاسم,مراهق أصم و كفيف](people-use-web/user-stories/#teenager/)




{% include excol.html type="end" %}
 
### التسميات التوضيحية و البدائل الأخرى للوسائط المتعددة  {#captions} 
 
بعض الأمثلة على الاشخاص الذين لا يستطيعون سماع الأصوات او رؤية الملفات المرئية في حاجة الى بدائل:

-   نصوص سردية او تسميات توضيحية للمحتوى الصوتي، مثال: تسجيلات مقابلات الراديو
-   وصف توضيحي للأصوات، والتي تروي وصف التفاصيل المهمة بطريقة مرئية في مقطع مرئي
-   لغة اشارة مرافقة للمحتوى الصوتي، بما في ذلك أي من الأدوات المساعدة لفهم الأصوات
 
المحتوى النصي المكتوب بعناية والذي يحتوي على تسلسل من أي معلومات بديلة للأصوات أو مرئيات يساهم بشكل كبير في توفير وصول أساسي للمعلومة و يسهل إنتاج التسميات التوضيحية للمحتوى الصوتي.

{% include excol.html type="start" %}
 
#### متطلبات الوصول المتعلقة بـ الوسائط المتعددة (روابط للوصف التقني)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
-   [إرشادات 2.1 – الوسائط المؤقتة](https://www.w3.org/WAI/WCAG21/quickref/#time-based-media) 

**UAAG**
 
 -   [إرشادات 1.1 – المحتوى البديل]( https://www.w3.org/TR/UAAG20/#gl-access-alternative-content)
**ATAG**
 
-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.1: (For the authoring tool user interface) Make alternative content available to authors](https://www.w3.org/TR/ATAG20/#gl_a21)
-   [Guideline A.3.7: (For the authoring tool user interface) Ensure that previews are at least as accessible as in-market user agents](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)
 
-   [المبدآ أ.1: أدوات إنشاء واجهة مستخدم تتبع إرشادات وصول قابلة للتطبيق](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [إرشادات أ.1.2: (أدوات إنشاء واجهة المستخدم) القيام بإتاحة المحتوى البديل للمؤلفين](https://www.w3.org/TR/ATAG20/#gl_a21)
-   [إرشادات أ.7.3: (أدوات إنشاء واجهة المستخدم) التأكد من أن المعاينات يمكن الوصول إليها مثل وكلاء المستخدم في السوق](https://www.w3.org/TR/ATAG20/#gl_a37)
-   [الجزء ب. دعم إنتاج محتوى قابل للوصول](https://www.w3.org/TR/ATAG20/#part_b)


{% include excol.html type="end" %}
{% include excol.html type="start" %}
 
#### قصص متعلقة بالوسائط المتعددة  {#stories-related-to-multimedia}
{:.no_toc}
 
{% include excol.html type=”middle” %}
 
-   [Martine, online student who is hard of hearing](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, senior staff member who is blind](/people-use-web/user-stories/#accountant)
-   [Kaseem, teenager who is deaf and blind](/people-use-web/user-stories/#teenager)
 
-   [مارتين,طالب عبر الإنترنت يعاني من ضعف السمع](/people-use-web/user-stories/#onlinestudent)
-   [ليا, موظف أول كفيف](/people-use-web/user-stories/#accountant)
-   [قاسم,مراهق أصم و كفيف](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}
 
### محتويات يمكن تقديمها بطرق مختلف   {#adaptable}
 
لكي يتمكن المستخدمون من تغيير طريقة عرض المحتوى ، من الضروري أن:

-   يتم تمييز العناوين والقوائم والجداول وحقول الإدخال وهياكل المحتوى بشكل صحيح
-   تسلسل المعلومات أو التعليمات مستقلة عن أي عرض تقديمي
-  توفر المستعرضات والتقنيات المساعدة إعدادات لتخصيص العرض التقديمي
 
تلبية هذه المتطلبات يسمح بقراءة المحتوى بشكل صحيح و بصوت عالٍ و واضح و تكييف الصوت تلبية احتياجات وتفضيلات مختلف الأشخاص.على سبيل المثال ، يمكن تقديمه باستخدام مجموعات ألوان مخصصة ، أو حجم النص ، أو أي تصميم آخر لتسهيل القراءة. يسهل هذا المتطلب أيضًا أشكالًا أخرى من التكيف ، بما في ذلك الإنشاء التلقائي لمخططات الصفحات والملخصات لمساعدة الأشخاص في الحصول على نظرة عامة والتركيز على أجزاء معينة بسهولة أكبر.

{% include excol.html type="start" %}
 
#### متطلبات الوصول المتعلقة بالتكيف (روابط للوصف التقني)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
-   [إرشادات 3.1 - التكييف]( https://www.w3.org/WAI/WCAG21/quickref/#adaptable) 

**UAAG**
 
-   [Guideline 1.4 - Text configuration](https://www.w3.org/TR/UAAG20/#gl-text-config)
-   [Guideline 1.5 - Volume configuration](https://www.w3.org/TR/UAAG20/#gl-volume-config)
-   [Guideline 1.6 - Synthesized speech configuration](https://www.w3.org/TR/UAAG20/#gl-speech-config)
-   [Guideline 1.7 - User style sheet configuration](https://www.w3.org/TR/UAAG20/#gl-style-sheets-config)
-   [Guideline 1.9 - Alternative views](https://www.w3.org/TR/UAAG20/#gl-alternative-views)
-   [Guideline 1.10 - Element information](https://www.w3.org/TR/UAAG20/#gl-info-link)
 
-   [إرشادات 4.1 – تكوين النص](https://www.w3.org/TR/UAAG20/#gl-text-config)
-   [إرشادات 5.1 – تكوين النص](https://www.w3.org/TR/UAAG20/#gl-volume-config)
-   [إرشادات 6.1 – تكوين النص](https://www.w3.org/TR/UAAG20/#gl-speech-config)
-   [إرشادات 7.1 – تكوين النص](https://www.w3.org/TR/UAAG20/#gl-style-sheets-config)
-   [إرشادات 9.1 – تكوين النص](https://www.w3.org/TR/UAAG20/#gl-alternative-views)
-   [إرشادات 10.1 – تكوين النص](https://www.w3.org/TR/UAAG20/#gl-info-link)




**ATAG**
 
-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure that editing-view presentation can be programmatically determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.3.7: (For the authoring tool user interface) Ensure that previews are at least as accessible as in-market user agents](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)
 
-   [المبدأ أ.1: إدوات](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [إرشادات أ.2.2: (أدوات إنشاء واجهة المستخدم) التأكد من إمكانية تحديد عرض التحرير بطريقة برمجية](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [إرشادات أ.7.3: (أدوات إنشاء واجهة المستخدم) التأكد من أن المعاينات يمكن الوصول إليها  مثل وكلاء المستخدم في السوق](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [الجزء ب. دعم إنتاج محتوى قابل للوصول](https://www.w3.org/TR/ATAG20/#part_b)



{% include excol.html type="end" %}{% include excol.html type="start" %}
 
#### قصص ذات علاقة بالتكيف
{:.no_toc}
 
{% include excol.html type="middle" %}

-   [ليي, متسوق عبر الإنترنت يعاني من عمى الألوان](/people-use-web/user-stories/#shopper)
-   [أليكس, مراسل مصاب بالضغط النفسي المتكرر](/people-use-web/user-stories/#reporter)
-   [ليا, موظف أول كفيف](/people-use-web/user-stories/#accountant)
-   [برييتي, طالب في المرحلة الإعدادية يعاني من اضطراب فرط الحركة وتشتت الانتباه وعسر القراءة](/people-use-web/user-stories/#classroomstudent)
-   [ين, متقاعد مع ضعف البصر ورعاش اليد وفقدان خفيف للذاكرة على المدى القصير](/people-use-web/user-stories/#retiree)
-   [لويس ، مساعد سوبر ماركت مصاب بمتلازمة داون](/people-use-web/user-stories/#supermarketassistant)
-   [قاسم,مراهق أصم و كفيف](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}
 
### المحتوى يكون أسهل عند الرؤية والسمع{#distinguishable}
 
المحتوى المميز يسهل رؤيته وسماعه. يتضمن هذا النوع من المحتوى:
-   عدم إستخدام اللون كطريقة وحيدة لنقل المعلومات أو تحديد المحتوى
-   أن توفر مجموعات ألوان المقدمة والخلفية الافتراضية تباينًا كافيًا
-   عندما يقوم المستخدمين بتغيير حجم النص حتى اربعة أضعاف أو تغيير تباعد النص ، لن يتم فقد المعلومات
-   يعاد تدفق النص في النوافذ الصغيرة ("إطارات العرض") وعندما يكبر المستخدمون النص
-   يمكن تغيير حجم صور النص أو استبدالها بنص حقيقي أو تجنبها عند الإمكان
-   يمكن للمستخدمين إيقاف أو ضبط مستوى الصوت الذي يتم تشغيله على موقع ويب
-   صوت الخلفية يكون منخفض أو يمكن إيقاف تشغيله لتجنب التداخل أو التشتيت

تساعد تلبية هذه المتطلبات في فصل المقدمة عن الخلفية، لجعل المعلومات المهمة أكثر تميزًا. يتضمن ذلك الاخذ في عين الاعتبار الأشخاص الذين لا يستخدمون التقنيات المساعدة والأشخاص الذين يستخدمونها في التداخل من المحتوى الصوتي أو المرئي البارز في الخلفية. على سبيل المثال، العديد من الأشخاص المصابين بعمى الألوان لا يستخدمون أي أدوات معينة ويعتمدون على تصميم مناسب يوفر تباينًا كافيًا في اللون بين النص والخلفية المحيطة به. بالنسبة للأشخاص الآخرين ، قد يتداخل الصوت الذي يتم تشغيله تلقائيًا مع تحويل النص إلى كلام أو مع [أجهزة الاستماع المساعدة (ALDs)](http://www.w3.org/WAI/training/accessible#ald "definition")

{% include excol.html type="start" %}
 
#### متطلبات الوصول المتعلقة بالتمييز (روابط للوصف التقني)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
 -   [إرشادات 4.1: التمييز]( https://www.w3.org/WAI/WCAG21/quickref/#distinguishable)

**UAAG**
 
-   [إرشادات 3.1: التمييز]( https://www.w3.org/WAI/WCAG21/quickref/#gl-interaction-highlight)
-   [إرشادات 4.1: تكوين النص]( https://www.w3.org/WAI/WCAG21/quickref/#gl-text-config)
-   [إرشادات 5.1: تكوين الصوت]( https://www.w3.org/WAI/WCAG21/quickref/#gl-volume-config)
-   [إرشادات 6.1: تكوين الكلام المركب]( https://www.w3.org/WAI/WCAG21/quickref/#gl-speech-config)
-   [إرشادات 7.1: تكوين ورقة أنماط المستخدم]( https://www.w3.org/WAI/WCAG21/quickref/#gl-style-sheets-config)
-   [إرشادات 8.1: الاتجاه في منافذ العرض]( https://www.w3.org/WAI/WCAG21/quickref/#gl-viewport-orient)
-   [إرشادات 9.1: الآراء البديلة]( https://www.w3.org/WAI/WCAG21/quickref/#gl-alternative-views)
-   [إرشادات 10.1: معلومات العناصر]( https://www.w3.org/WAI/WCAG21/quickref/#gl-info-link)

**ATAG**
 
-   [المبدأ أ.1: أدوات إنشاء واجهة المستخدم تتبع إرشادات وصول قابلة للتطبيق](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [إرشادات أ.7.3: (بالنسبة لأدوات إنشاء واجهة المستخدم) التأكد من أن المعاينات يمكن الوصول إليها مثل وكلاء المستخدم في السوق](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [الجزء ب. دعم إنتاج محتوى قابل للوصول](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}
 
#### قصص ذات علاقة بالتمييز
{:.no_toc}
 
{% include excol.html type="middle" %}

-   [ليي, متسوق عبر الإنترنت يعاني من عمى الألوان]( /people-use-web/user-stories/#shopper)
-   [ليا, موظف أول كفيف]( /people-use-web/user-stories/#onlinestudent)
-   [مارتين, طالب أون لاين يعاني من صعوبات بالسمع]( /people-use-web/user-stories/#accountant)
-   [ين, متقاعد مع ضعف البصر ورعاش اليد وفقدان خفيف للذاكرة على المدى القصير]( /people-use-web/user-stories/#retiree)
-   [قاسم, مراهق أصم و كفيف]( /people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}
 
##  واجهة مستخدم قابلة للتشغيل والتنقل {#operable}

### إتاحة الوظائف من خلال لوحة المفاتيح {#keyboard}
 
العديد من الأشخاص لا يستخدمون الفأرة ويعتمدون على لوحة المفاتيح للتفاعل مع الويب. يتطلب ذلك الوصول إلى لوحة المفاتيح لجميع الوظائف ، بما في ذلك نماذج التحكم، المدخلات، و مكونات واجهة المستخدم الأخرى.

تشمل إمكانية الوصول إلى لوحة المفاتيح:

-   جميع الوظائف المتوفرة عن طريق الفأرة تتوفر أيضاً عن طريق لوحة المفاتيح
-   لا ينحصر تركيز لوحة المفاتيح في أي جزء من المحتوى
-   توفر مستعرضات الويب ،أدوات الإنشاء ،والأدوات الأخرى دعمًا للوحة المفاتيح

يساعد تلبية هذه المتطلبات مستخدمي لوحة المفاتيح ، بما في ذلك الأشخاص الذين يستخدمون لوحات مفاتيح بديلة مثل لوحات المفاتيح ذات التخطيطات المريحة ، لوحات المفاتيح على الشاشة ،أو أجهزة السويتش. كما أنه يساعد الأشخاص الذين يستخدمون التعرف على الصوت (مدخلات الكلام) لتشغيل مواقع الويب وإملاء النص من خلال واجهة لوحة المفاتيح.

{% include excol.html type="start" %}
 
### متطلبات الوصول المتعلقة بوصول لوحة المفاتيح(روابط للوصف التقني)

{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
 -   [إرشادات 1.2: لوحة مفاتيح متاحة للوصول]( https://www.w3.org/WAI/WCAG21/quickref/#keyboard-accessible)

**UAAG**
 
-   [إرشادات 1.2: لوحة مفاتيح متاحة للوصول]( https://www.w3.org/TR/UAAG20/#gl-keyboard-access)
-   [إرشادات 2.2: لوحة مفاتيح متاحة للوصول]( https://www.w3.org/TR/UAAG20/#gl-sequential-navigation)
-   [إرشادات 3.2: لوحة مفاتيح متاحة للوصول]( https://www.w3.org/TR/UAAG20/#gl-direct-navigation-and-activation)
-   [إرشادات 11.2: لوحة مفاتيح متاحة للوصول]( https://www.w3.org/TR/UAAG20/#gl-other-devices)

**ATAG**

-   [المبدأ أ.1: أدوات إنشاء واجهة المستخدم تتبع إرشادات وصول قابلة للتطبيق]( https://www.w3.org/TR/ATAG20/#principle_a1)
-   [إرشادات أ.1.3: (لأدوات إنشاء واجهة المستخدم) توفير الوصول للوحة المفاتيح لخصائص الإنشاء]( https://www.w3.org/TR/ATAG20/#gl_a31)
-   [الجزء ب. دعم إنتاج محتوى قابل للوصول]( https://www.w3.org/TR/ATAG20/#part_b)
 
{% include excol.html type="end" %}{% include excol.html type="start" %}
 
#### قصص ذات علاقة بالوصول للوحة المفاتيح
{:.no_toc}
 
{% include excol.html type="middle" %}
 
-   [أليكس, مراسل مصاب بالضغط النفسي المتكرر]( /people-use-web/user-stories/#reporter)
-   [ليا, موظف أول كفيف]( /people-use-web/user-stories/#accountant)

{% include excol.html type="end" %}
 
 ### وقت المستخدمين الكافي لقراءة المحتوى واستخدامه  {#time} 
 
يحتاج بعض الأشخاص إلى وقت أطول من غيرهم لقراءة المحتوى واستخدامه. على سبيل المثال ، يحتاج بعض الأشخاص إلى مزيد من الوقت لكتابة نص، فهم الإرشادات، تشغيل عناصر التحكم ،أو لإكمال المهام على موقع ويب.

أمثلة على توفير الوقت الكافي لهؤلاء الأشخاص:

-   وقف، تمديد، تعديل الحدود الزمنية ، إلا عند الضرورة
-   إيقاف، تعليق، إخفاء، التنقل، أو تمرير المحتوى
-   تأجيل أو توقيف أي محتوى قد يسبب انقطاع تجربة المستخدم، إلا عند الضرورة
-  إعادة التوثيق عند انتهاء الجلسة دون فقد البيانات

{% include excol.html type="start" %}
 
#### متطلبات الوصول المتعلقة بالوقت الكافي (روابط للوصف التقني)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
-   [إرشادات 2.2 – وقت كافي]( https://www.w3.org/WAI/WCAG21/quickref/#enough-time)
 
**UAAG**
 
-   [إرشادات 2.2 – تفاعل مستقل عن الوقت]( https://www.w3.org/TR/UAAG20/#gl-time-independent)
-   [إرشادات 2.2 – الوقت المتعلق بالوسائط]( https://www.w3.org/TR/UAAG20/#gl-control-inaccessible-content)

**ATAG**
 
-   [المبدأ أ.1: أدوات إنشاء واجهة المستخدم تتبع إرشادات وصول قابلة للتطبيق]( https://www.w3.org/TR/ATAG20/#principle_a1)
-   [إرشادات أ.3.2: ( لأدوات إنشاء واجهة المستخدم) توفير الوقت الكافي للمؤلفين]( https://www.w3.org/TR/ATAG20/#gl_a32)
-   [الجزء ب. دعم إنتاج محتوى قابل للوصول]( https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}
 
#### قصص ذات علاقة بالوقت الكافي
{:.no_toc}
 
{% include excol.html type="middle" %}

-   [أليكس, مراسل مصاب بالضغط النفسي المتكرر](/people-use-web/user-stories/#reporter)
-   [برييتي, طالب في المرحلة الإعدادية يعاني من اضطراب فرط الحركة وتشتت الانتباه وعسر القراءة](/people-use-web/user-stories/#classroomstudent)
-   [ين, متقاعد مع ضعف البصر ورعاش اليد وفقدان خفيف للذاكرة على المدى القصير](/people-use-web/user-stories/#retiree)
-   [لويس ، مساعد سوبر ماركت مصاب بمتلازمة داون](/people-use-web/user-stories/#supermarketassistant)
-   [قاسم,مراهق أصم و كفيف](/people-use-web/user-stories/#teenager)
 
{% include excol.html type="end" %}
 
###  المحتوى لا يسبب أي  نوبات وردود فعل جسدية{#safe}
 
يمكن أن يتسبب المحتوى الذي يومض بمعدلات أو أنماط معينة في ردات فعل حساسة للضوء، و نوبات. يتم تجنب المحتوى الوامض كليًا أو استخدامه فقط بطريقة لا تسبب مخاطر معروفة. كما يمكن أن تسبب الرسوم المتحركة والمحتوى المتحرك إزعاجًا وردود أفعال جسدية.
 
بعض الأمثلة لتجنب التسبب في نوبات او ردات فعل جسدية:

-   لا تقم بتضمين محتوى يومض بمعدلات وأنماط معينة
-   تحذير المستخدمين قبل عرض المحتوى الوامض، وتقديم البدائل
-   توفير آليات لإيقاف تشغيل الرسوم المتحركة ما لم تكن ضرورية

{% include excol.html type="start" %}
 
#### متطلبات الوصول المتعلقة بالنوبات (روابط للوصف التقني)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
-   [إرشادات 3.2 - النوبات]( https://www.w3.org/WAI/WCAG21/quickref/#seizures-and-physical-reactions)
 
**UAAG**
 
-   [إرشادات 9.2 - الومضات]( https://www.w3.org/TR/UAAG20/#gl-prevent-flash)
 
**ATAG**

-   [المبدأ أ.1: أدوات إنشاء واجهة المستخدم تتبع إرشادات وصول قابلة للتطبيق]( https://www.w3.org/TR/ATAG20/#principle_a1)
-   [إرشادات أ.3.3: (لأدوات إنشاء واجهة المستخدم) مساعدة المؤلفين بتجنب الومضات التي قد تسبب نوبات]( https://www.w3.org/TR/ATAG20/#gl_a33)
-   [الجزء ب. دعم إنتاج محتوى قابل للوصول]( https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}
 
### إمكانية المستخدم  للتنقل بسهولة ، العثور على المحتويات ، وتحديد أماكنهم {#navigable}
 
المحتوى المنظم بشكل جيد يمكّن المستخدمين من استخدام الموقع والتنقل فيه على نحو فعال:

-   تحتوي الصفحات على عناوين واضحة ويتم تنظيمها باستخدام عناوين وصفية للأقسام
-   يجب أن يكون هناك أكثر من طريقة للعثور على الصفحات ذات الصلة ضمن مجموعة من صفحات الويب
-   يستطيع المستخدمين معرفة رقم الصفحة التي يتصفحونها حاليا ضمن نطاق محدد من الصفحات
-   توفر طرق لتجاوز مجموعات المحتوى التي تتكرر على صفحات متعددة
-   يكون تركيز لوحة المفاتيح مرئيًا، ويتبع ترتيب التركيز تسلسلًا ذا مغزى
-   اي روابط يتم عرضها يكون الهدف منها وما تؤدي إليه واضحًا

يساعد تلبية هذه المتطلبات الأشخاص على التنقل عبر صفحات الويب بطرق مختلفة، اعتمادًا على احتياجاتهم وتفضيلاتهم الخاصة. على سبيل المثال؛ بينما يعتمد بعض الأشخاص على هياكل التنقل الهرمية مثل أشرطة القوائم للعثور على صفحات ويب معينة، يعتمد الآخرون على وظائف البحث على مواقع الويب بدلاً من ذلك.  بعض الأشخاص يرون المحتوى بينما البعض الآخرون قد يسمعونه أو يرونه ويسمعونه في نفس الوقت. قد يستخدم بعض الأشخاص المحتوى باستخدام الفأرة أو لوحة المفاتيح فقط ، بينما الآخرون قد يستخدمون كليهما. 

{% include excol.html type="start" %}
 
#### متطلبات الوصول المتعلقة بالتنقل (روابط للوصف التقني)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**

 -   [إرشادات4.2: قابلية التنقل]( https://www.w3.org/WAI/WCAG21/quickref/#navigable)
 
**UAAG**
 
-   [إرشادات 2.2: التنقل المتسلسل]( https://www.w3.org/TR/UAAG20/#gl-sequential-navigation)
-   [إرشادات 3.2: التنقل والتفعيل المباشر]( https://www.w3.org/TR/UAAG20/#gl-direct-navigation-and-activation)
-   [إرشادات 4.2: البحث النصي]( https://www.w3.org/TR/UAAG20/#gl-search-text)
-   [إرشادات 5.2: التنقل الهيكلي]( https://www.w3.org/TR/UAAG20/#gl-nav-structure)
-   [إرشادات 7.2: الضوابط الرسومية]( https://www.w3.org/TR/UAAG20/#gl-configure-controls)

**ATAG**
 

-    [المبدأ أ.1: أدوات إنشاء واجهة المستخدم تتبع إرشادات وصول قابلة للتطبيق]( https://www.w3.org/TR/ATAG20/#principle_a1)
-    [المبدأ أ.1.2: (أدوات إنشاء واجهة المستخدم)  القيام بإتاحة المحتوى البديل للمؤلفين]( https://www.w3.org/TR/ATAG20/#gl_a21)
-    [المبدأ أ.2.2: (أدوات إنشاء واجهة المستخدم) التأكد من إمكانية تحديد طريقة عرض التحرير بطريقة برمجية]( https://www.w3.org/TR/ATAG20/#gl_a22)
-    [المبدأ أ.7.3: (أدوات إنشاء واجهة المستخدم) التأكد من أن طرق العرض يمكن الوصول إليها مثل وكلاء الويب المستخدمين]( https://www.w3.org/TR/ATAG20/#gl_b37)
-    [الجزء ب. دعم إنتاج محتوى قابل للوصول]( https://www.w3.org/TR/ATAG20/#part_b)

-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure that editing-view presentation can be programmatically determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.3.4: (For the authoring tool user interface) Enhance navigation and editing via content structure](https://www.w3.org/TR/ATAG20/#gl_a34)
-   [Guideline A.3.5: (For the authoring tool user interface) Provide text search of the content](https://www.w3.org/TR/ATAG20/#gl_a35)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)
 
{% include excol.html type="end" %}{% include excol.html type="start" %}
 
#### Stories related to navigation
{:.no_toc}
 
{% include excol.html type="middle" %}
 
-   [Alex, reporter with repetitive stress injury](/people-use-web/user-stories/#reporter)
-   [Ilya, senior staff member who is blind](/people-use-web/user-stories/#accountant)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia](/people-use-web/user-stories/#classroomstudent)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss](/people-use-web/user-stories/#retiree)
-   [Luis, supermarket assistant with Down syndrome](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, teenager who is deaf and blind](/people-use-web/user-stories/#teenager)
 
{% include excol.html type="end" %}
 
### Users can use different input modalities beyond keyboard {#modalities}
 
Input modalities beyond keyboard, such as touch activation, voice recognition (speech input), and gestures make content easier to use for many people. Yet not everyone can use each of these input modalities, and to the same degree. Particular design considerations maximize the benefit of these input modalities. This includes:
 
-   Gestures that require dexterity or fine movement have alternatives that do not require high dexterity
-   Components are designed to avoid accidental activation, for example by providing undo functionality
-   Lables presented to users match corresponding object names in the code, to support activation by voice
-   Functionality that is activated by movement can also be activated through user interface components
-   Buttons, links, and other active components are large enough to make them easier to activate by touch
 
Meeting this requirement makes the content easier to use for many people with a wide range of abilities using a wide range of devices. This includes content used on mobile phones, tablet computers, and self-service terminals such as ticketing machines.
 
{% include excol.html type="start" id="" %}
 
#### Accessibility requirements related to input modalities (links to technical specification)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
-   [Guideline 2.5 - Input Modalities](https://www.w3.org/WAI/WCAG21/quickref/#input-modalities)
 
{% include excol.html type="end" %}{% include excol.html type="start" id="" %}
 
#### Stories related to input modalities
{:.no_toc}
 
{% include excol.html type="middle" %}
 
-   [Alex, reporter with repetitive stress injury](/people-use-web/user-stories/#reporter)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss](/people-use-web/user-stories/#retiree)
-   [Luis, supermarket assistant with Down syndrome](/people-use-web/user-stories/#supermarketassistant)
 
{% include excol.html type="end" %}
 
## Understandable information and user interface {#understandable}
 
### Text is readable and understandable {#readable}
 
Content authors need to ensure that text content is readable and understandable to the broadest audience possible, including when it is read aloud by text-to-speech. Such content includes:
 
-   Identifying the primary language of a web page, such as Arabic, Dutch, or Korean
-   Identifying the language of text passages, phrases, or other parts of a web page
-   Providing definitions for any unusual words, phrases, idioms, and abbreviations
-   Using the clearest and simplest language possible, or providing simplified versions
 
Meeting this requirement helps software, including assistive technology, to process text content correctly. For instance, this requirement helps software to read the content aloud, to generate page summaries, and to provide definitions for unusual words such as technical jargon. It also helps people who have difficulty understanding more complex sentences, phrases, and vocabulary. In particular, it helps people with different types of cognitive disabilities.
 
{% include excol.html type="start" %}
 
#### Accessibility requirements related to readability (links to technical specification)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
-   [Guideline 3.1 - Readable](https://www.w3.org/WAI/WCAG21/quickref/#readable)
 
**ATAG**
 
-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.4.2: (For the authoring tool user interface) Document the user interface, including all accessibility features](https://www.w3.org/TR/ATAG20/#gl_b42)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)
 
{% include excol.html type="end" %}{% include excol.html type="start" %}
 
#### Stories related to readability
{:.no_toc}
 
{% include excol.html type="middle" %}
 
-   [Martine, online student who is hard of hearing](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, senior staff member who is blind](/people-use-web/user-stories/#accountant)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia](/people-use-web/user-stories/#classroomstudent)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss](/people-use-web/user-stories/#retiree)
-   [Luis, supermarket assistant with Down syndrome](/people-use-web/user-stories/#supermarketassistant)
 
{% include excol.html type="end" %}
 
### Content appears and operates in predictable ways {#predictable}
 
Many people rely on predictable user interfaces and are disoriented or distracted by inconsistent appearance or behavior. Examples of making content more predictable include:
 
-   Navigation mechanisms that are repeated on multiple pages appear in the same place each time
-   User interface components that are repeated on web pages have the same labels each time
-   Significant changes on a web page do not happen without the consent of the user
 
Meeting this requirement helps people to quickly learn the functionality and navigation mechanisms provided on a website, and to operate them according to their specific needs and preferences. For instance, some people assign personalized shortcut keys to functions they frequently use to enhance keyboard navigation. Others memorize the steps to reach certain pages or to complete processes on a website. Both rely on predictable and consistent functionality.
 
{% include excol.html type="start" %}
 
#### Accessibility requirements related to predictability (links to technical specification)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
-   [Guideline 3.2 - Predictable](https://www.w3.org/WAI/WCAG21/quickref/#predictable)
 
**UAAG**
 
-   [Guideline 3.3 - Predictable](https://www.w3.org/TR/UAAG20/#gl-predictable-operation)
 
**ATAG**
 
-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure that editing-view presentation can be programmatically determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.4.2: (For the authoring tool user interface) Document the user interface, including all accessibility features](https://www.w3.org/TR/ATAG20/#gl_b42)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)
 
{% include excol.html type="end" %}{% include excol.html type="start" %}
 
#### Stories related to predictability
{:.no_toc}
 
{% include excol.html type="middle" %}
 
-   [Alex, reporter with repetitive stress injury](/people-use-web/user-stories/#reporter)
-   [Ilya, senior staff member who is blind](/people-use-web/user-stories/#accountant)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia](/people-use-web/user-stories/#classroomstudent)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss](/people-use-web/user-stories/#retiree)
-   [Luis, supermarket assistant with Down syndrome](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, teenager who is deaf and blind](/people-use-web/user-stories/#teenager)
 
{% include excol.html type="end" %}
 
### Users are helped to avoid and correct mistakes {#tolerant}
 
Forms and other interaction can be confusing or difficult to use for many people, and, as a result, they may be more likely to make mistakes. Examples of helping users to avoid and correct mistakes include:
 
-   Descriptive instructions, error messages, and suggestions for correction
-   Context-sensitive help for more complex functionality and interaction
-   Opportunity to review, correct, or reverse submissions if necessary
 
Meeting this requirement helps people who do not see or hear the content, and may not recognize implicit relationships, sequences, and other cues. It also helps people who do not understand the functionality, are disoriented or confused, forget, or make mistakes using forms and interaction for any other reason.
 
{% include excol.html type="start" %}
 
#### Accessibility requirements related to input assistance (links to technical specification)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
-   [Guideline 3.3 - Input assistance](https://www.w3.org/WAI/WCAG21/quickref/#input-assistance)
 
**UAAG**
 
-   [Guideline 3.1 - Mistakes](https://www.w3.org/TR/UAAG20/#gl-avoid-mistakes)
 
**ATAG**
 
-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure that editing-view presentation can be programmatically determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.4.1: (For the authoring tool user interface) Help authors avoid and correct mistakes](https://www.w3.org/TR/ATAG20/#gl_b41)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)
 
{% include excol.html type="end" %}{% include excol.html type="start" %}
 
#### Stories related to input assistance
{:.no_toc}
 
{% include excol.html type="middle" %}
 
-   [Lee, online shopper with color blindness](/people-use-web/user-stories/#shopper)
-   [Alex, reporter with repetitive stress injury](/people-use-web/user-stories/#reporter)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia](/people-use-web/user-stories/#classroomstudent)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss](/people-use-web/user-stories/#retiree)
-   [Luis, supermarket assistant with Down syndrome](/people-use-web/user-stories/#supermarketassistant)
 
{% include excol.html type="end" %}
 
## Robust content and reliable interpretation {#robust}
 
### Content is compatible with current and future user tools {#compatible}
 
Robust content is compatible with different browsers, assistive technologies, and other user agents. Examples of how this can be achieved include:
 
-   Ensuring markup can be reliably interpreted, for instance by ensuring it is valid
-   Providing a name, role, and value for non-standard user interface components
 
Meeting this requirement helps maximize compatibility with current and future user agents, including assistive technologies. In particular, it enables assistive technologies to process the content reliably, and to present or to operate it in different ways. This includes non-standard (scripted) buttons, input fields, and other controls.
 
{% include excol.html type="start" %}
 
#### Accessibility requirements related to compatibility (links to technical specification)
{:.no_toc}
 
{% include excol.html type="middle" %}
 
**WCAG**
 
-   [Guideline 4.1 - Compatible](https://www.w3.org/WAI/WCAG21/quickref/#compatible)
 
**UAAG**
 
-   [Guideline 2.6 - Preference settings](https://www.w3.org/TR/UAAG20/#gl-store-prefs)
-   [Guideline 4.1 - Assistive technology](https://www.w3.org/TR/UAAG20/#gl-AT-access)
-   [Guideline 5.1 - Follow specifications](https://www.w3.org/TR/UAAG20/#gl-obs-env-conventions)
 
**ATAG**
 
-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)
 
{% include excol.html type="end" %}{% include excol.html type="start" %}
 
#### Stories related to compatibility
{:.no_toc}
 
{% include excol.html type="middle" %}
 
-   [Lee, online shopper with color blindness](/people-use-web/user-stories/#shopper)
-   [Alex, reporter with repetitive stress injury](/people-use-web/user-stories/#reporter)
-   [Ilya, senior staff member who is blind](/people-use-web/user-stories/#accountant)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia](/people-use-web/user-stories/#classroomstudent)
-   [Luis, supermarket assistant with Down syndrome](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, teenager who is deaf and blind](/people-use-web/user-stories/#teenager)
 
{% include excol.html type="end" %}
 
{% include excol.html type="all" %}
 

