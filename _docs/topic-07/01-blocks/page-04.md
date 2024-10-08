---
title: Grouping with Divs
module: topic-07
permalink: /topic-07/html-divs/
---

<div class="divider-heading"></div>

Up until this point, all elements we have examined have had specific structural or semantic purposes (e.g., defining a paragraph, heading, emphasizing text, or including images). However, there are elements that provide structure without necessarily implying styling or content.

<div class="container-row">
  <img src="../img/legos-divs.png" alt="stacked building blocks" title="Just like building blocks!" style="float: right; width: 150px; margin-top: 0; margin-left: 15px;" />

  <p>The <code>&lt;div&gt;...&lt;/div&gt;</code> element offers developers a <b>block-level element</b> to group other elements together.</p>

  <p>Divs can be <b>singular or nested</b> within each other. Developers heavily use this element to increase structural clarity and identify element groups. This, in turn, increases readability, which is always desired.</p>
</div>


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<div id="one">
  <!-- Content -->
</div>

<div id="two">
  <!-- Different Content -->
</div>
```


This element is an easy way to wrap content to style via CSS. _By itself, the sole styling implied by the_ `div` _element is that it will start on a new line_
