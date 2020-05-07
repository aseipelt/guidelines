---
layout: sidebar
sidebar: s1
version: "dev""
title: "model.editionLike"
---
<div class="specPage">
   <div class="modelClassSpec">
      <h3 id="model.editionLike">model.editionLike</h3>
      <div class="specs">
         <div class="desc">Groups elements containing bibliographic edition information.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.shared</div>
         </div>
         <div class="facet containedBy" id="containedBy">
            <div class="label">Contained by</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="containedBy_compact_tab" href="#containedBy" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="class" id="containedBy_class_tab" href="#containedBy" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="containedBy_module_tab" href="#containedBy" class="displayTab">by module</a></li>
               </ul>
               <div id="containedBy_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="(bibliographic reference) – Provides a loosely-structured bibliographic citation in which the sub-components may or may not be explicitly marked."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/bibl.html">bibl</a></span>, <span class="ident element" title="(edition statement) – Container for meta-data pertaining to a particular edition of the material being described."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/editionstmt.html">editionStmt</a></span>, <span class="ident element" title="(monograph level) – Contains bibliographic elements describing an item, for example, a published book or journal, score, recording, or an unpublished manuscript."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/monogr.html">monogr</a></span>, <span class="ident element" title="Contains a transcription of the title page of a text."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/titlepage.html">titlePage</a></span></div>
               <div id="containedBy_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="model.editionLike">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.editionlike.html">model.editionLike</a></label><span class="classDesc">(MEI.shared) Groups elements containing bibliographic edition information.</span></div>
                     <div class="classContent">
                        <div class="elementDef def"><span class="ident element" title="(edition statement) – Container for meta-data pertaining to a particular edition of the material being described."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/editionstmt.html">editionStmt</a></span><span class="elementDesc desc">(edition statement) – Container for meta-data pertaining to a particular edition of
                              the
                              material being described.</span></div>
                        <div class="elementDef def"><span class="ident element" title="(monograph level) – Contains bibliographic elements describing an item, for example, a published book or journal, score, recording, or an unpublished manuscript."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/monogr.html">monogr</a></span><span class="elementDesc desc">(monograph level) – Contains bibliographic elements describing an item, for example,
                              a
                              published book or journal, score, recording, or an unpublished manuscript.</span></div>
                        <div class="classBox" title="model.biblPart">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.biblpart.html">model.biblPart</a></label><span class="classDesc">(MEI.shared) Groups elements that may appear as part of a bibliographic description.</span></div>
                           <div class="classContent">
                              <div class="elementDef def"><span class="ident element" title="(bibliographic reference) – Provides a loosely-structured bibliographic citation in which the sub-components may or may not be explicitly marked."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/bibl.html">bibl</a></span><span class="elementDesc desc">(bibliographic reference) – Provides a loosely-structured bibliographic citation in
                                    which
                                    the sub-components may or may not be explicitly marked.</span></div>
                           </div>
                        </div>
                        <div class="classBox" title="model.titlePagePart">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.titlepagepart.html">model.titlePagePart</a></label><span class="classDesc">(MEI.shared) Groups elements that may appear as part of a title page transcription.</span></div>
                           <div class="classContent">
                              <div class="elementDef def"><span class="ident element" title="Contains a transcription of the title page of a text."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/titlepage.html">titlePage</a></span><span class="elementDesc desc">Contains a transcription of the title page of a text.</span></div>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
               <div id="containedBy_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.header">
                     <div class="classHeading"><label class="classLabel">MEI.header</label><span class="classDesc">Metadata header component declarations.</span></div>
                     <div class="classContent">
                        <div class="elementRef"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/editionstmt.html">editionStmt</a><span class="elementDesc">(edition statement) – Container for meta-data pertaining to a particular edition of
                              the
                              material being described.</span></div>
                     </div>
                  </div>
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc">Component declarations that are shared between two or more modules.</span></div>
                     <div class="classContent">
                        <div class="elementRef"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/bibl.html">bibl</a><span class="elementDesc">(bibliographic reference) – Provides a loosely-structured bibliographic citation in
                              which
                              the sub-components may or may not be explicitly marked.</span></div>
                        <div class="elementRef"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/monogr.html">monogr</a><span class="elementDesc">(monograph level) – Contains bibliographic elements describing an item, for example,
                              a
                              published book or journal, score, recording, or an unpublished manuscript.</span></div>
                        <div class="elementRef"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/titlepage.html">titlePage</a><span class="elementDesc">Contains a transcription of the title page of a text.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet members" id="members">
            <div class="label">Members</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="members_compact_tab" href="#members" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="module" id="members_module_tab" href="#members" class="displayTab">by module</a></li>
               </ul>
               <div id="members_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="(edition designation) – A word or text phrase that indicates a difference in either content or form between the item being described and a related item previously issued by the same publisher/distributor (e.g. 2nd edition, version 2.0, etc.), or simultaneously issued by either the same publisher/distributor or another publisher/distributor (e.g. large print edition, British edition, etc.)."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/edition.html">edition</a></span></div>
               <div id="members_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc">Component declarations that are shared between two or more modules.</span></div>
                     <div class="classContent">
                        <div class="elementRef"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/edition.html">edition</a><span class="elementDesc">(edition designation) – A word or text phrase that indicates a difference in either
                              content or form between the item being described and a related item previously issued
                              by the
                              same publisher/distributor (e.g. 2nd edition, version 2.0, etc.), or simultaneously
                              issued by
                              either the same publisher/distributor or another publisher/distributor (e.g. large
                              print
                              edition, British edition, etc.).</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"model.editionLike"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.shared"</span> <span class="attribute">type=</span><span class="attributevalue">"model"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Groups elements containing bibliographic edition information.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;classes&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.biblpart.html">model.biblPart</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.titlepagepart.html">model.titlePagePart</a>"</span></span>/&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/classes&gt;</span></div>
                        <span data-indentation="1" class="element">&lt;/classSpec&gt;</span></div></code></div>
            </div>
         </div>
      </div><script type="text/javascript">
            
            var tabbedFacets = document.querySelectorAll('.facet ul.tab');
            
            var tabClick = function(e) {
                var style = e.target.getAttribute('data-display');
                var facetId = e.target.parentNode.parentNode.parentNode.parentNode.id;
                setTabs(facetId,style)
            }
            
            for(var facetUl of tabbedFacets) {
                var facetElem = facetUl.parentNode.parentNode;
                var facetId = facetElem.id;
                var storageName = 'meiSpecs_' + facetId + '_display';
                var defaultValue = facetUl.children[0].children[0].getAttribute('data-display');
                
                if(localStorage.getItem(storageName) === null) {
                    setTabs(facetElem.id,defaultValue);
                } else {
                    setTabs(facetElem.id,localStorage.getItem(storageName));
                }
                
                var tabs = facetUl.querySelectorAll('.tab-item a');
                
                for(var tab of tabs) {
                    tab.addEventListener('click',tabClick);
                }
                
            }
            
            function setTabs(facetId,style) {
                
                var storageName = 'meiSpecs_' + facetId + '_display';
                localStorage.setItem(storageName,style);
                
                var facetElem = document.getElementById(facetId);
                
                var oldTab = facetElem.querySelector('.displayTab.active');
                oldTab.classList.remove('active');
                
                var newTab = document.getElementById(facetId + '_' + style + '_tab');
                newTab.classList.add('active');
                
                var oldBox = facetElem.querySelector('.active.facetTabbedContent');
                oldBox.classList.remove('active');
                oldBox.style.display = 'none';
                
                var newBox = document.getElementById(facetId + '_tabbedContent_' + style);
                newBox.classList.add('active');
                newBox.style.display = 'block';
                
            }
        </script></div>
</div>