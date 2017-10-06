---
layout: sidebar
sidebar: s1
title: "Common Music Notation"
sectionid: "cmn"
---

<span class="div">
   
   <h1 id="cmn">
      <span class="headingNumber">4</span>
      <span class="head">Common Music Notation</span>
   </h1>
   The module described in this chapter offers the means to describe music in so-called
   ‘Common Music Notation’ (CMN, sometimes referred to as
   ‘Common Western Music Notation’). For this purpose, it provides a number of
   special elements and adds several attribute classes to elements from the 
   <span class="ref">Shared</span> module.
   
   
   
   
   <!--<div type="div2" xml:id="cmnOriginalContent">
    <head>Overview of the CMN Module</head>
    <p>The module described in this chapter makes available the following components:</p>
    <!-\-<div type="div3" xml:id="cmnElements">
      <head>Elements</head>
      <p>
        <specList>
          <specDesc key="_arpeg"/>
          <specDesc key="_beam"/>
          <specDesc key="_beamSpan"/>
          <specDesc key="_beatRpt"/>
          <specDesc key="_bend"/>
          <specDesc key="_breath"/>
          <specDesc key="_bTrem"/>
          <specDesc key="_fermata"/>
          <specDesc key="_fTrem"/>
          <specDesc key="_hairpin"/>
          <specDesc key="_harpPedal"/>
          <specDesc key="_gliss"/>
          <specDesc key="_halfmRpt"/>
          <specDesc key="_measure"/>
          <specDesc key="_mRest"/>
          <specDesc key="_mRpt"/>
          <specDesc key="_mRpt2"/>
          <specDesc key="_mSpace"/>
          <specDesc key="_multiRest"/>
          <specDesc key="_multiRpt"/>
          <specDesc key="_octave"/>
          <specDesc key="_ossia"/>
          <specDesc key="_pedal"/>
          <specDesc key="_reh"/>
          <specDesc key="_slur"/>
          <specDesc key="_tie"/>
          <specDesc key="_tuplet"/>
          <specDesc key="_tupletSpan"/>
        </specList>
     </p>
    </div>-\->
    <div type="div3" xml:id="cmnAttributeClasses">
      <head>Attribute Classes</head>
      <p>
        <specList>
          <specDesc key="att.arpeg.anl"/>
          <specDesc key="att.arpeg.ges"/>
          <specDesc key="att.arpeg.log"/>
          <specDesc key="att.arpeg.vis"/>
          <specDesc key="att.beam.anl"/>
          <specDesc key="att.beam.ges"/>
          <specDesc key="att.beam.log"/>
          <specDesc key="att.beam.vis"/>
          <specDesc key="att.beamed"/>
          <specDesc key="att.beamedwith"/>
          <specDesc key="att.beaming.log"/>
          <specDesc key="att.beamrend"/>
          <specDesc key="att.beamsecondary"/>
          <specDesc key="att.beamSpan.anl"/>
          <specDesc key="att.beamSpan.ges"/>
          <specDesc key="att.beamSpan.log"/>
          <specDesc key="att.beamSpan.vis"/>
          <specDesc key="att.beatRpt.anl"/>
          <specDesc key="att.beatRpt.ges"/>
          <specDesc key="att.beatRpt.log"/>
          <specDesc key="att.beatRpt.vis"/>
          <specDesc key="att.bend.anl"/>
          <specDesc key="att.bend.ges"/>
          <specDesc key="att.bend.log"/>
          <specDesc key="att.bend.vis"/>
          <specDesc key="att.breath.anl"/>
          <specDesc key="att.breath.ges"/>
          <specDesc key="att.breath.log"/>
          <specDesc key="att.breath.vis"/>
          <specDesc key="att.bTrem.anl"/>
          <specDesc key="att.bTrem.ges"/>
          <specDesc key="att.bTrem.log"/>
          <specDesc key="att.bTrem.vis"/>
          <specDesc key="att.chord.ges.cmn"/>
          <specDesc key="att.chord.log.cmn"/>
          <specDesc key="att.chord.vis.cmn"/>
          <specDesc key="att.cutout"/>
          <specDesc key="att.expandable"/>
          <specDesc key="att.fermata.anl"/>
          <specDesc key="att.fermata.ges"/>
          <specDesc key="att.fermata.log"/>
          <specDesc key="att.fermata.vis"/>
          <specDesc key="att.fTrem.anl"/>
          <specDesc key="att.fTrem.ges"/>
          <specDesc key="att.fTrem.log"/>
          <specDesc key="att.fTrem.vis"/>
          <specDesc key="att.gliss.anl"/>
          <specDesc key="att.gliss.ges"/>
          <specDesc key="att.gliss.log"/>
          <specDesc key="att.gliss.vis"/>
          <specDesc key="att.graced"/>
          <specDesc key="att.hairpin.anl"/>
          <specDesc key="att.hairpin.ges"/>
          <specDesc key="att.hairpin.log"/>
          <specDesc key="att.hairpin.vis"/>
          <specDesc key="att.halfmRpt.anl"/>
          <specDesc key="att.halfmRpt.ges"/>
          <specDesc key="att.halfmRpt.log"/>
          <specDesc key="att.halfmRpt.vis"/>
          <specDesc key="att.harpPedal.anl"/>
          <specDesc key="att.harpPedal.ges"/>
          <specDesc key="att.harpPedal.log"/>
          <specDesc key="att.harpPedal.vis"/>
          <specDesc key="att.layerDef.log.cmn"/>
          <specDesc key="att.lvpresent"/>
          <specDesc key="att.measure.vis"/>
          <specDesc key="att.mRest.anl"/>
          <specDesc key="att.mRest.ges"/>
          <specDesc key="att.mRest.log"/>
          <specDesc key="att.mRest.vis"/>
          <specDesc key="att.mRpt.anl"/>
          <specDesc key="att.mRpt.ges"/>
          <specDesc key="att.mRpt.log"/>
          <specDesc key="att.mRpt.vis"/>
          <specDesc key="att.mRpt2.anl"/>
          <specDesc key="att.mRpt2.ges"/>
          <specDesc key="att.mRpt2.log"/>
          <specDesc key="att.mRpt2.vis"/>
          <specDesc key="att.mSpace.anl"/>
          <specDesc key="att.mSpace.ges"/>
          <specDesc key="att.mSpace.log"/>
          <specDesc key="att.mSpace.vis"/>
          <specDesc key="att.multiRest.anl"/>
          <specDesc key="att.multiRest.ges"/>
          <specDesc key="att.multiRest.log"/>
          <specDesc key="att.multiRest.vis"/>
          <specDesc key="att.multiRpt.anl"/>
          <specDesc key="att.multiRpt.ges"/>
          <specDesc key="att.multiRpt.log"/>
          <specDesc key="att.multiRpt.vis"/>
          <specDesc key="att.note.ges.cmn"/>
          <specDesc key="att.note.log.cmn"/>
          <specDesc key="att.note.vis.cmn"/>
          <specDesc key="att.numbered"/>
          <specDesc key="att.numberplacement"/>
          <specDesc key="att.octave.anl"/>
          <specDesc key="att.octave.ges"/>
          <specDesc key="att.octave.log"/>
          <specDesc key="att.octave.vis"/>
          <specDesc key="att.ornamentaccid"/>
          <specDesc key="att.ossia.anl"/>
          <specDesc key="att.ossia.ges"/>
          <specDesc key="att.ossia.log"/>
          <specDesc key="att.ossia.vis"/>
          <specDesc key="att.pedal.anl"/>
          <specDesc key="att.pedal.ges"/>
          <specDesc key="att.pedal.log"/>
          <specDesc key="att.pedal.vis"/>
          <specDesc key="att.phrase.vis.cmn"/>
          <specDesc key="att.pianopedals"/>
          <specDesc key="att.reh.anl"/>
          <specDesc key="att.reh.ges"/>
          <specDesc key="att.reh.log"/>
          <specDesc key="att.reh.vis"/>
          <specDesc key="att.rehearsal"/>
          <specDesc key="att.rest.log.cmn"/>
          <specDesc key="att.rest.vis.cmn"/>
          <specDesc key="att.scoreDef.log.cmn"/>
          <specDesc key="att.scoreDef.vis.cmn"/>
          <specDesc key="att.slur.anl"/>
          <specDesc key="att.slur.ges"/>
          <specDesc key="att.slur.log"/>
          <specDesc key="att.slur.vis"/>
          <specDesc key="att.slurrend"/>
          <specDesc key="att.space.log.cmn"/>
          <specDesc key="att.staffDef.log.cmn"/>
          <specDesc key="att.staffDef.vis.cmn"/>
          <specDesc key="att.stemmed.cmn"/>
          <specDesc key="att.tie.anl"/>
          <specDesc key="att.tie.ges"/>
          <specDesc key="att.tie.log"/>
          <specDesc key="att.tie.vis"/>
          <specDesc key="att.tierend"/>
          <specDesc key="att.tuplet.anl"/>
          <specDesc key="att.tuplet.ges"/>
          <specDesc key="att.tuplet.log"/>
          <specDesc key="att.tuplet.vis"/>
          <specDesc key="att.tupletSpan.anl"/>
          <specDesc key="att.tupletSpan.ges"/>
          <specDesc key="att.tupletSpan.log"/>
          <specDesc key="att.tupletSpan.vis"/>
        </specList>
     </p>
    </div>
    <div type="div3" xml:id="cmnModelClasses">
      <head>Model Classes</head>
      <p>
        <specList>
          <specDesc key="model.controleventLike.cmn"/>
          <specDesc key="model.eventLike.cmn"/>
          <specDesc key="model.eventLike.measureFilling"/>
          <specDesc key="model.layerPart.cmn"/>
          <specDesc key="model.measureLike"/>
          <specDesc key="model.measurePart"/>
          <specDesc key="model.ossiaLike"/>
          <specDesc key="model.sectionPart.cmn"/>
        </specList>
     </p>
    </div>
  </div>-->
   
</span>