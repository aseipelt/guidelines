---
layout: sidebar
sidebar: s1
version: "dev"
title: "data.OTHERSTAFF"
---
<div class="specPage">
   <div class="datatypeSpec">
      <h3 id="data.OTHERSTAFF">data.OTHERSTAFF</h3>
      <div class="specs">
         <div class="desc">For musical material designated to appear on another staff, the location of the staff
            relative to the current one; i.e., the staff above or the staff below.
         </div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI</div>
         </div>
         <div class="facet usedBy" id="usedBy">
            <div class="label">Used by</div>
            <div class="statement list">
               <div class="classBox dtBox" title="Attribute Classes">
                  <div class="classHeading"><label class="classLabel">Attribute Classes</label><span class="classDesc">These class-based attributes use data.OTHERSTAFF</span></div>
                  <div class="classContent"><span class="ident attclass" data-ident="att.beamedWith" data-module="MEI.cmn"><a class="classLink" title="Attributes indicating cross-staff beaming." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beamedwith.html">att.beamedWith</a>/<span title="In the case of cross-staff beams, the beam.with attribute is used to indicate which staff the beam is connected to; that is, the staff above or the staff below.">@beam.with</span></span><span class="ident attclass" data-ident="att.stems.cmn" data-module="MEI.cmn"><a class="classLink" title="Attributes that describe the properties of stemmed features; that is, chords and notes." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.stems.cmn.html">att.stems.cmn</a>/<span title="Contains an indication of which staff a note or chord that logically belongs to the current staff should be visually placed on; that is, the one above or the one below.">@stem.with</span></span></div>
               </div>
            </div>
         </div>
         <div class="facet allowedValues" id="allowedValues">
            <div class="label">Allowed Values</div>
            <div class="statement list">
               <div class="dataValueBox" id="above"><span class="dataValue ident">above</span><span class="dataValue desc">The staff immediately above.</span></div>
               <div class="dataValueBox" id="below"><span class="dataValue ident">below</span><span class="dataValue desc">The staff immediately below.</span></div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;macroSpec <span class="attribute">ident=</span><span class="attributevalue">"data.OTHERSTAFF"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI"</span> <span class="attribute">type=</span><span class="attributevalue">"dt"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>For musical material designated to appear on another staff, the location of the staff
                           relative to the current one; i.e., the staff above or the staff below.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;content&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;valList <span class="attribute">type=</span><span class="attributevalue">"closed"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"above"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>The staff immediately above.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"below"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>The staff immediately below.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/valList&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/content&gt;</span></div>
                        <span data-indentation="1" class="element">&lt;/macroSpec&gt;</span></div></code></div>
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