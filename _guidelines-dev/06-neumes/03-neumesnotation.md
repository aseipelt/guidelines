---
sectionid: neumesNotation
title: "Neume Notation"
version: "dev"
---

Most neume notation is used to set music to an existing text. The syllable is the fundamental unit of structure, with the neumes themselves serving as a means of "sonifying" the text. A syllable may be expressed via one or more neumes, with the particular neume shape chosen depending on the pitch contour that is being employed and the desired interpretation. For example, two pitches in rising succession might be encoded as a "podatus" (sometimes also called a "pes"), or it might be encoded as two separate punctums, depending on whether it should be sung smoothly connected or with a slight amount of space between the notes.

There are a limited number of possiblities for the most popular musical contours. In general, groups of two to four notes are given unique names, assigned depending on their contour. A "clivis" would be two joined descending notes, while a "podatus" is two joined ascending notes. Table 1 shows most of the named neume shapes. Neume groups of more than four notes are simply called "compound" neumes.

{% include figure img="modules/neumes/parrish_neumes.png" caption="Table 1. Variant neume notation. (From Parrish, \"The notation of medieval music,\" 6)" %}

As shown in Table 1, it is possible to have many different styles of neume shapes, derived from local practices of regional groups. In general, these styles are all interpreted in a similar fashion; however, there is evidence that the performance practice of some styles of neume notation differed with regard to rhythm and cadence. This version of the MEI neumes module does not attempt to encode any rhythmic information present in the neume notation. While it may be possible to encode rhythmic values on {% include link elem="note" %} elements, this practice is highly discouraged and, if present, should be interpreted as a modern transcription not present in the original sources.

Neume notation existed before the invention of the staff. Staffless neume notation ("adiastemtic", "cheironomic" or "in campo aperto") existed primarily as a mnemonic device, reminding performers of the contour of the melody but lacking any absolute pitch information. These neumes were written above the text. With the invention of the staff lines and the clef, "heightened" or "diastematic" neume notation could be used to provide exact interval information. In some cases the staff lines are not actually drawn on the page, but their position relative to an imaginary line and initial clef is consistent.

The {% include link elem="syllable" %} element is used as the primary organizational element for neume notation within a {% include link elem="layer" %} element. Within {% include link elem="syllable" %}, the {% include link elem="syl" %} element defined in the MEI.shared module is used for encoding the textual content, while the {% include link elem="neume" %} and {% include link elem="nc" %} elements are used to encode the neumes themeselves. Within these neume module elements, other standard MEI mechanisms are available to accommodate, for example, editorial or critical markup.
