# Title changes

When dealing with an enquiry relating to the title of an item in the Visual Collections, consider the existing title. Titles can be changed when one of the following issues apply:

* The item has a title which has not been used in the title field
* The title wrongly describes the subject of the item
* The wording used could be considered offensive, outdated, not inclusive
* The title is subjective
* The title does not comply with Wellcome Collection [Visual Cataloguing Framework](https://docs.wellcomecollection.org/visual-material/metadata-framework/metadata-elements/title-brief-description).

If the title needs to be changed use the following procedure:

* Copy the old title to a 246 field, using the following format:

{% hint style="info" %}
**246 1\_ |i**Previous title, replaced _DATE (Month Year)_**|a**_Previous title_.**|5**UkLW

e.g. [535948i](https://wellcomecollection.org/works/u4hc2hwe) \
**246 1\_ |i**Previous title, replaced May 2022:**|a**A medical missionary attending to a sick African. Oil painting by Harold Copping, 1916.**|5**UkLW
{% endhint %}

* Edit the existing 245 title field so it contains the new title.
* Check the first and second MARC indicators (numbers following the main field number):
  * If the record contains a 100/110 entry the first indicator should be 1, if there is no 100/110 the first indicator should be 0.
  * If the title starts with an article (the, an, a) then the 2nd indicator needs to indicate how many spaces to skip when indexing: a=2, an=3, the=4

{% hint style="info" %}
e.g.   245 1**2** A spaceman...\
&#x20;        245 1**3** An apple...\
&#x20;        245 1**4** The world...
{% endhint %}

* When the title being replaced includes other information about the object (creator, medium/technique, date), then ensure this information is included in the appropriate fields in the record. They do not need to be in the title.
* Add a note to explain the source of the title in a 500 note. A list of phrases to use is [here](https://docs.wellcomecollection.org/visual-material/metadata-framework/metadata-elements/title-brief-description).
* If you are adding a title that has been given by the artist or is taken from text on the object, then add a brief description of the visual content of the image / object in 520 field.

{% hint style="info" %}
e.g. [5150i](https://wellcomecollection.org/works/mahrpy8v):  &#x20;

**245 10** Disease is disguised. Don't gamble with VD!

**246 1\_** **|i**Previous title, replaced November 2019**|a**The face of a beautiful woman is revealed as a mask covering her real face, which is hideously disfigured with syphilitic sores. Colour lithograph after Forsyth, ca. 1946(?)**|5**UkLW

**500 \_\_** The title has been taken from wording on the object.

**520 \_\_** The face of a woman is revealed as a mask covering her real face, which has visible syphilitic sores.
{% endhint %}