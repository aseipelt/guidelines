---
layout: sidebar
sidebar: s1
version: "dev"
title: "att.nc.anl"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.nc.anl">att.nc.anl</h3>
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
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="Captures scale degree information using Humdrum **deg syntax -- an optional indicator of melodic approach (^ = ascending approach, v = descending approach), a scale degree value (1 = tonic ... 7 = leading tone), and an optional indication of chromatic alteration, &#34;1&#34;, &#34;v7&#34;, &#34;^1&#34;, or &#34;v5+&#34;, for example. The amount of chromatic alternation is not indicated.">deg</span>, <span class="ident attribute" title="Encodes the melodic interval from the previous pitch. The value may be a general directional indication (u, d, s, etc.), an indication of diatonic interval direction, quality, and size, or a precise numeric value in half steps.">intm</span>, <span class="ident attribute" title="Describes melodic function using Humdrum **embel syntax.">mfunc</span>, <span class="ident attribute" title="Holds pitch class information.">pclass</span>, <span class="ident attribute" title="Contains sol-fa designation, e.g., do, re, mi, etc., in either a fixed or movable Do system.">psolfa</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Captures scale degree information using Humdrum **deg syntax -- an optional indicator of melodic approach (^ = ascending approach, v = descending approach), a scale degree value (1 = tonic ... 7 = leading tone), and an optional indication of chromatic alteration, &#34;1&#34;, &#34;v7&#34;, &#34;^1&#34;, or &#34;v5+&#34;, for example. The amount of chromatic alternation is not indicated.">deg</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Captures scale degree information using Humdrum **deg syntax -- an optional indicator
                        of melodic approach (^ = ascending approach, v = descending approach), a scale degree
                        value (1 = tonic ... 7 = leading tone), and an optional indication of chromatic
                        alteration, "1", "v7", "^1", or "v5+", for example. The amount of chromatic alternation
                        is
                        not indicated.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.scaledegree.html">data.SCALEDEGREE</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Encodes the melodic interval from the previous pitch. The value may be a general directional indication (u, d, s, etc.), an indication of diatonic interval direction, quality, and size, or a precise numeric value in half steps.">intm</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the melodic interval from the previous pitch. The value may be a general
                        directional indication (u, d, s, etc.), an indication of diatonic interval direction,
                        quality, and size, or a precise numeric value in half steps.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.interval.melodic.html">data.INTERVAL.MELODIC</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Describes melodic function using Humdrum **embel syntax.">mfunc</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes melodic function using Humdrum **embel syntax.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.melodicfunction.html">data.MELODICFUNCTION</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Holds pitch class information.">pclass</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds pitch class information.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.pitchclass.html">data.PITCHCLASS</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Contains sol-fa designation, e.g., do, re, mi, etc., in either a fixed or movable Do system.">psolfa</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains sol-fa designation, e.g., do, re, mi, etc., in either a fixed or movable
                        Do
                        system.</span><span class="attributeValues">
                        Value is a <a target="_blank" href="https://www.w3.org/TR/xmlschema11-2/#NMTOKEN">NMTOKEN</a>.
                        </span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.harmonicFunction">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.harmonicfunction.html">att.harmonicFunction</a></label><span class="classDesc">(MEI.analytical) Attributes describing the harmonic function of a single pitch.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Captures scale degree information using Humdrum **deg syntax -- an optional indicator of melodic approach (^ = ascending approach, v = descending approach), a scale degree value (1 = tonic ... 7 = leading tone), and an optional indication of chromatic alteration, &#34;1&#34;, &#34;v7&#34;, &#34;^1&#34;, or &#34;v5+&#34;, for example. The amount of chromatic alternation is not indicated.">deg</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Captures scale degree information using Humdrum **deg syntax -- an optional indicator
                              of melodic approach (^ = ascending approach, v = descending approach), a scale degree
                              value (1 = tonic ... 7 = leading tone), and an optional indication of chromatic
                              alteration, "1", "v7", "^1", or "v5+", for example. The amount of chromatic alternation
                              is
                              not indicated.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.scaledegree.html">data.SCALEDEGREE</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.intervalMelodic">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.intervalmelodic.html">att.intervalMelodic</a></label><span class="classDesc">(MEI.analytical) Attributes that provide for description of intervallic content.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Encodes the melodic interval from the previous pitch. The value may be a general directional indication (u, d, s, etc.), an indication of diatonic interval direction, quality, and size, or a precise numeric value in half steps.">intm</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the melodic interval from the previous pitch. The value may be a general
                              directional indication (u, d, s, etc.), an indication of diatonic interval direction,
                              quality, and size, or a precise numeric value in half steps.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.interval.melodic.html">data.INTERVAL.MELODIC</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.melodicFunction">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.melodicfunction.html">att.melodicFunction</a></label><span class="classDesc">(MEI.analytical) Attributes describing melodic function.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Describes melodic function using Humdrum **embel syntax.">mfunc</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes melodic function using Humdrum **embel syntax.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.melodicfunction.html">data.MELODICFUNCTION</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.pitchClass">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.pitchclass.html">att.pitchClass</a></label><span class="classDesc">(MEI.analytical) Attributes that describe pitch class.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Holds pitch class information.">pclass</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds pitch class information.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.pitchclass.html">data.PITCHCLASS</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.solfa">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.solfa.html">att.solfa</a></label><span class="classDesc">(MEI.analytical) Attributes that specify pitch using sol-fa.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Contains sol-fa designation, e.g., do, re, mi, etc., in either a fixed or movable Do system.">psolfa</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains sol-fa designation, e.g., do, re, mi, etc., in either a fixed or movable
                              Do
                              system.</span><span class="attributeValues">
                              Value is a <a target="_blank" href="https://www.w3.org/TR/xmlschema11-2/#NMTOKEN">NMTOKEN</a>.
                              </span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.analytical">
                     <div class="classHeading"><label class="classLabel">MEI.analytical</label><span class="classDesc">Analytical component declarations.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Captures scale degree information using Humdrum **deg syntax -- an optional indicator of melodic approach (^ = ascending approach, v = descending approach), a scale degree value (1 = tonic ... 7 = leading tone), and an optional indication of chromatic alteration, &#34;1&#34;, &#34;v7&#34;, &#34;^1&#34;, or &#34;v5+&#34;, for example. The amount of chromatic alternation is not indicated.">deg</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Captures scale degree information using Humdrum **deg syntax -- an optional indicator
                              of melodic approach (^ = ascending approach, v = descending approach), a scale degree
                              value (1 = tonic ... 7 = leading tone), and an optional indication of chromatic
                              alteration, "1", "v7", "^1", or "v5+", for example. The amount of chromatic alternation
                              is
                              not indicated.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.scaledegree.html">data.SCALEDEGREE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Encodes the melodic interval from the previous pitch. The value may be a general directional indication (u, d, s, etc.), an indication of diatonic interval direction, quality, and size, or a precise numeric value in half steps.">intm</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the melodic interval from the previous pitch. The value may be a general
                              directional indication (u, d, s, etc.), an indication of diatonic interval direction,
                              quality, and size, or a precise numeric value in half steps.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.interval.melodic.html">data.INTERVAL.MELODIC</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Describes melodic function using Humdrum **embel syntax.">mfunc</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes melodic function using Humdrum **embel syntax.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.melodicfunction.html">data.MELODICFUNCTION</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Holds pitch class information.">pclass</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds pitch class information.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.pitchclass.html">data.PITCHCLASS</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.analytical"><span class="ident attribute" title="Contains sol-fa designation, e.g., do, re, mi, etc., in either a fixed or movable Do system.">psolfa</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains sol-fa designation, e.g., do, re, mi, etc., in either a fixed or movable
                              Do
                              system.</span><span class="attributeValues">
                              Value is a <a target="_blank" href="https://www.w3.org/TR/xmlschema11-2/#NMTOKEN">NMTOKEN</a>.
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
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="Sign representing a single pitched event, although the exact pitch may not be known."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/nc.html">nc</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.nc.anl">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.nc.anl.html">att.nc.anl</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.neumes"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/nc.html">nc</a><span class="elementDesc">Sign representing a single pitched event, although the exact pitch may not be
                              known.</span></div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.neumes">
                     <div class="classHeading"><label class="classLabel">MEI.neumes</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.neumes"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/nc.html">nc</a><span class="elementDesc">Sign representing a single pitched event, although the exact pitch may not be
                              known.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.nc.anl"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.analytical"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Analytical domain attributes.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;classes&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.harmonicfunction.html">att.harmonicFunction</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.intervalmelodic.html">att.intervalMelodic</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.melodicfunction.html">att.melodicFunction</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.pitchclass.html">att.pitchClass</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.solfa.html">att.solfa</a>"</span></span>/&gt;</span></div>
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