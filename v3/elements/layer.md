---
layout: sidebar
sidebar: s1
version: "v3"
title: "layer"

---

<div class="elementSpec">
   <h3 id="layer">&lt;layer&gt;</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">&lt;layer&gt;</span> An independent stream of events on a staff.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI.shared</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Attributes</span>
         </td>
         <td class="wovenodd-col2">
            <div class="attributeDef">
               <span class="attribute">@copyof</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to an element of which the current element is a copy.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@corresp</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to point to other elements that correspond to this one in a generic
                  fashion.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@decls</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Identifies one or more metadata elements within the header, which are understood to
                  apply to the element bearing this attribute and its content.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.declaring">att.declaring</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@def</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a mechanism for linking the layer to a layerDef element.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.layer.log">att.layer.log</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@facs</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Permits the current element to reference a facsimile surface or image zone which
                  corresponds to it.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.facsimile">att.facsimile</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@label</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a name or label for an element. The value may be any string.</span>
               Value of datatype 
               <span style="font-weight: 500;">string</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.commonPart">att.commonPart</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@metcon</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the relationship between the content of a staff or layer and the
                  prevailing meter.
               </span>
               Allowed values are:
               "
               <span style="font-weight: 500;">c</span>" 
               <i>(Complete; i.e., conformant with the prevailing meter.)</i>,  "
               <span style="font-weight: 500;">i</span>" 
               <i>(Incomplete; i.e., not enough beats.)</i>,  "
               <span style="font-weight: 500;">o</span>" 
               <i>(Overfull; i.e., too many beats.)</i>
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.meterconformance">att.meterconformance</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@n</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">A non-negative integer value functioning as a "name".</span>
               Value of datatype 
               <span style="font-weight: 500;">nonNegativeInteger</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/layer">layer</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@next</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to point to the next event(s) in a user-defined collection.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@prev</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to the previous event(s) in a user-defined collection.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@sameas</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to an element that is the same as the current element but is not a literal
                  copy of the current element.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@synch</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to elements that are synchronous with the current element.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@visible</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates if a feature should be rendered when the notation is presented graphically
                  or sounded when it is presented in an aural form.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.BOOLEAN">data.BOOLEAN</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.visibility">att.visibility</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@when</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the point of occurrence of this feature along a time line. Its value must
                  be the ID of a 
                  <a class="link_odd_elementSpec" href="/{{ v3}}/when">when</a> element elsewhere in the document.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.alignment">att.alignment</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@xml:base</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a base URI reference with which applications can resolve relative URI
                  references into absolute URI references.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ v3}}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.commonPart">att.commonPart</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@xml:id</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Regularizes the naming of an element and thus facilitates building links between it
                  and other resources. Each id attribute within a document must have a unique
                  value.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">ID</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ v3}}/att.id">att.id</a>
               </span>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Member of</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <a class="link_odd_classSpec" href="/{{ v3}}/model.layerLike">model.layerLike</a>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Contained by</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div class="specChildren">
                  <div class="specChild">
                     <span class="specChildModule">MEI.cmn</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ v3}}/ossia">ossia</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.critapp</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ v3}}/lem">lem</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/rdg">rdg</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.edittrans</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ v3}}/abbr">abbr</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/add">add</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/corr">corr</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/damage">damage</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/del">del</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/expan">expan</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/orig">orig</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/reg">reg</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/restore">restore</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/sic">sic</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/supplied">supplied</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/unclear">unclear</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.shared</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ v3}}/layer">layer</a> 
                        <a class="link_odd_elementSpec" href="/{{ v3}}/staff">staff</a>
                     </span>
                  </div>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">May contain</span>
         </td>
         <td class="wovenodd-col2">
            <div class="specChildren">
               <div class="specChild">
                  <span class="specChildModule">MEI.cmn</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/arpeg">arpeg</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/beam">beam</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/beamSpan">beamSpan</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/beatRpt">beatRpt</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/bend">bend</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/breath">breath</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/bTrem">bTrem</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/fermata">fermata</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/fTrem">fTrem</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/gliss">gliss</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/hairpin">hairpin</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/halfmRpt">halfmRpt</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/harpPedal">harpPedal</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/meterSig">meterSig</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/meterSigGrp">meterSigGrp</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/mRest">mRest</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/mRpt">mRpt</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/mRpt2">mRpt2</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/mSpace">mSpace</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/multiRest">multiRest</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/multiRpt">multiRpt</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/octave">octave</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/pedal">pedal</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/reh">reh</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/slur">slur</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/tie">tie</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/tuplet">tuplet</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/tupletSpan">tupletSpan</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.cmnOrnaments</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/mordent">mordent</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/trill">trill</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/turn">turn</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.critapp</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/app">app</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.edittrans</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/add">add</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/choice">choice</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/corr">corr</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/cpMark">cpMark</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/damage">damage</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/del">del</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/gap">gap</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/handShift">handShift</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/orig">orig</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/reg">reg</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/restore">restore</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/sic">sic</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/subst">subst</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/supplied">supplied</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/unclear">unclear</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.fingering</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/fing">fing</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/fingGrp">fingGrp</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.harmony</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/harm">harm</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.lyrics</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/lyrics">lyrics</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.mensural</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/ligature">ligature</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/mensur">mensur</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/proport">proport</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.midi</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/midi">midi</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.neumes</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/ineume">ineume</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/syllable">syllable</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/uneume">uneume</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.shared</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/accid">accid</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/annot">annot</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/artic">artic</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/barLine">barLine</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/chord">chord</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/clef">clef</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/clefGrp">clefGrp</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/custos">custos</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/dir">dir</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/div">div</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/dot">dot</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/dynam">dynam</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/keySig">keySig</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/note">note</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/ornam">ornam</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/pad">pad</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/pb">pb</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/phrase">phrase</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/rest">rest</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/sb">sb</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/scoreDef">scoreDef</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/space">space</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/staffDef">staffDef</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/tempo">tempo</a>
                  </span>
               </div>
               <div class="specChild">
                  <span class="specChildModule">MEI.usersymbols</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ v3}}/anchoredText">anchoredText</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/curve">curve</a> 
                     <a class="link_odd_elementSpec" href="/{{ v3}}/line">line</a>
                  </span>
               </div>
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
                  <span data-indentation="1" class="element">&lt;classes&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.commonPart">att.commonPart</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.declaring">att.declaring</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.facsimile">att.facsimile</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.layer.log">att.layer.log</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.layer.vis">att.layer.vis</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.layer.ges">att.layer.ges</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.layer.anl">att.layer.anl</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/model.layerLike">model.layerLike</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/classes&gt;</span>
               </div>
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;content&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;rng:zeroOrMore&gt;</span>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:choice&gt;</span>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:ref 
                              <span class="attribute">name=</span>
                              <span class="attributevalue">"
                                 <a class="link_odd" href="/model.appLike">model.appLike</a>"
                              </span>/&gt;
                           </span>
                        </div>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:ref 
                              <span class="attribute">name=</span>
                              <span class="attributevalue">"
                                 <a class="link_odd" href="/model.divLike">model.divLike</a>"
                              </span>/&gt;
                           </span>
                        </div>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:ref 
                              <span class="attribute">name=</span>
                              <span class="attributevalue">"
                                 <a class="link_odd" href="/model.milestoneLike.music">model.milestoneLike.music</a>"
                              </span>/&gt;
                           </span>
                        </div>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:ref 
                              <span class="attribute">name=</span>
                              <span class="attributevalue">"
                                 <a class="link_odd" href="/model.annotLike">model.annotLike</a>"
                              </span>/&gt;
                           </span>
                        </div>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:ref 
                              <span class="attribute">name=</span>
                              <span class="attributevalue">"
                                 <a class="link_odd" href="/model.graphicprimitiveLike">model.graphicprimitiveLike</a>"
                              </span>/&gt;
                           </span>
                        </div>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:ref 
                              <span class="attribute">name=</span>
                              <span class="attributevalue">"
                                 <a class="link_odd" href="/model.editLike">model.editLike</a>"
                              </span>/&gt;
                           </span>
                        </div>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:ref 
                              <span class="attribute">name=</span>
                              <span class="attributevalue">"
                                 <a class="link_odd" href="/model.transcriptionLike">model.transcriptionLike</a>"
                              </span>/&gt;
                           </span>
                        </div>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:ref 
                              <span class="attribute">name=</span>
                              <span class="attributevalue">"
                                 <a class="link_odd" href="/model.layerPart">model.layerPart</a>"
                              </span>/&gt;
                           </span>
                        </div>
                        
                        <span data-indentation="3" class="element">&lt;/rng:choice&gt;</span>
                     </div>
                     
                     <span data-indentation="2" class="element">&lt;/rng:zeroOrMore&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/content&gt;</span>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Remarks</span>
         </td>
         <td class="wovenodd-col2">
            <p>The term 'layer' is used instead of 'voice' in order to avoid confusion between 'voice'
               and 'voice leading' and 'voicing'. The 
               <span class="att">def</span> attribute may be used to create a
               connection with a 
               <a class="link_odd_elementSpec" href="/{{ v3}}/layerDef">layerDef</a> element where logical and visual
               information about the layer is recorded. Alternatively, the 
               <span class="att">n</span> attribute may be
               used as a reference to a 
               <a class="link_odd_elementSpec" href="/{{ v3}}/layerDef">layerDef</a> element with the same value in its
               
               <span class="att">n</span> attribute. If neither 
               <span class="att">def</span> nor 
               <span class="att">n</span> attributes are
               present, then encoding order of the layers is presumed to match the encoding order
               of the
               layer definitions.
            </p>
         </td>
      </tr>
   </table>
</div>