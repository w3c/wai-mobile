---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "W3C의 모바일 접근성"
nav_title: "W3C의 모바일 접근성"

description: 

lang: ko
last_updated: 2019-09-23

translators: 
- name: "Yong Ui Lee"
  link: "https://twitter.com/yongui9"
contributors:
- name: "Jun Ho Lee"

permalink: /standards-guidelines/mobile/

github:
  repository: w3c/wai-mobile
  path: index.ko.md

feedbackmail: wai@w3.org
footer: >
  <p><strong>날짜:</strong> 2019년 3월 1일 업데이트됨. 첫 발행일은 2008년 1월입니다.</p>
  <p><strong>편집자:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. 기여자: <a href="http://www.w3.org/People/Brewer/">Judy Brewer</a>.</p>
  <p>교육과 활동관련 실무 그룹인 (<a href="http://www.w3.org/WAI/EO/">EOWG</a>)의 지원을 받아 제작되었습니다.</p>
ref: /standards-guidelines/mobile/
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

-   **모바일 접근성은 현재의 W3C WAI 접근성 표준/지침으로 지원가능합니다.**. 모바일 접근성만을 위한 별도의 지침은 없습니다.
-   W3C는 모바일 접근성에 더 초점을 맞춘 지침과 업데이트된 필요조건 관련 작업을 하고 있습니다.
-   **WAI의 [모바일 접근성 TF](https://www.w3.org/WAI/GL/mobile-a11y-tf/)의 작업 내용:**
    -   [모바일 접근성 : WCAG 2.0와 다른 W3C/WAI 지침들을 모바일에 적용하는 방법](http://www.w3.org/TR/mobile-accessibility-mapping/)
    -   WCAG 2.1 성공 기준과 기술
    -   미래 W3C 표준에 모바일 접근성 통합하기

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

## "모바일" 이상으로 {#intro}

"모바일 접근성"은 장애가 있는 사용자가 모바일 폰이나 다른 장치들에서 더 접근 가능한 어플리케이션이나 웹 사이트를 만드는 것을 가리킵니다. 이 영역에서 WAI의 일은 웹과 상호작용하기 위해 다양한 장치를 사용하는 사람들의 접근성 문제를 다루는 것입니다. 다음의 장치를 포함합니다. :

-   모바일 폰이나 태블릿
-   디지털 TV
-   스마트워치 같은 웨어러블 기기
-   자동차 계기판이나 비행기 좌석 뒷편의 장치
-   가전제품 장치
-   다른 "IoT(사물 인터넷)"

다양한 이슈들을 다룹니다. :

-   터치스크린
-   작은 스크린 크기
-   압력 센서로 동작하는 3D 터치와 음성과 같은 다양한 입력 장치
-   밝은 햇빛 아래 같은 다양한 상황속 기기 사용
-   등등

## W3C WAI가 다루는 모바일 접근성 {#covered}

**WAI의 접근성 표준들은 모바일 접근성을 다룹니다.**:

-   **웹 콘텐츠** 접근성 지침 ([WCAG](/standards-guidelines/wcag/))은 모바일 기기에서 사용되는 콘텐츠를 포함한 웹 어플리케이션과 웹 페이지를 포함합니다.
    -   WCAG 2.0을 모바일 웹 콘텐츠, 모바일 웹앱, 네이티브 앱, 네이티브 앱 속 웹 콘텐츠를 사용하는 하이브리드 앱에 적용하는 방법을 배우기 위해, [모바일 접근성: WCAG 2.0와 다른 W3C/WAI 지침을 모바일에 적용하는 방법](http://www.w3.org/TR/mobile-accessibility-mapping/)을 참고하세요.
    -   모바일 앱을 포함하는 더 일반적인 정보를 얻고 싶다면 [WCAG2ICT: 웹이 아닌 정보와 통신기술에 WCAG 2.0 적용하기](http://www.w3.org/TR/wcag2ict/)를 참고하세요.
    -   2018년에 발행된 WCAG 2.1은 모바일 접근성을 다루는 새로운 필요조건("성공 기준")을 포함합니다. 이 내용은 [[WCAG 2.1의 새로운 내용 알아보기]](/standards-guidelines/wcag/new-in-21/)을 참고하세요.
-   **사용자 에이전트** 접근성 지침 ([UAAG](/standards-guidelines/uaag/))은 웹 브라우저와 모바일 브라우저를 포함한 다른 "사용자 에이전트"를 다룹니다.
    -   UAAG를 준수하는 웹 브라우저가 모바일 기기의 웹을 사용하는 장애를 가진 사용자에게 어떤 이점을 제공하는지에 대한 예시는 [UAAG에서의 웹 접근성 예시](http://www.w3.org/TR/IMPLEMENTING-UAAG20/mobile)를 참고하세요.
    -   더 많은 이슈들을 탐색하고 싶은 분들은 [모바일 폰에 UAAG 적용하기](http://www.w3.org/WAI/UA/work/wiki/Applying_UAAG_to_Mobile_Phones)를 참고하세요.
-   **저작 도구** 접근성 지침 ([ATAG](/standards-guidelines/atag/))은 모바일을 포함한 어플리케이션과 웹 페이지를 만드는 데에 사용되는 소프트웨어를 포함합니다.
-   **[WAI-ARIA](/standards-guidelines/aria/)** (접근성 리치 인터넷 어플리케이션)는 웹 콘텐츠(특히 다양한 콘테츠와 사용자 진보된 인터페이스 컨트롤)가 더 접근 가능하게 만드는 방법을 정의합니다. 웹 어플리케이션과 모바일 기기의 웹 사이트에 접근하는 데에 적용됩니다.

WAI의 교육과 활동관련 실무 그룹(EOWG)는 디자이너와 개발자를 위한 가이드와 함께 **모바일 접근성 입문**를 개발합니다. 2019년 말까지 완수할 수 있기를 기대합니다. 

**W3C addresses mobile accessibility.** WAI ensures that the core W3C technologies support accessibility, including those that are essential for the mobile web. All W3C work is reviewed for accessibility by WAI's Accessible Platform Architectures Working Group ([APA](https://www.w3.org/WAI/APA/)).

W3C work on mobile includes [Mobile Web Application Best Practices](http://www.w3.org/TR/mwabp/) and [Mobile Web Best Practices](http://www.w3.org/TR/mobile-bp/). For a summary of technologies developed in W3C that increase the capabilities of web applications and how they apply specifically to the mobile context, see [Standards for Web Applications on Mobile](http://www.w3.org/Mobile/mobile-web-app-state/).

## Get Updates {#updates}

If you would like to get notification of future work on mobile accessibility at W3C WAI, see [[Get WAI News]](/news/subscribe/).

## Get Involved {#involved}

General information is available in [[Participating in WAI]](/about/participating/).

Most of WAI's work related to mobile accessibility is through the [Mobile Accessibility Task Force](https://www.w3.org/WAI/GL/mobile-a11y-tf/). If you would like to be more involved in WAI's work on mobile accessibility, please send an e-mail with information about your interests and time availability to the Task Force facilitators [Kim Patch and Kathy Wahlbin](mailto:kathy@interactiveaccessibility.com,Kim@redstartsystems.com?cc=wai@w3.org,shadi@w3.org&subject=Mobile%20Accessibility%20Task%20Force%20Enquiry) with CC to WAI Staff (wai@w3.org).

## About W3C and WAI {#about}

The World Wide Web Consortium (W3C) is an international consortium where Member organizations, a full-time staff, and the public work together to develop Web standards. W3C primarily pursues its mission through the creation of Web standards and guidelines designed to ensure long-term growth for the Web. To learn more, see [About W3C](http://www.w3.org/Consortium/).

W3C's Web Accessibility Initiative (WAI) brings together individuals and organizations from around the world to develop strategies, guidelines, and resources to help make the Web accessible to people with disabilities. To learn more, see the [WAI website](http://www.w3.org/WAI/).
