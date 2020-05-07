---
layout: sidebar
sidebar: s1
version: "v4"
title: "data.TSTAMPOFFSET"
---
<div class="specPage">
   <div class="datatypeSpec">
      <h3 id="data.TSTAMPOFFSET">data.TSTAMPOFFSET</h3>
      <div class="specs">
         <div class="desc">A positive or negative offset from the value given in the tstamp attribute in terms
            of
            musical time, i.e., beats[.fractional beat part].
         </div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI</div>
         </div>
         <div class="facet usedBy" id="usedBy">
            <div class="label">Used by</div>
            <div class="statement list">
               <div class="classBox dtBox" title="Attribute Classes">
                  <div class="classHeading"><label class="classLabel">Attribute Classes</label><span class="classDesc">These class-based attributes use data.TSTAMPOFFSET</span></div>
                  <div class="classContent"><span class="ident attclass" data-ident="att.visualOffset.to" data-module="MEI.shared"><a class="classLink" title="Horizontal offset attributes specified in terms of time." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset.to.html">att.visualOffset.to</a>/<span title="Records a timestamp adjustment of a feature's programmatically-determined location in terms of musical time; that is, beats.">@to</span></span><span class="ident attclass" data-ident="att.visualOffset2.to" data-module="MEI.shared"><a class="classLink" title="Horizontal offset attributes requiring a pair of attributes specified in terms of time." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset2.to.html">att.visualOffset2.to</a>/<span title="Records a timestamp adjustment of a feature's programmatically-determined start point.">@startto</span></span><span class="ident attclass" data-ident="att.visualOffset2.to" data-module="MEI.shared"><a class="classLink" title="Horizontal offset attributes requiring a pair of attributes specified in terms of time." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset2.to.html">att.visualOffset2.to</a>/<span title="Records a timestamp adjustment of a feature's programmatically-determined end point.">@endto</span></span></div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;macroSpec <span class="attribute">ident=</span><span class="attributevalue">"data.TSTAMPOFFSET"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI"</span> <span class="attribute">type=</span><span class="attributevalue">"dt"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>A positive or negative offset from the value given in the tstamp attribute in terms
                           of
                           musical time, i.e., beats[.fractional beat part].<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;content&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:data <span class="attribute">type=</span><span class="attributevalue">"decimal"</span>/&gt;</span></div>
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