---
sectionid: namesdatesBasic
title: "Basic Elements for Names and Dates"
version: "v3"
---

The basic elements for capturing names and dates are defined in the shared module:



{% include desc elem="name" %}
{% include desc elem="date" %}




The {% include link elem="name" %} element contains the name of an entity that is difficult to
tag more specifically as a {% include link elem="corpname" %}, {% include link elem="geogname" %}, {% include link elem="persname" %}, or {% include link elem="title" %}. In section {% include link id="sharednamesnumbersdates" %} it was noted that the {% include link elem="name" %} element
may be used in place of the more specific elements when it is not known what kind
of name is
being described or when a high degree of precision is not necessary. For example,
the {% include link elem="name" %} element might be used when it is not clear whether the name "Bach"
refers to a person or a geographic feature. When name parts are needed, use {% include link elem="name" %} sub-elements. The recommended values for the **@type** attribute are:

<table class="table table-striped">
   <thead>
      <tr>
         <th>Value</th>
         <th>Description</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>'pers'</td>
         <td> - a personal name</td>
      </tr>
      <tr>
         <td>'corp'</td>
         <td> - the name of a corporate entity</td>
      </tr>
      <tr>
         <td>'place'</td>
         <td> - a geographic name</td>
      </tr>
      <tr>
         <td>'process'</td>
         <td> - the name of a process or mechanical agent</td>
      </tr>
   </tbody>
</table>The date sub-element is available within {% include link elem="name" %} in order to record any
dates associated with the name, for example, creation and dissolution in the case
of a
corporate entity or place or birth and death dates in the case of an individual. The
name of
the list from which a controlled value is taken, such as the Library of Congress Name
Authority File (LCNAF), may be recorded using the authority attribute.

Examples of the use of the {% include link elem="name" %} element:

{% include plainExample.html example="examples/namesdates/namesdates-sample276.xml" valid="false" version=page.version %}
The element {% include link elem="date" %} contains a date in any format, including a date range.
A date range may be expressed as textual content or, when intervening punctuation
is present,
as a combination of date sub-elements and text.

{% include plainExample.html example="examples/namesdates/namesdates-sample277.xml" valid="false" version=page.version %}
To be more specific about the date, the attributes in the {% include link att-class="att.datable" %} class can be used:


<table class="table table-striped">
   <thead>
      <tr>
         <th>Value</th>
         <th>Description</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td><span class="att">startdate</span></td>
         <td> - contains the starting point of a date range in standard ISO form</td>
      </tr>
      <tr>
         <td><span class="att">enddate</span></td>
         <td> - contains the end point of a date range in standard ISO form</td>
      </tr>
      <tr>
         <td><span class="att">notbefore</span></td>
         <td> - contains a lower boundary for an uncertain date</td>
      </tr>
      <tr>
         <td><span class="att">notafter</span></td>
         <td> - contains an upper boundary for an uncertain date</td>
      </tr>
      <tr>
         <td><span class="att">isodate</span></td>
         <td> - gives the value of a textual date in standard ISO form</td>
      </tr>
      <tr>
         <td><span class="att">calendar</span></td>
         <td> - indicates the system or calendar to which a date belongs, for example, Gregorian,
            Julian, Roman, Mosaic, Revolutionary, Islamic, etc.
         </td>
      </tr>
      <tr>
         <td><span class="att">cert</span></td>
         <td> - signifies the degree of certainty or precision associated with a feature (high,
            medium, low, unknown)
         </td>
      </tr>
   </tbody>
</table>In the following example, the ambiguous date text "5/3/05" is resolved using the
**@isodate** attribute:

{% include plainExample.html example="examples/namesdates/namesdates-sample278.xml" valid="false" version=page.version %}