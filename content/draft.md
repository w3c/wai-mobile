---
title: "testing for changelogs"
lang: en
layout: default

permalink: /standards-guidelines/mobile/draft/
ref: /standards-guidelines/mobile/draft/
github:
   repository: w3c/wai-mobile
   path: content/draft.md

feedbackmail: wai@w3.org
footer: >
   <p>Thanks to Tolu Adegbite for updating this changelog in May 2021.</p>
---

_This changelog includes some Markdown and HTML syntax to facilitate updating translations._


## Change 1 - cirrectly not pulling heading, but missing double brackets
* add this
```
### Pronunciation
[```[Pronunciation Overview]```](/pronunciation/) &mdash; Pronunciation is about screen readers and other text-to-speech (TTS) synthesis pronouncing content properly.
```

## Change 1.1 - single escape inbetween brackets
* add this
`### Pronunciation`
`[``[Pronunciation Overview]``](/pronunciation/) &mdash; Pronunciation is about screen readers and other text-to-speech (TTS) synthesis pronouncing content properly.`

## Change 2 - single
* add this:
`### W3C Accessibility Guidelines (WCAG) 3 Working Draft {#wcag3}`
<br>`WCAG 3 is an early draft that is intended to become a W3C Standard. WCAG 3 applies to web content, apps, tools, publishing, and emerging technologie on the web.`
<br>`WCAG 3 info:`
<br>`- [[WCAG 3 Introduction]](/standards-guidelines/wcag/wcag3-intro/)`

## Change 2.2 - 3
* add this:
```
### W3C Accessibility Guidelines (WCAG) 3 Working Draft {#wcag3}
WCAG 3 is an early draft that is intended to become a W3C Standard. WCAG 3 applies to web content, apps, tools, publishing, and emerging technologies on the web.
WCAG 3 info:
- [```[WCAG 3 Introduction]```](/standards-guidelines/wcag/wcag3-intro/)
```

## Change 2.2 - adds 8 spaces in front
* add this:
```
        ### W3C Accessibility Guidelines (WCAG) 3 Working Draft {#wcag3}
        WCAG 3 is an early draft that is intended to become a W3C Standard. WCAG 3 applies to web content, apps, tools, publishing, and emerging technologies on the web.
WCAG 3 info:
        - [[WCAG 3 Introduction]](/standards-guidelines/wcag/wcag3-intro/)
```

## Change @@
* Change xyz to:
```
- [[WCAG 2 Translations]](/standards-guidelines/wcag/translations/)
- [WCAG 2.0 Standard](https://www.w3.org/TR/WCAG20/)
- [WCAG 2.1 Standard](https://www.w3.org/TR/WCAG21/), [[What’s New in WCAG 2.1]](/standards-guidelines/wcag/new-in-21/)
- [[What's New in WCAG 2.2 Working Draft]](/standards-guidelines/wcag/new-in-22/)
```

## Change @@
* Change xyz to:
<br>`- [`[WCAG 2 Translations]`](/standards-guidelines/wcag/translations/)`
<br>`- [WCAG 2.0 Standard](https://www.w3.org/TR/WCAG20/)`
<br>`- [WCAG 2.1 Standard](https://www.w3.org/TR/WCAG21/), [[What’s New in WCAG 2.1]](/standards-guidelines/wcag/new-in-21/)`
<br>`- [``[What's New in WCAG 2.2 Working Draft]``](/standards-guidelines/wcag/new-in-22/)`

