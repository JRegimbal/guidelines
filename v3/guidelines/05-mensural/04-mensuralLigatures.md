---
sectionid: mensuralLigatures
title: Ligatures
---


<h2 id="mensuralLigatures">
   <span class="headingNumber">5.4</span>
   <span class="head">Ligatures</span>
</h2>

Ligatures can be encoded using the 
<a class="link_odd_elementSpec" href="/v3/elements/ligature">ligature</a> element. The
**@form** attribute is available for specifying if the ligature is recta or
obliqua.



<figure class="figure">
   <img src="../../../../guidelines/3.0.0/Images/modules/mensural/ex_ligatures01.png" class="img-responsive"></img>
   <figcaption class="figure-caption">Figure 19. Recta and obliqua ligatures</figcaption>
</figure>


{% include _plainExample.html example="./v3/examples/mensural/mensural-sample156.xml" valid="false" %}


In cases where the ligature contains both recta and obliqua notes, the **@lig**
attribute of the 
<a class="link_odd_elementSpec" href="/v3/elements/note">note</a> element can be used to specify the form of the
ligature at the note level.



<figure class="figure">
   <img src="../../../../guidelines/3.0.0/Images/modules/mensural/ex_ligatures02.png" class="img-responsive"></img>
   <figcaption class="figure-caption">Figure 20. Ligature with more than two notes with recta and obliqua</figcaption>
</figure>


{% include _plainExample.html example="./v3/examples/mensural/mensural-sample157.xml" valid="true" %}



