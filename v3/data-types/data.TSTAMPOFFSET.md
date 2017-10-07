---
layout: sidebar
sidebar: s1
version: "v3"
title: "data.TSTAMPOFFSET"

---

<div class="macroSpec">
   <h3 id="data.TSTAMPOFFSET">data.TSTAMPOFFSET</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">data.TSTAMPOFFSET</span> A positive or negative offset from the value given in the tstamp attribute in terms
            of
            musical time, i.e., beats[.fractional beat part].
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
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.visualoffset.to">att.visualoffset.to</a> (@to), 
               <a class="link_odd_classSpec" href="/{{ page.version }}/att.visualoffset2.to">att.visualoffset2.to</a> (@startto)
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
                     <span data-indentation="2" class="element">&lt;rng:data 
                        <span class="attribute">type=</span>
                        <span class="attributevalue">"decimal"</span>/&gt;
                     </span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/content&gt;</span>
               </div>
            </div>
         </td>
      </tr>
   </table>
</div>