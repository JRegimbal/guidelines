---
sectionid: sharedAddresses
title: "Addresses"
version: "v3"
---

Addresses may be encoded using the {% include link elem="address" %} element, which itself
may hold an arbitrary number of {% include link elem="addrline" %} elements.



{% include desc elem="address" %}
{% include desc elem="addrline" %}




It is important to note that the {% include link elem="address" %} element does not hold a
reference to the person or organization whose address is specified. This must be provided
in a separate element, as in the following example:

{% include plainExample.html example="examples/shared/shared-sample010.xml" valid="false" version=page.version %}