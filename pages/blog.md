---
title: Blog
layout: about
permalink: /blog.html
# include CollectionBuilder info at bottom
credits: false
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://images.eap.bl.uk/EAP001/EAP001_1_1/1.jp2/full/pct:40/0/default.jpg" %} 



## About this website

This demo collection features items from the British Library's [Endangered Archives Programme](https://eap.bl.uk).
 
Photographs from the EAP collections:

- EAP001: Iran
- EAP755: Argentina
- EAP894: Bulgaria



{% include feature/card.html header="This is a Card" text="text description underneath" objectid="https://images.eap.bl.uk/EAP755/EAP755_1_1_28/3.jp2/full/pct:20/0/default.jpg" width="25" centered=true %}

{% include feature/button.html text="Full EAP website" link="https://eap.bl.uk" color="success" %}

{% include feature/modal.html button="Modal that displays other text as a popup" title="Message popup:" text="More info given here" color="primary" %}

{% include feature/image.html objectid="eap755_1_1_28_5" width="75" caption="an image" %}


{% include feature/image.html objectid="https://images.eap.bl.uk/EAP755/EAP755_1_1_28/3.jp2/full/pct:20/0/default.jpg" width="75" alt="EAP image" %}

{% include feature/image.html objectid="eap894_1_9_50;eap755_1_1_28_2;eap755_1_1_1_2" %}

{% include feature/image.html objectid="https://images.eap.bl.uk/EAP001/EAP001_16_1/1.jp2/full/full/0/default.jpg;https://images.eap.bl.uk/EAP001/EAP001_16_1/16.jp2/full/full/0/default.jpg" caption="EAP001;EAP001" link="https://eap.bl.uk/archive-file/EAP001-16-1;https://eap.bl.uk/archive-file/EAP001-16-1" alt="Link back to EAP website;Link back to EAP website" %}

{% include feature/timelinejs.html %}