---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: false
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://images.eap.bl.uk/EAP755/EAP755_1_1_28/5.jp2/full/pct:50/0/default.jpg" %} 

{% include feature/nav-menu.html sections="About CollectionBuilder SA;About the About Page" %}

## About this website

This demo collection features items from the British Library's [Endangered Archives Programme](https://eap.bl.uk).
 
Photographs from the EAP collections:

- EAP001: Iran
- EAP755: Argentina
- EAP894: Bulgaria

{% include feature/image.html objectid="http://127.0.0.1:4000/items/eap755_1_1_28_6.html" width="75" %}

{% include feature/card.html header="This is a Card" text="text description underneath" objectid="https://images.eap.bl.uk/EAP755/EAP755_1_1_28/3.jp2/full/pct:20/0/default.jpg" width="25" centered=true %}

{% include feature/button.html text="Full EAP website" link="https://eap.bl.uk" color="success" %}

{% include feature/modal.html button="Modal that displays other text as a popup" title="when clicked:" text="More info given here" color="primary" %}

{% include feature/image.html objectid="demo_001" width="75" %} 

<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include cb/about_the_about.md %} 
