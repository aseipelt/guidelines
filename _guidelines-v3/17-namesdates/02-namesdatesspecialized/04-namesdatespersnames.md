---
sectionid: namesdatesPersNames
title: "Personal Names"
version: "v3"
---

{% include desc elem="persName" %} 

Personal names within an MEI document may simply be marked with the {% include link elem="persName" %} element containing a proper noun or proper noun phrase referring to an individual. Personal names, however, often consist of several components, like forenames and surnames, but also other components, such as inherited or life-time titles of nobility, honorific or academic prefixes, military ranks or traditional descriptive phrases. These components may be marked using {% include link elem="name" %} sub-elements, the function of which may be indicated using the **@type** attribute. In this case, **@type** attribute may take the following values:

{:.gloss}
**'forename'**: contains a forename, given or baptismal name.

{:.gloss}
**'surname'**: a family (inherited) name, as opposed to a given, baptismal, or nick name.

{:.gloss}
**'rolename'**: contains a name component which indicates that the referent has a particular role or position in society, such as an official title or rank.

{:.gloss}
**'addname' (additional name)**: contains an additional name component, such as a nickname, epithet, or alias, or any other descriptive phrase used within a personal name.

{:.gloss}
**'namelink' (name link)**: contains a connecting phrase or link used within a name but not regarded as part of it, such as van der or of.

{:.gloss}
**'genname' (generational name)**: contains a name component used to distinguish otherwise similar names on the basis of the relative ages or generations of the persons named.

{% include mei example="namesDates/namesDates-sample289.xml" valid="false" %}

The {% include link elem="persName" %} element is often enclosed in the {% include link elem="respStmt" %} element which may occur within {% include link elem="titleStmt" %}, {% include link elem="pubStmt" %}, {% include link elem="seriesStmt" %} and {% include link elem="change" %}. This usage of the {% include link elem="persName" %} element typical looks like this:

{% include mei example="namesDates/namesDates-sample290.xml" valid="false" %}

Apart from the composer or originator of a musical work, however, there could be many other persons involved in the genesis of a musical work, such as librettists, lyricists, arrangers, editors, transcribers, printers, publishers, etc. The special roles of these persons may be marked using the **@role** attribute on {% include link elem="persName" %}. For example:

{% include mei example="namesDates/namesDates-sample291.xml" valid="true" %}
{% include mei example="namesDates/namesDates-sample292.xml" valid="true" %}

The [Marc code list for relators](http://www.loc.gov/marc/relators/relaterm.html){:.link_ref} offers a variety of controlled terms that may serve as values for this use of **@role**.

For names in the metadata header, the use of a controlled list, such as the Gemeinsame Normdatei (GND) or the Library of Congress Name Authorities, is recommended.  The name and web-accessible location of the list may be recorded using the **@authority** and **@authURI** attributes, respectively. To record a value which serves as a primary key in an external database, the **@dbkey** attribute may be used.

For maximal machine-processability, these three attributes may be used in combination. For example:

{% include mei example="namesDates/namesDates-sample293.xml" valid="true" %}
