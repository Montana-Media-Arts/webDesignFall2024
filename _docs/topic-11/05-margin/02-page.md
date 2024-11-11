---
title: Margins in Practice
module: topic-11
permalink: /topic-11/margin-example/
---

<div class="divider-heading"></div>


In the following example, look at the two containers and their position based on the margin settings.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="NWrYQVp" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Margin, Pt. 1" class="codepen"></p>
</div>



### Margin and Padding Combined

In the next example, notice how the `.child-container-03` has both margin and padding properties set. Also, notice that the parent container does not have either. Note that the browser does not allow the child container's margin to push the parent container's height. However, it still creates space between the top of the containing window and the parent and child elements.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="dyXmxEx" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Margin, Pt. 2" class="codepen"></p>
</div>


### Using Margin to Set Center Alignment

The margin property is also used to center-align an element horizontally in its parent element. This can be accomplished by setting the properties value to `auto`, or by setting both `margin-left: auto;` & `margin-right: auto;`.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="QWEmeXM" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Margin, Pt. 3" class="codepen"></p>
</div>
