---
layout: sidebar
sidebar: s1
version: "dev""
title: "att.midiTempo"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.midiTempo">att.midiTempo</h3>
      <div class="specs">
         <div class="desc">Attributes that record MIDI tempo information.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.midi</div>
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
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="Captures the number of *quarter notes* per minute. In MIDI, a beat is always defined as a quarter note, *not the numerator of the time signature or the metronomic indication*.">midi.bpm</span>, <span class="ident attribute" title="Records the number of microseconds per *quarter note*. In MIDI, a beat is always defined as a quarter note, *not the numerator of the time signature or the metronomic indication*. At 120 quarter notes per minute, each quarter note will last 500,000 microseconds.">midi.mspb</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.midi"><span class="ident attribute" title="Captures the number of *quarter notes* per minute. In MIDI, a beat is always defined as a quarter note, *not the numerator of the time signature or the metronomic indication*.">midi.bpm</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Captures the number of *quarter notes* per minute. In MIDI, a beat is always defined
                        as a quarter note, *not the numerator of the time signature or the metronomic
                        indication*.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.midibpm.html">data.MIDIBPM</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.midi"><span class="ident attribute" title="Records the number of microseconds per *quarter note*. In MIDI, a beat is always defined as a quarter note, *not the numerator of the time signature or the metronomic indication*. At 120 quarter notes per minute, each quarter note will last 500,000 microseconds.">midi.mspb</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the number of microseconds per *quarter note*. In MIDI, a beat is always
                        defined as a quarter note, *not the numerator of the time signature or the metronomic
                        indication*. At 120 quarter notes per minute, each quarter note will last 500,000
                        microseconds.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.midimspb.html">data.MIDIMSPB</a>.
                        </span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox direct" title="direct childs">
                     <div class="classHeading"><label class="classLabel">direct childs</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.midi"><span class="ident attribute" title="Captures the number of *quarter notes* per minute. In MIDI, a beat is always defined as a quarter note, *not the numerator of the time signature or the metronomic indication*.">midi.bpm</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Captures the number of *quarter notes* per minute. In MIDI, a beat is always defined
                              as a quarter note, *not the numerator of the time signature or the metronomic
                              indication*.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.midibpm.html">data.MIDIBPM</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.midi"><span class="ident attribute" title="Records the number of microseconds per *quarter note*. In MIDI, a beat is always defined as a quarter note, *not the numerator of the time signature or the metronomic indication*. At 120 quarter notes per minute, each quarter note will last 500,000 microseconds.">midi.mspb</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the number of microseconds per *quarter note*. In MIDI, a beat is always
                              defined as a quarter note, *not the numerator of the time signature or the metronomic
                              indication*. At 120 quarter notes per minute, each quarter note will last 500,000
                              microseconds.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.midimspb.html">data.MIDIMSPB</a>.
                              </span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.midi">
                     <div class="classHeading"><label class="classLabel">MEI.midi</label><span class="classDesc">MIDI component declarations.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.midi"><span class="ident attribute" title="Captures the number of *quarter notes* per minute. In MIDI, a beat is always defined as a quarter note, *not the numerator of the time signature or the metronomic indication*.">midi.bpm</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Captures the number of *quarter notes* per minute. In MIDI, a beat is always defined
                              as a quarter note, *not the numerator of the time signature or the metronomic
                              indication*.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.midibpm.html">data.MIDIBPM</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.midi"><span class="ident attribute" title="Records the number of microseconds per *quarter note*. In MIDI, a beat is always defined as a quarter note, *not the numerator of the time signature or the metronomic indication*. At 120 quarter notes per minute, each quarter note will last 500,000 microseconds.">midi.mspb</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the number of microseconds per *quarter note*. In MIDI, a beat is always
                              defined as a quarter note, *not the numerator of the time signature or the metronomic
                              indication*. At 120 quarter notes per minute, each quarter note will last 500,000
                              microseconds.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.midimspb.html">data.MIDIMSPB</a>.
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
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="(score definition) – Container for score meta-information."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a></span>, <span class="ident element" title="Text and symbols descriptive of tempo, mood, or style, e.g., &#34;allarg.&#34;, &#34;a tempo&#34;, &#34;cantabile&#34;, &#34;Moderato&#34;, &#34;♩=60&#34;, &#34;Moderato ♩ =60&#34;)."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/tempo.html">tempo</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.midiTempo">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.miditempo.html">att.midiTempo</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="classBox" title="att.scoreDef.ges">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.scoredef.ges.html">att.scoreDef.ges</a></label><span class="classDesc"></span></div>
                           <div class="classContent">
                              <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a><span class="elementDesc">(score definition) – Container for score meta-information.</span></div>
                           </div>
                        </div>
                        <div class="classBox" title="att.tempo.ges">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.tempo.ges.html">att.tempo.ges</a></label><span class="classDesc"></span></div>
                           <div class="classContent">
                              <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/tempo.html">tempo</a><span class="elementDesc">Text and symbols descriptive of tempo, mood, or style, e.g., "allarg.", "a tempo",
                                    "cantabile", "Moderato", "♩=60", "Moderato ♩ =60").</span></div>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a><span class="elementDesc">(score definition) – Container for score meta-information.</span></div>
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/tempo.html">tempo</a><span class="elementDesc">Text and symbols descriptive of tempo, mood, or style, e.g., "allarg.", "a tempo",
                              "cantabile", "Moderato", "♩=60", "Moderato ♩ =60").</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.midiTempo"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.midi"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Attributes that record MIDI tempo information.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;attList <span class="attribute">org=</span><span class="attributevalue">"group"</span>&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"midi.bpm"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>Captures the number of *quarter notes* per minute. In MIDI, a beat is always defined
                                 as a quarter note, *not the numerator of the time signature or the metronomic
                                 indication*.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;datatype <span class="attribute">maxOccurs=</span><span class="attributevalue">"1"</span> <span class="attribute">minOccurs=</span><span class="attributevalue">"1"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:ref
                                       
                                       <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.midibpm.html">data.MIDIBPM</a>"</span></span>
                                       /&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/datatype&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/attDef&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"midi.mspb"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>Records the number of microseconds per *quarter note*. In MIDI, a beat is always
                                 defined as a quarter note, *not the numerator of the time signature or the metronomic
                                 indication*. At 120 quarter notes per minute, each quarter note will last 500,000
                                 microseconds.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;datatype <span class="attribute">maxOccurs=</span><span class="attributevalue">"1"</span> <span class="attribute">minOccurs=</span><span class="attributevalue">"1"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:ref
                                       
                                       <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.midimspb.html">data.MIDIMSPB</a>"</span></span>
                                       /&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/datatype&gt;</span></div>
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