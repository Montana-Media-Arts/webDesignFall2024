---
title: Maps in the iframe Element
module: topic-07
permalink: /topic-07/iframe-element-maps/
---

<div class="divider-heading"></div>

In addition to displaying other webpages in the main webpage, the iframe element is often used to display specific types of instances, like including a [Google Map](https://www.google.com/maps) of the University of Montana.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2728.1679496500064!2d-113.98739678456647!3d46.86006717914222!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x535dcc33f19815cb%3A0x9c296b8546ca9abf!2sUniversity%20of%20Montana!5e0!3m2!1sen!2sus!4v1601845704518!5m2!1sen!2sus" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
```


<div class="external-embed" style="width: 600px; margin: auto;">
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2728.1679496500064!2d-113.98739678456647!3d46.86006717914222!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x535dcc33f19815cb%3A0x9c296b8546ca9abf!2sUniversity%20of%20Montana!5e0!3m2!1sen!2sus!4v1601845704518!5m2!1sen!2sus" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
</div>


<div class="divider-pg"></div>


## How-To:
From the Google Maps page, you can click the “share” button after completing a search. This opens a separate pop-up, where you should select the “Embed a map” option. You can then tweak the display options and copy Google's iframe code to include on your site.


<img src="../img/embed-google-maps.gif" title="Google Map embed" alt="Image showing the “embed map” option from Google Maps" width="600" />


Including this code on your site will create an embedded Google Map that your visitors may interact with. This is typically useful for showing a business's location.
