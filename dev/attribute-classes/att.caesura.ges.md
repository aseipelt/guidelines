---
layout: sidebar
sidebar: s1
version: "dev"
title: "att.caesura.ges"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.caesura.ges">att.caesura.ges</h3>
      <div class="specs">
         <div class="desc">Gestural domain attributes.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.gestural</div>
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
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="Number of dots required for a gestural duration when different from that of the written duration.">dots.ges</span>, <span class="ident attribute" title="Records performed duration information that differs from the written duration.">dur.ges</span>, <span class="ident attribute" title="Duration as a count of units provided in the time signature denominator.">dur.metrical</span>, <span class="ident attribute" title="Duration recorded as pulses-per-quarter note, e.g. MIDI clicks or MusicXML divisions.">dur.ppq</span>, <span class="ident attribute" title="Duration in seconds, e.g. '1.732'.">dur.real</span>, <span class="ident attribute" title="Duration as an optionally dotted Humdrum *recip value.">dur.recip</span>, <span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp.ges</span>, <span class="ident attribute" title="Records the onset time in terms of ISO time.">tstamp.real</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Number of dots required for a gestural duration when different from that of the written duration.">dots.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Number of dots required for a gestural duration when different from that of the
                        written duration.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.augmentdot.html">data.AUGMENTDOT</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Records performed duration information that differs from the written duration.">dur.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records performed duration information that differs from the written duration.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.duration.gestural.html">data.DURATION.gestural</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration as a count of units provided in the time signature denominator.">dur.metrical</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration as a count of units provided in the time signature denominator.</span><span class="attributeValues">
                        Value of datatype <span style="font-weight: 500;">
                           a decimal number matching the pattern "\d+(\.\d+)?"
                           </span>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration recorded as pulses-per-quarter note, e.g. MIDI clicks or MusicXML divisions.">dur.ppq</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration recorded as pulses-per-quarter note, e.g. MIDI clicks or MusicXML
                        divisions.</span><span class="attributeValues">
                        Value of datatype <span style="font-weight: 500;">nonNegativeInteger</span>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration in seconds, e.g. '1.732'.">dur.real</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration in seconds, e.g. '1.732'.</span><span class="attributeValues">
                        Value of datatype <span style="font-weight: 500;">
                           a decimal number matching the pattern "\d+(\.\d+)?"
                           </span>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration as an optionally dotted Humdrum *recip value.">dur.recip</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration as an optionally dotted Humdrum *recip value.</span><span class="attributeValues">
                        Value of datatype <span style="font-weight: 500;">
                           a string matching the following regular expression: "\d+(\.)*"
                           </span>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part],
                        as expressed in the written time signature.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Records the onset time in terms of ISO time.">tstamp.real</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the onset time in terms of ISO time.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isotime.html">data.ISOTIME</a>.
                        </span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.duration.gestural">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.duration.gestural.html">att.duration.gestural</a></label><span class="classDesc">(MEI.gestural) Attributes that record performed duration that differs from a feature's
                           written duration.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Records performed duration information that differs from the written duration.">dur.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records performed duration information that differs from the written duration.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.duration.gestural.html">data.DURATION.gestural</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Number of dots required for a gestural duration when different from that of the written duration.">dots.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Number of dots required for a gestural duration when different from that of the
                              written duration.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.augmentdot.html">data.AUGMENTDOT</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration as a count of units provided in the time signature denominator.">dur.metrical</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration as a count of units provided in the time signature denominator.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">
                                 a decimal number matching the pattern "\d+(\.\d+)?"
                                 </span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration recorded as pulses-per-quarter note, e.g. MIDI clicks or MusicXML divisions.">dur.ppq</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration recorded as pulses-per-quarter note, e.g. MIDI clicks or MusicXML
                              divisions.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">nonNegativeInteger</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration in seconds, e.g. '1.732'.">dur.real</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration in seconds, e.g. '1.732'.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">
                                 a decimal number matching the pattern "\d+(\.\d+)?"
                                 </span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration as an optionally dotted Humdrum *recip value.">dur.recip</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration as an optionally dotted Humdrum *recip value.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">
                                 a string matching the following regular expression: "\d+(\.)*"
                                 </span>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.timestamp.gestural">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.gestural.html">att.timestamp.gestural</a></label><span class="classDesc">(MEI.gestural) Attributes that record a performed (as opposed to notated) time stamp.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part],
                              as expressed in the written time signature.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Records the onset time in terms of ISO time.">tstamp.real</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the onset time in terms of ISO time.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isotime.html">data.ISOTIME</a>.
                              </span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.gestural">
                     <div class="classHeading"><label class="classLabel">MEI.gestural</label><span class="classDesc">Gestural component declarations.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Number of dots required for a gestural duration when different from that of the written duration.">dots.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Number of dots required for a gestural duration when different from that of the
                              written duration.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.augmentdot.html">data.AUGMENTDOT</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Records performed duration information that differs from the written duration.">dur.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records performed duration information that differs from the written duration.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.duration.gestural.html">data.DURATION.gestural</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration as a count of units provided in the time signature denominator.">dur.metrical</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration as a count of units provided in the time signature denominator.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">
                                 a decimal number matching the pattern "\d+(\.\d+)?"
                                 </span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration recorded as pulses-per-quarter note, e.g. MIDI clicks or MusicXML divisions.">dur.ppq</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration recorded as pulses-per-quarter note, e.g. MIDI clicks or MusicXML
                              divisions.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">nonNegativeInteger</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration in seconds, e.g. '1.732'.">dur.real</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration in seconds, e.g. '1.732'.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">
                                 a decimal number matching the pattern "\d+(\.\d+)?"
                                 </span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Duration as an optionally dotted Humdrum *recip value.">dur.recip</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Duration as an optionally dotted Humdrum *recip value.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">
                                 a string matching the following regular expression: "\d+(\.)*"
                                 </span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part],
                              as expressed in the written time signature.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Records the onset time in terms of ISO time.">tstamp.real</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the onset time in terms of ISO time.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isotime.html">data.ISOTIME</a>.
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
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="Break, pause, or interruption in the normal tempo of a composition. Typically indicated by &#34;railroad tracks&#34;, i.e., two diagonal slashes."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/caesura.html">caesura</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.caesura.ges">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.caesura.ges.html">att.caesura.ges</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/caesura.html">caesura</a><span class="elementDesc">Break, pause, or interruption in the normal tempo of a composition. Typically indicated
                              by
                              "railroad tracks", i.e., two diagonal slashes.</span></div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/caesura.html">caesura</a><span class="elementDesc">Break, pause, or interruption in the normal tempo of a composition. Typically indicated
                              by
                              "railroad tracks", i.e., two diagonal slashes.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.caesura.ges"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.gestural"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Gestural domain attributes.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;classes&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.duration.gestural.html">att.duration.gestural</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.gestural.html">att.timestamp.gestural</a>"</span></span>/&gt;</span></div>
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