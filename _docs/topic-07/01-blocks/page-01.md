---
title: Page Structure and Extra Markup
module: topic-07
permalink: /topic-07/extra-markup/
---

<div class="divider-heading"></div>

Up to this point, we've added HTML elements to pages singularly, in that they really had no defined groupings. However, most pages are built on “blocks” of content that are placed in relation to each other.

Consider an HTML file "**gallery.html**," that might be on your website:

<img src="../img/gallery-page.png" alt="simple gallery page" style="width: 200px;" />

The gallery page has 4 defined areas that display different content based on their type:
1. image
2. video
3. audio
4. social media sharing button for visitors to use

Each area has a section for files, a slider (or scrollable gallery) to present those files interactively, and a decorative illustration.

These sections, or _divisions_, help us control how content looks en masse rather than element-by-element. This will become more apparent as we proceed.


<div class="divider-pg"></div>


To describe the examples you've seen, elements on these pages work much like building “blocks” - separate bricks that come together to create the page's structure.

<img src="../img/gallery-page-blocks.gif" alt="page breaking into blocks" style="width: 300px;" />

These elements are primarily divided into two categories: **block-level elements**, which take up the full width of the page, and **inline elements**, which do not cause line breaks and can be positioned naturally next to each other.


<h2 id="block-level">Block-Level Elements</h2>

Block elements appear on their own block on a new line. Each of these (unless told otherwise through styling) appears on a new line in HTML pages. Some block elements are:

- Headings `<h1>`-`<h6>`
- Paragraphs `<p>`
- Lists `<ol>`, `<ul>`
- Horizontal rules `<hr>`

In the example above, a new type of block-level element was used (the `<div>`) to section off a row for each media gallery, which altogether fills the page edge-to-edge.


<h2 id="inline">Inline Elements</h2>

Inline elements do not start on a new line. Instead, they sit next to other elements on the same line. Some examples of inline elements include:

- Images `<img>`
- Semantic elements `<em>`, `<b>`, etc.
- Links `<a>`

The example above used a new type of inline element (the `<span>`) to create the slider. The illustration can sit on the same block since `<img>` is also an inline element.
