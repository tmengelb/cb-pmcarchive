---
title: Unknown Marks
layout: page
permalink: /unknown.html
# include CollectionBuilder info at bottom
credits: false
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
about-featured-image: 
# set background-position for featured image, "center", "top", "bottom"
position: 
# major heading to display over featured image
heading:
# paragraph text below heading in featured image
sub-heading: 
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
padding: 2.5em
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---
<br>
## Do you recognize me?
<br>
#### The below marks are not yet identified. If you can identify any, please let us know by emailing info@printersmarks.org and referencing the number we have assigned (e.g. Unknown 001).

<div class="row">
  <div class="col-md-3">
    {% capture col1 %} 
<br> 
{% include feature/card.html text="Seen on prints in the series *Krieg droht (War Threatens)* by Lea Grundig." header="Unknown 001" objectid="/assets/img/unidentified_001.jpg" %}
<br>
{% include feature/card.html text="Seen adjacent to the Collector's Press chop on an untitled lithograph edition by Ulfert S. Wilke." header="Unknown 005" objectid="/assets/img/unknown_005.jpg" %}
<br>
    {% endcapture %}
    {{ col1 | markdownify }}
  </div>

  <div class="col-md-3">
    {% capture col2 %}
<br> 
{% include feature/card.html text="Seen on a Richard Bosman print published by Brooke Alexander Editions. Possibly Brooke Alexander Editions." header="Unknown 002" objectid="/assets/img/unidentified_002.jpg" %}
<br>
    {% endcapture %}
    {{ col2 | markdownify }}
  </div>

  <div class="col-md-3">
    {% capture col3 %}
<br> 
{% include feature/card.html text="Seen adjacent to the Littleton Studio's chop on an edition by Nancy Genn. Possibly Sandy Willcox." header="Unknown 003" objectid="/assets/img/unknown_003.jpg" %}
<br>
    {% endcapture %}
    {{ col3 | markdownify }}
  </div>
    <div class="col-md-3">
    {% capture col4 %}
<br> 
{% include feature/card.html text="Seen adjacent to the Collector's Press chop on *Encounter*, a lithograph edition by Arthur Secunda." header="Unknown 004" objectid="/assets/img/unknown_004.jpg" %}
<br>
    {% endcapture %}
    {{ col4 | markdownify }}
  </div>
</div>