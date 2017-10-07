---
sectionid: sharedDocumentElements
title: "Document Elements"
---



The following elements are available for the representation of the outermost structure
of
an MEI document:



{% include specDesc.html key="mei" atts="" %}
{% include specDesc.html key="mei" atts="meiversion" %}
{% include specDesc.html key="meiCorpus" atts="" %}
{% include specDesc.html key="meiHead" atts="" %}
{% include specDesc.html key="music" atts="" %}



A typical MEI document contains an [mei](/v3/elements/mei.html){:.link_odd_elementSpec} element, which in turn
contains metadata, represented by an [meiHead](/v3/elements/meiHead.html){:.link_odd_elementSpec} element, and the musical
text itself, represented by a [music](/v3/elements/music.html){:.link_odd_elementSpec} element. The [meiHead](/v3/elements/meiHead.html){:.link_odd_elementSpec} element, formally declared in the MEI.header module, is described in chapter
<a class="link_ptr" title="The MEI Header" href="/v3/guidelines/header.html">2 The MEI Header</a>.

Other variations on this basic form are also available for the representation of a:


- collection of related MEI-encoded texts, each with its own metadata, known as a
corpus
- document that contain only metadata, known as an independent or stand-alone
header
- music notation markup without metadata, typically intended to be embedded within
another kind of markup, such as TEI

Further information regarding the organization and encoding of music corpora is given
in
chapter 
<a class="link_ptr" title="Musical Corpora" href="/v3/guidelines/corpus.html">9 Musical Corpora</a>. Stand-alone headers are more fully described in chapter

<a class="link_ptr" title="Independent Headers" href="/v3/guidelines/header.html#headerIndependentHeader">2.6 Independent Headers</a>.

Inclusion of MEI encodings (partial or complete) inside Text Encoding Initiative (TEI)
documents is covered in the TEI Guidelines at [http://www.tei-c.org/release/doc/tei-p5-doc/en/html/FT.html#FTNM](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/FT.html#FTNM){:.link_ref} and by the TEI
Music Special Interest Group at [http://www.tei-c.org/SIG/Music/twm/index.html](http://www.tei-c.org/SIG/Music/twm/index.html){:.link_ref}.
