---
sectionid: sharedTextRendition
title: "Text Rendition"
version: "v4"
---

Sometimes, it is desirable to capture the typographical qualities of a word or phrase without assigning it a special meaning. For this purpose, MEI offers the {% include link elem="rend" %} element, similar to TEI's *hi* element. Using CSS-like values, its **@rend** attribute can be used to specify many typographic features, such as font style, font variants, and relative font size and weight. In addition, text decoration, direction, and enclosing ‘boxes’ may be captured. While **@rend** is used to record relative font size and weight, absolute values for these qualities (measured in printer's points) should be specified using the **@fontsize** and **@fontweight** attributes. In addition to commonly found typographical qualities, MEI provides the **@altrend** attribute for the capture of additional, user-defined rendition information.

{% include desc elem="rend" %}
{% include desc atts="att.textRendition/rend att.textRendition/altrend att.typography/fontname att.typography/fontsize att.typography/fontstyle att.typography/fontweight att.horizontalAlign/halign att.verticalAlign/valign" %}
