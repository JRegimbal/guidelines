---
layout: sidebar
sidebar: s1
title: "hairpin"

---

<div class="elementSpec">
   <h3 id="hairpin">&lt;hairpin&gt;</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">&lt;hairpin&gt;</span> Indicates continuous dynamics expressed on the score as wedge-shaped graphics, e.g.
            &lt;
            and &gt;.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI.cmn</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Attributes</span>
         </td>
         <td class="wovenodd-col2">
            <div class="attributeDef">
               <span class="attribute">@color</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to indicate visual appearance. Do not confuse this with the musical term
                  'color' as used in pre-CMN notation.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.COLOR">data.COLOR</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.color">att.color</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@copyof</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to an element of which the current element is a copy.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@corresp</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to point to other elements that correspond to this one in a generic
                  fashion.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@dots</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records the number of augmentation dots required by a dotted duration.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.AUGMENTDOT">data.AUGMENTDOT</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.augmentdots">att.augmentdots</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@dur</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records duration using optionally dotted, relative durational values provided by the
                  data.DURATION datatype. When the duration is "irrational", as is sometimes the case
                  with
                  tuplets, multiple space-separated values that add up to the total duration may be
                  used.
                  When dotted values are present, the dots attribute must be ignored.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/v3/data.DURATION.additive">data.DURATION.additive</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.duration.additive">att.duration.additive</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@dur.ges</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records performed duration information that differs from the written duration. Its
                  value may be expressed in several forms; that is, ppq (MIDI clicks and MusicXML
                  'divisions'), Humdrum **recip values, beats, seconds, or mensural duration
                  values.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.DURATION.gestural">data.DURATION.gestural</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.duration.performed">att.duration.performed</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@endho</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records the horizontal adjustment of a feature's programmatically-determined end
                  point.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.MEASUREMENTREL">data.MEASUREMENTREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.visualoffset2.ho">att.visualoffset2.ho</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@endid</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the final element in a sequence of events to which the feature
                  applies.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.startendid">att.startendid</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@endto</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records a timestamp adjustment of a feature's programmatically-determined end
                  point.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.TSTAMPOFFSET">data.TSTAMPOFFSET</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.visualoffset2.to">att.visualoffset2.to</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@endvo</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records a vertical adjustment of a feature's programmatically-determined end
                  point.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.MEASUREMENTREL">data.MEASUREMENTREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.visualoffset2.vo">att.visualoffset2.vo</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@evaluate</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Specifies the intended meaning when a participant in a relationship is itself a
                  pointer.
               </span>
               Allowed values are:
               "
               <span style="font-weight: 500;">all</span>" 
               <i>(If an element pointed to is itself a pointer, then the target of that pointer
                  will be taken, and so on, until an element is found which is not a pointer.)
               </i>,  "
               <span style="font-weight: 500;">one</span>" 
               <i>(If an element pointed to is itself a pointer, then its target (whether a pointer
                  or not) is taken as the target of this pointer.)
               </i>,  "
               <span style="font-weight: 500;">none</span>" 
               <i>(No further evaluation of targets is carried out beyond that needed to find the
                  element(s) specified in plist or target attribute.)
               </i>
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.targeteval">att.targeteval</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@facs</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Permits the current element to reference a facsimile surface or image zone which
                  corresponds to it.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.facsimile">att.facsimile</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@form</span>
               <span class="attributeUsage">(required)</span>
               <span class="attributeDesc">Captures the visual rendition and function of the hairpin; that is, whether it
                  indicates an increase or a decrease in volume.
               </span>
               Allowed values are:
               "
               <span style="font-weight: 500;">cres</span>" 
               <i>(Crescendo; i.e., louder.)</i>,  "
               <span style="font-weight: 500;">dim</span>" 
               <i>(Diminuendo; i.e., softer.)</i>
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.hairpin.log">att.hairpin.log</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@ho</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records a horizontal adjustment to a feature's programmatically-determined location
                  in terms of staff interline distance; that is, in units of 1/2 the distance between
                  adjacent staff lines.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.MEASUREMENTREL">data.MEASUREMENTREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.visualoffset.ho">att.visualoffset.ho</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@label</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a name or label for an element. The value may be any string.</span>
               Value of datatype 
               <span style="font-weight: 500;">string</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.commonPart">att.commonPart</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@layer</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Identifies the layer to which a feature applies.</span>
               One or more values of datatype 
               <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.layerident">att.layerident</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@lform</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Describes the line style of a line.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.LINEFORM">data.LINEFORM</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.linerend.base">att.linerend.base</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@lwidth</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Width of a line.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.LINEWIDTH">data.LINEWIDTH</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.linerend.base">att.linerend.base</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@n</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a number-like designation for an element.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/token">token</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.common">att.common</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@next</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to point to the next event(s) in a user-defined collection.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@niente</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates that the hairpin starts from or ends in silence. Often rendered as a small
                  circle attached to the closed end of the hairpin. See Gould, p. 108.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.BOOLEAN">data.BOOLEAN</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.hairpin.log">att.hairpin.log</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@opening</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Specifies the distance between the lines at the open end of a hairpin dynamic
                  mark.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.MEASUREMENTABS">data.MEASUREMENTABS</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.hairpin.vis">att.hairpin.vis</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@place</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Captures the placement of the item with respect to the staff with which it is
                  associated.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.STAFFREL">data.STAFFREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.placement">att.placement</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@plist</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Contains a space separated list of references that identify active participants in
                  a
                  collection/relationship, such as notes under a phrase mark; that is, the entities
                  pointed "from".
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.plist">att.plist</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@prev</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to the previous event(s) in a user-defined collection.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@sameas</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to an element that is the same as the current element but is not a literal
                  copy of the current element.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@staff</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Signifies the staff on which a notated event occurs or to which a control event
                  applies. Mandatory when applicable.
               </span>
               One or more values of datatype 
               <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.staffident">att.staffident</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@startho</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records the horizontal adjustment of a feature's programmatically-determined start
                  point.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.MEASUREMENTREL">data.MEASUREMENTREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.visualoffset2.ho">att.visualoffset2.ho</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@startid</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Holds a reference to the first element in a sequence of events to which the feature
                  applies.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.startid">att.startid</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@startto</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records a timestamp adjustment of a feature's programmatically-determined start
                  point.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.TSTAMPOFFSET">data.TSTAMPOFFSET</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.visualoffset2.to">att.visualoffset2.to</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@startvo</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records a vertical adjustment of a feature's programmatically-determined start
                  point.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.MEASUREMENTREL">data.MEASUREMENTREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.visualoffset2.vo">att.visualoffset2.vo</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@subtype</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provide any sub-classification for the element, additional to that given by its type
                  attribute.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">NMTOKEN</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.typed">att.typed</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@synch</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to elements that are synchronous with the current element.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@to</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records a timestamp adjustment of a feature's programmatically-determined location
                  in terms of musical time; that is, beats.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.TSTAMPOFFSET">data.TSTAMPOFFSET</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.visualoffset.to">att.visualoffset.to</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@tstamp</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Encodes the onset time in terms of musical time, i.e.,
                  beats[.fractional_beat_part].
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.BEAT">data.BEAT</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.timestamp.musical">att.timestamp.musical</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@tstamp.ges</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Captures performed onset time in several forms; that is, ppq (MIDI clicks and
                  MusicXML 'divisions'), Humdrum **recip values, beats, seconds, or mensural duration
                  values.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.DURATION.gestural">data.DURATION.gestural</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.timestamp.performed">att.timestamp.performed</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@tstamp.real</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to record the onset time in terms of ISO time.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.ISOTIME">data.ISOTIME</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.timestamp.performed">att.timestamp.performed</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@tstamp2</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Encodes the ending point of an event in terms of musical time, i.e., a count of
                  measures plus a beat location.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.MEASUREBEAT">data.MEASUREBEAT</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.timestamp2.musical">att.timestamp2.musical</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@type</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Characterizes the element in some sense, using any convenient classification scheme
                  or typology.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">NMTOKEN</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.typed">att.typed</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@val</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">MIDI number.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.MIDIVALUE">data.MIDIVALUE</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.midivalue">att.midivalue</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@val2</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">MIDI number.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.MIDIVALUE">data.MIDIVALUE</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.midivalue2">att.midivalue2</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@vo</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records the vertical adjustment of a feature's programmatically-determined location
                  in terms of staff interline distance; that is, in units of 1/2 the distance between
                  adjacent staff lines.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.MEASUREMENTREL">data.MEASUREMENTREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.visualoffset.vo">att.visualoffset.vo</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@when</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the point of occurrence of this feature along a time line. Its value must
                  be the ID of a 
                  <a class="link_odd_elementSpec" href="/v3/when">when</a> element elsewhere in the document.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.alignment">att.alignment</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@x</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Encodes an x coordinate for a feature in an output coordinate system. When it is
                  necessary to record the placement of a feature in a facsimile image, use the facs
                  attribute.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">decimal</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.xy">att.xy</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@x2</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Encodes the optional 2nd x coordinate.</span>
               Value of datatype 
               <span style="font-weight: 500;">decimal</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.xy2">att.xy2</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@xml:base</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a base URI reference with which applications can resolve relative URI
                  references into absolute URI references.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/v3/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.commonPart">att.commonPart</a>
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
                  <a class="link_odd" href="/v3/att.id">att.id</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@y</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Encodes an y coordinate for a feature in an output coordinate system. When it is
                  necessary to record the placement of a feature in a facsimile image, use the facs
                  attribute.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">decimal</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.xy">att.xy</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@y2</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Encodes the optional 2nd y coordinate.</span>
               Value of datatype 
               <span style="font-weight: 500;">decimal</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/v3/att.xy2">att.xy2</a>
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
               <a class="link_odd_classSpec" href="/v3/model.controleventLike.cmn">model.controleventLike.cmn</a>
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
                        <a class="link_odd_elementSpec" href="/v3/arpeg">arpeg</a> 
                        <a class="link_odd_elementSpec" href="/v3/beamSpan">beamSpan</a> 
                        <a class="link_odd_elementSpec" href="/v3/bend">bend</a> 
                        <a class="link_odd_elementSpec" href="/v3/breath">breath</a> 
                        <a class="link_odd_elementSpec" href="/v3/fermata">fermata</a> 
                        <a class="link_odd_elementSpec" href="/v3/gliss">gliss</a> 
                        <a class="link_odd_elementSpec" href="/v3/hairpin">hairpin</a> 
                        <a class="link_odd_elementSpec" href="/v3/harpPedal">harpPedal</a> 
                        <a class="link_odd_elementSpec" href="/v3/measure">measure</a> 
                        <a class="link_odd_elementSpec" href="/v3/octave">octave</a> 
                        <a class="link_odd_elementSpec" href="/v3/pedal">pedal</a> 
                        <a class="link_odd_elementSpec" href="/v3/reh">reh</a> 
                        <a class="link_odd_elementSpec" href="/v3/slur">slur</a> 
                        <a class="link_odd_elementSpec" href="/v3/tie">tie</a> 
                        <a class="link_odd_elementSpec" href="/v3/tupletSpan">tupletSpan</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.critapp</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/v3/lem">lem</a> 
                        <a class="link_odd_elementSpec" href="/v3/rdg">rdg</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.edittrans</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/v3/abbr">abbr</a> 
                        <a class="link_odd_elementSpec" href="/v3/add">add</a> 
                        <a class="link_odd_elementSpec" href="/v3/corr">corr</a> 
                        <a class="link_odd_elementSpec" href="/v3/cpMark">cpMark</a> 
                        <a class="link_odd_elementSpec" href="/v3/damage">damage</a> 
                        <a class="link_odd_elementSpec" href="/v3/del">del</a> 
                        <a class="link_odd_elementSpec" href="/v3/expan">expan</a> 
                        <a class="link_odd_elementSpec" href="/v3/orig">orig</a> 
                        <a class="link_odd_elementSpec" href="/v3/reg">reg</a> 
                        <a class="link_odd_elementSpec" href="/v3/restore">restore</a> 
                        <a class="link_odd_elementSpec" href="/v3/sic">sic</a> 
                        <a class="link_odd_elementSpec" href="/v3/supplied">supplied</a> 
                        <a class="link_odd_elementSpec" href="/v3/unclear">unclear</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.mensural</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/v3/ligature">ligature</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.neumes</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/v3/syllable">syllable</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.shared</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/v3/dir">dir</a> 
                        <a class="link_odd_elementSpec" href="/v3/dynam">dynam</a> 
                        <a class="link_odd_elementSpec" href="/v3/layer">layer</a> 
                        <a class="link_odd_elementSpec" href="/v3/ornam">ornam</a> 
                        <a class="link_odd_elementSpec" href="/v3/phrase">phrase</a> 
                        <a class="link_odd_elementSpec" href="/v3/tempo">tempo</a>
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
            <div class="specChild">
               <span class="specChildModule">Empty</span>
               <span class="specChildElements"></span>
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
                           <a class="link_odd" href="/att.common">att.common</a>"
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
                           <a class="link_odd" href="/att.hairpin.log">att.hairpin.log</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.hairpin.vis">att.hairpin.vis</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.hairpin.ges">att.hairpin.ges</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.hairpin.anl">att.hairpin.anl</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.typed">att.typed</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/model.controleventLike.cmn">model.controleventLike.cmn</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/classes&gt;</span>
               </div>
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;content&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;rng:empty/&gt;</span>
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
            <p>The 
               <a class="link_odd_elementSpec" href="/v3/hairpin">hairpin</a> element is used for 
               <em class="mentioned">graphical</em>, i.e.,
               crescendo and diminuendo, dynamic markings. For instantaneous or continuous
               
               <em class="mentioned">textual</em> dynamics, such as 'p', 'mf', or 'cres. poco a poco', the 
               <a class="link_odd_elementSpec" href="/v3/dynam">dynam</a> element should be used. The starting point of the hairpin
               marking may be indicated by either a 
               <span class="att">startid</span>, 
               <span class="att">tstamp</span>,
               
               <span class="att">tstamp.ges</span>, or 
               <span class="att">tstamp.real</span> attribute, while the ending point may
               be recorded by either a 
               <span class="att">dur</span>, 
               <span class="att">dur.ges</span>, 
               <span class="att">endid</span>, or
               
               <span class="att">tstamp2</span> attribute. It is a semantic error not to specify one starting and one
               ending type of attribute. MIDI values associated with the graphical dynamic sign may
               be
               recorded in the 
               <span class="att">val</span> and 
               <span class="att">val2</span> attributes.
            </p>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Constraints</span>
         </td>
         <td class="wovenodd-col2">
            <div>
               <div>Must have one of the attributes: startid, tstamp, tstamp.ges or tstamp.real.</div>
               <div>Must have one of the attributes: dur, dur.ges, endid, or tstamp2.</div>
            </div>
            <div xml:space="preserve" class="pre">
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;sch:rule 
                     <span class="attribute">context=</span>
                     <span class="attributevalue">"mei:hairpin"</span>&gt;
                  </span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;sch:assert 
                        <span class="attribute">test=</span>
                        <span class="attributevalue">"@startid or @tstamp or @tstamp.ges or @tstamp.real"</span>&gt;
                     </span>Must have one of
                     the attributes: startid, tstamp, tstamp.ges or tstamp.real.
                     <span data-indentation="2" class="element">&lt;/sch:assert&gt;</span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;sch:assert 
                        <span class="attribute">test=</span>
                        <span class="attributevalue">"@dur or @dur.ges or @endid or @tstamp2"</span>&gt;
                     </span>Must have one of the
                     attributes: dur, dur.ges, endid, or tstamp2.
                     <span data-indentation="2" class="element">&lt;/sch:assert&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/sch:rule&gt;</span>
               </div>
            </div>
         </td>
      </tr>
   </table>
</div>