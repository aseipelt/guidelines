---
layout: sidebar
sidebar: s1
version: "dev"
title: "att.harm.anl"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.harm.anl">att.harm.anl</h3>
      <div class="specs">
         <div class="desc">Analytical domain attributes.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.analytical</div>
         </div>
         <div class="facet attributes" id="attributes">
            <div class="label">Attributes</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="attributes_compact_tab" href="#attributes" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="full" id="attributes_full_tab" href="#attributes" class="displayTab">full definition</a></li>
                  <li class="tab-item"><a data-display="class" id="attributes_class_tab" href="#attributes" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="attributes_module_tab" href="#attributes" class="displayTab">by module</a></li>
               </ul>
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="Indicates to what degree the harmonic label is supported by the notation.">form</span>, <span class="ident attribute" title="Encodes the harmonic interval between pitches occurring at the same time.">inth</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Indicates to what degree the harmonic label is supported by the notation.">form</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Indicates to what degree the harmonic label is supported by the notation.</span><span class="attributeValues">
                        Allowed values are:
                        "<span style="font-weight: 500;">explicit</span>" <i>(The notation contains all the notes necessary for the harmonic label, e.g., the
                           notes "D F♯ A" for the harmonic label "D".)</i>,  "<span style="font-weight: 500;">implied</span>" <i>(The harmonic label relies on notes implied, but not actually present, in the
                           notation, e.g., the notes "D F♯ C" for the harmonic label "D7". The note "A" is
                           missing from the notation, but can be implied.)</i></span></div>
                  <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Encodes the harmonic interval between pitches occurring at the same time.">inth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the harmonic interval between pitches occurring at the same time.</span><span class="attributeValues">
                        One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.interval.harmonic.html">data.INTERVAL.HARMONIC</a>, separated by spaces.
                        </span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox direct" title="direct childs">
                     <div class="classHeading"><label class="classLabel">direct childs</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Indicates to what degree the harmonic label is supported by the notation.">form</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Indicates to what degree the harmonic label is supported by the notation.</span><span class="attributeValues">
                              Allowed values are:
                              "<span style="font-weight: 500;">explicit</span>" <i>(The notation contains all the notes necessary for the harmonic label, e.g., the
                                 notes "D F♯ A" for the harmonic label "D".)</i>,  "<span style="font-weight: 500;">implied</span>" <i>(The harmonic label relies on notes implied, but not actually present, in the
                                 notation, e.g., the notes "D F♯ C" for the harmonic label "D7". The note "A" is
                                 missing from the notation, but can be implied.)</i></span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.intervalHarmonic">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.intervalharmonic.html">att.intervalHarmonic</a></label><span class="classDesc">(MEI.analytical) Attributes that describe harmonic intervals.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Encodes the harmonic interval between pitches occurring at the same time.">inth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the harmonic interval between pitches occurring at the same time.</span><span class="attributeValues">
                              One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.interval.harmonic.html">data.INTERVAL.HARMONIC</a>, separated by spaces.
                              </span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.analytical">
                     <div class="classHeading"><label class="classLabel">MEI.analytical</label><span class="classDesc">Analytical component declarations.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Indicates to what degree the harmonic label is supported by the notation.">form</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Indicates to what degree the harmonic label is supported by the notation.</span><span class="attributeValues">
                              Allowed values are:
                              "<span style="font-weight: 500;">explicit</span>" <i>(The notation contains all the notes necessary for the harmonic label, e.g., the
                                 notes "D F♯ A" for the harmonic label "D".)</i>,  "<span style="font-weight: 500;">implied</span>" <i>(The harmonic label relies on notes implied, but not actually present, in the
                                 notation, e.g., the notes "D F♯ C" for the harmonic label "D7". The note "A" is
                                 missing from the notation, but can be implied.)</i></span></div>
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Encodes the harmonic interval between pitches occurring at the same time.">inth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the harmonic interval between pitches occurring at the same time.</span><span class="attributeValues">
                              One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.interval.harmonic.html">data.INTERVAL.HARMONIC</a>, separated by spaces.
                              </span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet availableAt" id="availableAt">
            <div class="label">Available at</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="availableAt_compact_tab" href="#availableAt" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="class" id="availableAt_class_tab" href="#availableAt" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="availableAt_module_tab" href="#availableAt" class="displayTab">by module</a></li>
               </ul>
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="(harmony) – An indication of harmony, e.g., chord names, tablature grids, harmonic analysis, figured bass."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/harm.html">harm</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.harm.anl">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.harm.anl.html">att.harm.anl</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.harmony"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/harm.html">harm</a><span class="elementDesc">(harmony) – An indication of harmony, e.g., chord names, tablature grids, harmonic
                              analysis, figured bass.</span></div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.harmony">
                     <div class="classHeading"><label class="classLabel">MEI.harmony</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.harmony"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/harm.html">harm</a><span class="elementDesc">(harmony) – An indication of harmony, e.g., chord names, tablature grids, harmonic
                              analysis, figured bass.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.harm.anl"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.analytical"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Analytical domain attributes.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;classes&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.intervalharmonic.html">att.intervalHarmonic</a>"</span></span>/&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/classes&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;attList <span class="attribute">org=</span><span class="attributevalue">"group"</span>&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"form"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>Indicates to what degree the harmonic label is supported by the notation.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valList <span class="attribute">type=</span><span class="attributevalue">"closed"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"explicit"</span>&gt;</span>
                                    
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;desc&gt;</span>The notation contains all the notes necessary for the harmonic label, e.g., the
                                       notes "D F♯ A" for the harmonic label "D".<span data-indentation="6" class="element">&lt;/desc&gt;</span></div>
                                    <span data-indentation="5" class="element">&lt;/valItem&gt;</span></div>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"implied"</span>&gt;</span>
                                    
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;desc&gt;</span>The harmonic label relies on notes implied, but not actually present, in the
                                       notation, e.g., the notes "D F♯ C" for the harmonic label "D7". The note "A" is
                                       missing from the notation, but can be implied.<span data-indentation="6" class="element">&lt;/desc&gt;</span></div>
                                    <span data-indentation="5" class="element">&lt;/valItem&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valList&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/attDef&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/attList&gt;</span></div>
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