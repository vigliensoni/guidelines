---
layout: sidebar
sidebar: s1
version: "v3"
title: "data.INTERVAL.HARMONIC"

---

<div class="macroSpec">
   <h3 id="data.INTERVAL.HARMONIC">data.INTERVAL.HARMONIC</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">data.INTERVAL.HARMONIC</span> A token indicating diatonic interval quality and size.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Used by</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.intervalharmonic">att.intervalharmonic</a> (@inth)
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Declaration</span>
         </td>
         <td class="wovenodd-col2">
            <div xml:space="preserve" class="pre">
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;content&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;rng:choice&gt;</span>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:data 
                           <span class="attribute">type=</span>
                           <span class="attributevalue">"token"</span>&gt;
                        </span>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:param 
                              <span class="attribute">name=</span>
                              <span class="attributevalue">"pattern"</span>&gt;
                           </span>[AdMmP][0-9]+
                           <span data-indentation="4" class="element">&lt;/rng:param&gt;</span>
                        </div>
                        
                        <span data-indentation="3" class="element">&lt;/rng:data&gt;</span>
                     </div>
                     
                     <span data-indentation="2" class="element">&lt;/rng:choice&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/content&gt;</span>
               </div>
            </div>
         </td>
      </tr>
   </table>
</div>