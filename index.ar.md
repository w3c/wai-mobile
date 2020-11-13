---
# Translation info https://www.w3.org/wiki/WAI/Translation_Instructions

title: "Mobile Accessibility at W3C"
nav_title: "Mobile Accessibility at W3C"

description: 

lang: ar
last_updated: 2020-10-14
permalink: /standards-guidelines/mobile/ar

github:
  repository: w3c/wai-mobile
  path: index.ar.md

translators: 
- name: "Your Name"
# contributors:
# - name: "Other Name"

feedbackmail: wai@w3.org
footer: >
  <p><strong>Date:</strong> Updated 14 October 2020. First published January 2008.</p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributor: <a href="http://www.w3.org/People/Brewer/">Judy Brewer</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>).</p>
ref: /standards-guidelines/mobile/
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

-   **Mobile accessibility is covered in existing W3C WAI accessibility standards/guidelines**. There are not separate guidelines for mobile accessibility.
-   W3C is developing updated requirements and more specific guidance on mobile accessibility.
-   **WAI's [Mobile Accessibility Task Force](https://www.w3.org/WAI/GL/mobile-a11y-tf/) work includes:**
    -   [Mobile Accessibility: How WCAG 2.0 and Other W3C/WAI Guidelines Apply to Mobile](http://www.w3.org/TR/mobile-accessibility-mapping/)
    -   WCAG 2 Success Criteria and Techniques
    -   Integrating mobile accessibility in future W3C standards

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## More than "Mobile" {#intro}
## اكثر من "أجهزة محمولة"

تشير "إتاحة المتحتوى للأجهزة" المحمولة الى جعل المواقع الاكترونية و التطبيقات اكثر سهولة للأشخاص ذوى الإعاقة عند استخدامهم للأجهزة المحمولة و الأجهزة الأخرى. يتناول عمل WAI في هذا المجال مشاكل إمكانية الوصول للأشخاص الذين يستخدمون مجموعة واسعة من الأجهزة للتفاعل مع المواقع الالكترونية على سبيل المثال:

-   الهواتف النقالة و الأجهزة اللوحية
-   أجهزة التلفزيون
-   الأجهزة القابلة للارتداء كالساعات الذكية
-   أجهزة في لوحات القيادة للسيارات و مقاعد الطائرات
-   الأجهزة المنزلية
-   "انترنت الأشياء" (IOT)

يتناول مجموعة واسعة من المشاكل:

-   الشاشات اللمس
-   الشاشة الصغيرة
-   طرق ادخال مختلفة بما في ذلك النطق و اللمس الثلاثي الابعاد الذي يتم تمكينه بواسطة استشعارات الضغط
-   استخدام الجهاز في ظروف متعددة، مثل الضوء الشمس الساطع
-   و اكثر

## يطرح w3c WAI  إتاحة المتحوى عبر الأجهزة المحمولة {#covered}
** تتناول إتاحة المحتوى الخاصة بـ WAI إمكانية الوصول عبر الأجهزة المحمولة:**

-   تغطي إرشادات إمكانية الوصول **لمحتوى الموقع الالكتروني** (WCAG) صفحات الموقع الإلكتروني و البرامج تحت الويب، بما في ذلك المحتوى المستخدم على الأجهزة المحمولة.
	-	لمعرفة كيفية تطبيق WCAG 2.0 على محتوى الويب في الأجهزة المحمولة تطبيقات الويب للهواتف، التطبيقات الاصلية، راجع [إتاحة المحتوى للأجهزة النقالة: كيفية تطبيق إرشادات WCAG 2.0 و إرشادات W3C/WAI و إرشادات أخرى على الأجهزة المحمولة]( http://www.w3.org/TR/mobile-accessibility-mapping/).
	-	يعد WCAG2ICT من الموارد العامة التي تشتمل أيضا على تطبيقات الأجهزة المحمولة: [WCAG2ICT: تطبيق WCAG 2.0  على تقنيات المعلومات و الاتصالات بخلاف الويب]( http://www.w3.org/TR/wcag2ict/)
	-	تم نشر WCAG 2.1 في يونيو 2018 الذي يتضمن المتطلبات الجديدة لـ ("معايير النجاح") تتناول إتاحة المحتوى عبر الأجهزة المحمولة والذي تم طرحه في [[ماهو جديد في WCAG2.1]]( /standards-guidelines/wcag/new-in-21/).
-	تغطي إرشادات الوصول الخاصة بوكيل المستخدم (UAAG) متصفح الويب و غيره من **وكلاء مستخدمين** بما في ذلك متصفحات الهاتف.
	-	للحصول على أمثلة حول كيفية إفادة المتصفح الويب للأجهزة المحمولة الذي تتبع UAAG للأشخاص ذوى الاعاقة، راجع  [أمثلة إمكانية الوصول عبر الأجهزة المحمولة من UAAG]( http://www.w3.org/TR/IMPLEMENTING-UAAG20/mobile)
	-	لمن يرغب في ان يستكشف اكثر في هذا الموضوع، يرجى مراجعة [تطبيق UAAG  على الهواتف المحمولة]( http://www.w3.org/WAI/UA/work/wiki/Applying_UAAG_to_Mobile_Phones)
-	يغطي دليل الوصول الى **أدوات التطوير** (ATAG) البرامج المستخدمة  لإنشاء المواقع الالكترونية و التطبيقات، في ما ذلك ما يختص بالهواتف النقالة.
-	تحدد **WAI-ARIA (تطبيقات الانترنت الغنية التي يمكن الوصول اليها)** طرقا لتسهيل الوصول الى المحتوى الويب، لاسيما المحتوى الديمناميكي و عناصر التحكم المتقدمة في واجهة المستخدم و تنطبق على تطبيقات الويب و الوصول الى المواقع الالكترونية باستخدام الأجهزة المحمولة.

<!-- WAI's Education and Outreach Working Group (EOWG) is developing a **Mobile Accessibility Introduction** with guidance for designers and developers. We expect it to be completed in late 2019. -->

**يتناول عمل W3C إمكانية الوصول للاجهزة المحمولة.** يضمن WAI  ان تقنيات الأساسية لـ W3C تدعم إتاحة المحتوى، بما في ذلك شبكة الويب للأجهزة المحمولة. تتم مراجعة اعمال w3c  للوصول الى المحتوى من قبل مجموعة عمل ([APA]( https://www.w3.org/WAI/APA/)).

يتضمن عمل W3C  للأجهزة النقالة على [أفضل ممارسات للتطبيقات الويب للهاتف]( http://www.w3.org/TR/mwabp/) و [افضل ممارسات الويب للهاتف]( http://www.w3.org/TR/mobile-bp/). لمعرفة موجز التقنيات التي تم تطويرها من قبل W3C و التي تزيد من إمكانيات تطبيقات الويب و كيفية تطبيقها للهواتف النقالة خاصة، يرجى مراجعة [معايير تطبيقات الويب على الأجهزة المحمولة]( http://www.w3.org/Mobile/mobile-web-app-state/).

##  إحصل على التحديثات {#updates}

اذا كنت ترغب بالحصول على إشعار لإعمال W3C WAI المستقبلية الخاصة بإمكانية الوصول للهواتف النقالة، يرجى مراجعة [إحصل على أخبار WAI ]( /news/subscribe/).

## شارك {#involved}

المعلومات العامة متاحة في [المشاركة في WAI ]( /about/participating/).

تتم معظم اعمال WAI المتعلقة بإتاحة المحتوى عبر أجهزة النقالة من خلال [فريق عمل إتاحة المحتوى عبر الأجهزة النقالة]( https://www.w3.org/WAI/GL/mobile-a11y-tf/). اذا كنت ترغب في المشاركة في عمل WAI بشأن اتاحة المحتوى عبر الأجهزة المحمولة – يرجى ارسال بريد الكتروني يحتوي على معلومات حول اهتماماتك و الوقت المتاح لديك الى منسقي فريق عمل [كيم باتش و كايثي والبين]( mailto:kathy@interactiveaccessibility.com,Kim@redstartsystems.com?cc=wai@w3.org,shadi@w3.org&subject=Mobile%20Accessibility%20Task%20Force%20Enquiry) و (wai@w3.org)

## حول W3C و WAI {#about}

اتحاد شبكة الويب العالمية (W3C) هو اتحاد دولي حيث تعمل المنظمات الأعضاء و الموظفون و الجمهور معا لتطوير معايير الويب و التي تتابع مهمتها بشكل أساسي من خلال إنشاء معايير الويب و المبادئ التوجيهية المصممة لضمان نمو طويل المدى للويب. لمعرفة المزيد راجع [حول W3C ]( http://www.w3.org/Consortium/).

تجمع مبادرة إتاحة المحتوى إلى الويب (WAI) من W3C الأفراد و المنظمات من جميع أنحاء العالم لتطوير استراتيجيات و إرشادات و موارد للمساعدة في جعل الويب في متناول الأشخاص ذوى الإعاقة. لمعرفة المزيد يرجى مراجعة [موقع WAI]( http://www.w3.org/WAI/)
