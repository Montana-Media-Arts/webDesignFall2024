---
title: Relative Position
module: topic-11
permalink: /topic-11/position-relative/
---

<div class="divider-heading"></div>

Setting the position property to "relative" (position: relative;) allows developers to adjust an element's position slightly from its original place in the normal document flow. When an element is positioned relatively, it maintains its spot in the normal flow but can be moved relative to that position using offset properties (top, right, bottom, left).

**NOTE:** This does not affect the position of surrounding elements. These other elements will remain positioned where they would in normal flow. This is true even if the altered element is positioned over them.

In the below example, notice how the `top:` and `left:` properties are used to move the second paragraph to the lower-right of where its
normal flow" position would have been.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="PozeYZb" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Position, Pt. 1 " class="codepen"></p>
</div>
