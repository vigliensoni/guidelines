---
layout: sidebar
sidebar: s1
version: "v4"
title: "att.name"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.name">att.name</h3>
      <div class="specs">
         <div class="desc">Attributes shared by names.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.shared</div>
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
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="A name or label associated with a controlled vocabulary or other authoritative source for this element or its content.">auth</span>, <span class="ident attribute" title="A web-accessible location of the controlled vocabulary or other authoritative source of identification or definition for this element or its content. This attribute may contain a complete URI or a partial URI which is completed by the value of the codedval attribute.">auth.uri</span>, <span class="ident attribute" title="auth auth.uri A value that represents or identifies other data. Often, it is a primary key in the database or a unique value in the coded list identified by the or attributes.">codedval</span>, <span class="ident attribute" title="Contains the end point of a date range in standard ISO form.">enddate</span>, <span class="ident attribute" title="Provides the value of a textual date in standard ISO form.">isodate</span>, <span class="ident attribute" title="Holds the number of initial characters (such as those constituting an article or preposition) that should not be used for sorting a title or name.">nonfiling</span>, <span class="ident attribute" title="Contains an upper boundary for an uncertain date in standard ISO form.">notafter</span>, <span class="ident attribute" title="Contains a lower boundary, in standard ISO form, for an uncertain date.">notbefore</span>, <span class="ident attribute" title="Used to record a pointer to the regularized form of the name elsewhere in the document.">nymref</span>, <span class="ident attribute" title="Used to specify further information about the entity referenced by this name, for example, the occupation of a person or the status of a place.">role</span>, <span class="ident attribute" title="Contains the starting point of a date range in standard ISO form.">startdate</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="A name or label associated with a controlled vocabulary or other authoritative source for this element or its content.">auth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A name or label associated with a controlled vocabulary or other authoritative source
                        for this element or its content.</span><span class="attributeValues">
                        Value is plain text.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="A web-accessible location of the controlled vocabulary or other authoritative source of identification or definition for this element or its content. This attribute may contain a complete URI or a partial URI which is completed by the value of the codedval attribute.">auth.uri</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A web-accessible location of the controlled vocabulary or other authoritative source
                        of identification or definition for this element or its content. This attribute may
                        contain a complete URI or a partial URI which is completed by the value of the codedval
                        attribute.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="auth auth.uri A value that represents or identifies other data. Often, it is a primary key in the database or a unique value in the coded list identified by the or attributes.">codedval</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A value that represents or identifies other data. Often, it is a primary key in the
                        database or a unique value in the coded list identified by the <span class="att">auth</span> or
                        <span class="att">auth.uri</span> attributes.</span><span class="attributeValues">
                        One or more values of datatype <span style="font-weight: 500;">NMTOKEN</span>, separated by spaces.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains the end point of a date range in standard ISO form.">enddate</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains the end point of a date range in standard ISO form.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Provides the value of a textual date in standard ISO form.">isodate</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Provides the value of a textual date in standard ISO form.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the number of initial characters (such as those constituting an article or preposition) that should not be used for sorting a title or name.">nonfiling</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the number of initial characters (such as those constituting an article or
                        preposition) that should not be used for sorting a title or name.</span><span class="attributeValues">
                        Value is a positive integer.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains an upper boundary for an uncertain date in standard ISO form.">notafter</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains an upper boundary for an uncertain date in standard ISO form.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains a lower boundary, in standard ISO form, for an uncertain date.">notbefore</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains a lower boundary, in standard ISO form, for an uncertain date.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to record a pointer to the regularized form of the name elsewhere in the document.">nymref</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to record a pointer to the regularized form of the name elsewhere in the
                        document.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to specify further information about the entity referenced by this name, for example, the occupation of a person or the status of a place.">role</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to specify further information about the entity referenced by this name, for
                        example, the occupation of a person or the status of a place.</span><span class="attributeValues">
                        Value is plain text.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains the starting point of a date range in standard ISO form.">startdate</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains the starting point of a date range in standard ISO form.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                        </span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox direct" title="direct childs">
                     <div class="classHeading"><label class="classLabel">direct childs</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to record a pointer to the regularized form of the name elsewhere in the document.">nymref</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to record a pointer to the regularized form of the name elsewhere in the
                              document.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to specify further information about the entity referenced by this name, for example, the occupation of a person or the status of a place.">role</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to specify further information about the entity referenced by this name, for
                              example, the occupation of a person or the status of a place.</span><span class="attributeValues">
                              Value is plain text.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.authorized">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.authorized.html">att.authorized</a></label><span class="classDesc">(MEI.shared) Attributes that describe the source of a controlled value.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="A name or label associated with a controlled vocabulary or other authoritative source for this element or its content.">auth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A name or label associated with a controlled vocabulary or other authoritative source
                              for this element or its content.</span><span class="attributeValues">
                              Value is plain text.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="A web-accessible location of the controlled vocabulary or other authoritative source of identification or definition for this element or its content. This attribute may contain a complete URI or a partial URI which is completed by the value of the codedval attribute.">auth.uri</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A web-accessible location of the controlled vocabulary or other authoritative source
                              of identification or definition for this element or its content. This attribute may
                              contain a complete URI or a partial URI which is completed by the value of the codedval
                              attribute.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                              </span></div>
                        <div class="classBox" title="att.canonical">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.canonical.html">att.canonical</a></label><span class="classDesc">(MEI.shared) Attributes that can be used to associate a representation such as a name
                                 or title with canonical information about the object being named or referenced.</span></div>
                           <div class="classContent">
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="auth auth.uri A value that represents or identifies other data. Often, it is a primary key in the database or a unique value in the coded list identified by the or attributes.">codedval</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A value that represents or identifies other data. Often, it is a primary key in the
                                    database or a unique value in the coded list identified by the <span class="att">auth</span> or
                                    <span class="att">auth.uri</span> attributes.</span><span class="attributeValues">
                                    One or more values of datatype <span style="font-weight: 500;">NMTOKEN</span>, separated by spaces.
                                    </span></div>
                           </div>
                        </div>
                     </div>
                  </div>
                  <div class="classBox" title="att.datable">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.datable.html">att.datable</a></label><span class="classDesc">(MEI.shared) Attributes common to dates.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains the end point of a date range in standard ISO form.">enddate</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains the end point of a date range in standard ISO form.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Provides the value of a textual date in standard ISO form.">isodate</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Provides the value of a textual date in standard ISO form.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains an upper boundary for an uncertain date in standard ISO form.">notafter</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains an upper boundary for an uncertain date in standard ISO form.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains a lower boundary, in standard ISO form, for an uncertain date.">notbefore</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains a lower boundary, in standard ISO form, for an uncertain date.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains the starting point of a date range in standard ISO form.">startdate</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains the starting point of a date range in standard ISO form.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.filing">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.filing.html">att.filing</a></label><span class="classDesc">(MEI.shared) Attributes that deal with string filing characteristics.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the number of initial characters (such as those constituting an article or preposition) that should not be used for sorting a title or name.">nonfiling</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the number of initial characters (such as those constituting an article or
                              preposition) that should not be used for sorting a title or name.</span><span class="attributeValues">
                              Value is a positive integer.
                              </span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc">Component declarations that are shared between two or more modules.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="A name or label associated with a controlled vocabulary or other authoritative source for this element or its content.">auth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A name or label associated with a controlled vocabulary or other authoritative source
                              for this element or its content.</span><span class="attributeValues">
                              Value is plain text.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="A web-accessible location of the controlled vocabulary or other authoritative source of identification or definition for this element or its content. This attribute may contain a complete URI or a partial URI which is completed by the value of the codedval attribute.">auth.uri</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A web-accessible location of the controlled vocabulary or other authoritative source
                              of identification or definition for this element or its content. This attribute may
                              contain a complete URI or a partial URI which is completed by the value of the codedval
                              attribute.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="auth auth.uri A value that represents or identifies other data. Often, it is a primary key in the database or a unique value in the coded list identified by the or attributes.">codedval</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A value that represents or identifies other data. Often, it is a primary key in the
                              database or a unique value in the coded list identified by the <span class="att">auth</span> or
                              <span class="att">auth.uri</span> attributes.</span><span class="attributeValues">
                              One or more values of datatype <span style="font-weight: 500;">NMTOKEN</span>, separated by spaces.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains the end point of a date range in standard ISO form.">enddate</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains the end point of a date range in standard ISO form.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Provides the value of a textual date in standard ISO form.">isodate</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Provides the value of a textual date in standard ISO form.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the number of initial characters (such as those constituting an article or preposition) that should not be used for sorting a title or name.">nonfiling</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the number of initial characters (such as those constituting an article or
                              preposition) that should not be used for sorting a title or name.</span><span class="attributeValues">
                              Value is a positive integer.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains an upper boundary for an uncertain date in standard ISO form.">notafter</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains an upper boundary for an uncertain date in standard ISO form.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains a lower boundary, in standard ISO form, for an uncertain date.">notbefore</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains a lower boundary, in standard ISO form, for an uncertain date.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to record a pointer to the regularized form of the name elsewhere in the document.">nymref</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to record a pointer to the regularized form of the name elsewhere in the
                              document.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to specify further information about the entity referenced by this name, for example, the occupation of a person or the status of a place.">role</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to specify further information about the entity referenced by this name, for
                              example, the occupation of a person or the status of a place.</span><span class="attributeValues">
                              Value is plain text.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains the starting point of a date range in standard ISO form.">startdate</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains the starting point of a date range in standard ISO form.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isodate.html">data.ISODATE</a>.
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
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="(additional name) – Contains an additional name component, such as a nickname, epithet, or alias, or any other descriptive phrase used within a personal name."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/addname.html">addName</a></span>, <span class="ident element" title="Contains the name of a geopolitical unit consisting of two or more nation states or countries."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/bloc.html">bloc</a></span>, <span class="ident element" title="(corporate name) – Identifies an organization or group of people that acts as a single entity."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/corpname.html">corpName</a></span>, <span class="ident element" title="Contains the name of a geopolitical unit, such as a nation, country, colony, or commonwealth, larger than or administratively superior to a region and smaller than a bloc."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/country.html">country</a></span>, <span class="ident element" title="Contains the name of any kind of subdivision of a settlement, such as a parish, ward, or other administrative or geographic unit."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/district.html">district</a></span>, <span class="ident element" title="(family name) – Contains a family (inherited) name, as opposed to a given, baptismal, or nick name."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/famname.html">famName</a></span>, <span class="ident element" title="Contains a forename, given or baptismal name."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/forename.html">foreName</a></span>, <span class="ident element" title="(generational name component) – Contains a name component used to distinguish otherwise similar names on the basis of the relative ages or generations of the persons named."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/genname.html">genName</a></span>, <span class="ident element" title="(geographical feature name) – Contains a common noun identifying a geographical feature."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/geogfeat.html">geogFeat</a></span>, <span class="ident element" title="(geographic name) – The proper noun designation for a place, natural feature, or political jurisdiction."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/geogname.html">geogName</a></span>, <span class="ident element" title="Proper noun or noun phrase."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/name.html">name</a></span>, <span class="ident element" title="(name link) – Contains a connecting phrase or link used within a name but not regarded as part of it, such as &#34;van der&#34; or &#34;of&#34;, &#34;from&#34;, etc."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/namelink.html">nameLink</a></span>, <span class="ident element" title="(period name) – A label that describes a period of time, such as 'Baroque' or '3rd Style period'."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/periodname.html">periodName</a></span>, <span class="ident element" title="(personal name) – Designation for an individual, including any or all of that individual's forenames, surnames, honorific titles, and added names."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/persname.html">persName</a></span>, <span class="ident element" title="Contains the name of an administrative unit such as a state, province, or county, larger than a settlement, but smaller than a country."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/region.html">region</a></span>, <span class="ident element" title="Institution, agency, or individual which holds a bibliographic item."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/repository.html">repository</a></span>, <span class="ident element" title="(role name) – Contains a name component which indicates that the referent has a particular role or position in society, such as an official title or rank."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/rolename.html">roleName</a></span>, <span class="ident element" title="Contains the name of a settlement such as a city, town, or village identified as a single geopolitical or administrative unit."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/settlement.html">settlement</a></span>, <span class="ident element" title="(style name) – A label for a characteristic style of writing or performance, such as 'bebop' or 'rock-n-roll'."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/stylename.html">styleName</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.name">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.name.html">att.name</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/addname.html">addName</a><span class="elementDesc">(additional name) – Contains an additional name component, such as a nickname, epithet,
                              or
                              alias, or any other descriptive phrase used within a personal name.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/bloc.html">bloc</a><span class="elementDesc">Contains the name of a geopolitical unit consisting of two or more nation states or
                              countries.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/corpname.html">corpName</a><span class="elementDesc">(corporate name) – Identifies an organization or group of people that acts as a single
                              entity.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/country.html">country</a><span class="elementDesc">Contains the name of a geopolitical unit, such as a nation, country, colony, or
                              commonwealth, larger than or administratively superior to a region and smaller than
                              a
                              bloc.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/district.html">district</a><span class="elementDesc">Contains the name of any kind of subdivision of a settlement, such as a parish, ward,
                              or
                              other administrative or geographic unit.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/famname.html">famName</a><span class="elementDesc">(family name) – Contains a family (inherited) name, as opposed to a given, baptismal,
                              or
                              nick name.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/forename.html">foreName</a><span class="elementDesc">Contains a forename, given or baptismal name.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/genname.html">genName</a><span class="elementDesc">(generational name component) – Contains a name component used to distinguish otherwise
                              similar names on the basis of the relative ages or generations of the persons named.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/geogfeat.html">geogFeat</a><span class="elementDesc">(geographical feature name) – Contains a common noun identifying a geographical
                              feature.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/geogname.html">geogName</a><span class="elementDesc">(geographic name) – The proper noun designation for a place, natural feature, or political
                              jurisdiction.</span></div>
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/name.html">name</a><span class="elementDesc">Proper noun or noun phrase.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/namelink.html">nameLink</a><span class="elementDesc">(name link) – Contains a connecting phrase or link used within a name but not regarded
                              as
                              part of it, such as "van der" or "of", "from", etc.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/periodname.html">periodName</a><span class="elementDesc">(period name) – A label that describes a period of time, such as 'Baroque' or '3rd
                              Style
                              period'.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/persname.html">persName</a><span class="elementDesc">(personal name) – Designation for an individual, including any or all of that individual's
                              forenames, surnames, honorific titles, and added names.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/region.html">region</a><span class="elementDesc">Contains the name of an administrative unit such as a state, province, or county,
                              larger
                              than a settlement, but smaller than a country.</span></div>
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/repository.html">repository</a><span class="elementDesc">Institution, agency, or individual which holds a bibliographic item.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/rolename.html">roleName</a><span class="elementDesc">(role name) – Contains a name component which indicates that the referent has a particular
                              role or position in society, such as an official title or rank.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/settlement.html">settlement</a><span class="elementDesc">Contains the name of a settlement such as a city, town, or village identified as a
                              single
                              geopolitical or administrative unit.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/stylename.html">styleName</a><span class="elementDesc">(style name) – A label for a characteristic style of writing or performance, such
                              as
                              'bebop' or 'rock-n-roll'.</span></div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.namesdates">
                     <div class="classHeading"><label class="classLabel">MEI.namesdates</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/addname.html">addName</a><span class="elementDesc">(additional name) – Contains an additional name component, such as a nickname, epithet,
                              or
                              alias, or any other descriptive phrase used within a personal name.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/bloc.html">bloc</a><span class="elementDesc">Contains the name of a geopolitical unit consisting of two or more nation states or
                              countries.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/corpname.html">corpName</a><span class="elementDesc">(corporate name) – Identifies an organization or group of people that acts as a single
                              entity.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/country.html">country</a><span class="elementDesc">Contains the name of a geopolitical unit, such as a nation, country, colony, or
                              commonwealth, larger than or administratively superior to a region and smaller than
                              a
                              bloc.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/district.html">district</a><span class="elementDesc">Contains the name of any kind of subdivision of a settlement, such as a parish, ward,
                              or
                              other administrative or geographic unit.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/famname.html">famName</a><span class="elementDesc">(family name) – Contains a family (inherited) name, as opposed to a given, baptismal,
                              or
                              nick name.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/forename.html">foreName</a><span class="elementDesc">Contains a forename, given or baptismal name.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/genname.html">genName</a><span class="elementDesc">(generational name component) – Contains a name component used to distinguish otherwise
                              similar names on the basis of the relative ages or generations of the persons named.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/geogfeat.html">geogFeat</a><span class="elementDesc">(geographical feature name) – Contains a common noun identifying a geographical
                              feature.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/geogname.html">geogName</a><span class="elementDesc">(geographic name) – The proper noun designation for a place, natural feature, or political
                              jurisdiction.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/namelink.html">nameLink</a><span class="elementDesc">(name link) – Contains a connecting phrase or link used within a name but not regarded
                              as
                              part of it, such as "van der" or "of", "from", etc.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/periodname.html">periodName</a><span class="elementDesc">(period name) – A label that describes a period of time, such as 'Baroque' or '3rd
                              Style
                              period'.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/persname.html">persName</a><span class="elementDesc">(personal name) – Designation for an individual, including any or all of that individual's
                              forenames, surnames, honorific titles, and added names.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/region.html">region</a><span class="elementDesc">Contains the name of an administrative unit such as a state, province, or county,
                              larger
                              than a settlement, but smaller than a country.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/rolename.html">roleName</a><span class="elementDesc">(role name) – Contains a name component which indicates that the referent has a particular
                              role or position in society, such as an official title or rank.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/settlement.html">settlement</a><span class="elementDesc">Contains the name of a settlement such as a city, town, or village identified as a
                              single
                              geopolitical or administrative unit.</span></div>
                        <div class="elementRef" data-module="MEI.namesdates"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/stylename.html">styleName</a><span class="elementDesc">(style name) – A label for a characteristic style of writing or performance, such
                              as
                              'bebop' or 'rock-n-roll'.</span></div>
                     </div>
                  </div>
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/name.html">name</a><span class="elementDesc">Proper noun or noun phrase.</span></div>
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/repository.html">repository</a><span class="elementDesc">Institution, agency, or individual which holds a bibliographic item.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet constraints" id="constraints">
            <div class="label">Constraints</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="text" id="constraints_text_tab" href="#constraints" class="displayTab active">text</a></li>
                  <li class="tab-item"><a data-display="schematron" id="constraints_schematron_tab" href="#constraints" class="displayTab">schematron</a></li>
               </ul>
               <div id="constraints_tabbedContent_text" class="facetTabbedContent text active">
                  <div class="constraint">
                     <div class="schematronText">@nymref attribute should have content.</div>
                     <div class="schematronText">The value in @nymref should correspond to the @xml:id attribute of an element.</div>
                  </div>
               </div>
               <div id="constraints_tabbedContent_schematron" class="facetTabbedContent schematron">
                  <div class="constraint">
                     <div class="code" xml:space="preserve" data-lang="Schematron"><code>
                           <div class="indent1 indent"><span data-indentation="1" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"@nymref"</span>&gt;</span>
                              
                              <div class="indent2 indent"><span data-indentation="2" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"not(normalize-space(.) eq '')"</span>&gt;</span>@nymref attribute
                                 should have content.<span data-indentation="2" class="element">&lt;/sch:assert&gt;</span></div>
                              
                              <div class="indent2 indent"><span data-indentation="2" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"every $i in tokenize(., '\s+') satisfies substring($i,2)=//mei:*/@xml:id"</span>&gt;</span>The
                                 value in @nymref should correspond to the @xml:id attribute of an
                                 element.<span data-indentation="2" class="element">&lt;/sch:assert&gt;</span></div>
                              <span data-indentation="1" class="element">&lt;/sch:rule&gt;</span></div></code></div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.name"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.shared"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Attributes shared by names.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;classes&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.authorized.html">att.authorized</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.datable.html">att.datable</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.filing.html">att.filing</a>"</span></span>/&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/classes&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;attList&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"nymref"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>Used to record a pointer to the regularized form of the name elsewhere in the
                                 document.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;datatype&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:ref
                                       
                                       <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>"</span></span>
                                       /&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/datatype&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;constraintSpec <span class="attribute">ident=</span><span class="attributevalue">"check_nymrefTarget"</span> <span class="attribute">scheme=</span><span class="attributevalue">"isoschematron"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;constraint&gt;</span>
                                    
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"@nymref"</span>&gt;</span>
                                       
                                       <div class="indent7 indent"><span data-indentation="7" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"not(normalize-space(.) eq '')"</span>&gt;</span>@nymref attribute
                                          should have content.<span data-indentation="7" class="element">&lt;/sch:assert&gt;</span></div>
                                       
                                       <div class="indent7 indent"><span data-indentation="7" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"every $i in tokenize(., '\s+') satisfies substring($i,2)=//mei:*/@xml:id"</span>&gt;</span>The
                                          value in @nymref should correspond to the @xml:id attribute of an
                                          element.<span data-indentation="7" class="element">&lt;/sch:assert&gt;</span></div>
                                       <span data-indentation="6" class="element">&lt;/sch:rule&gt;</span></div>
                                    <span data-indentation="5" class="element">&lt;/constraint&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/constraintSpec&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/attDef&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"role"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>Used to specify further information about the entity referenced by this name, for
                                 example, the occupation of a person or the status of a place.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;datatype&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:text/&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/datatype&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;remarks&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;p&gt;</span>When applicable, values from the MARC relator term list (
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;ref <span class="attribute">target=</span><span class="attributevalue">"http://www.loc.gov/marc/relators/relaterm.html"</span>&gt;</span>http://www.loc.gov/marc/relators/relaterm.html<span data-indentation="6" class="element">&lt;/ref&gt;</span></div>) or code list (
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;ref <span class="attribute">target=</span><span class="attributevalue">"http://www.loc.gov/marc/relators/relacode.html"</span>&gt;</span>http://www.loc.gov/marc/relators/relacode.html<span data-indentation="6" class="element">&lt;/ref&gt;</span></div>) are recommended for
                                    
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;att&gt;</span>role<span data-indentation="6" class="element">&lt;/att&gt;</span></div>.<span data-indentation="5" class="element">&lt;/p&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/remarks&gt;</span></div>
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