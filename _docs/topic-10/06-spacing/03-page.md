---
title: Kerning
module: topic-10
permalink: /topic-10/kerning/
---

<div class="divider-heading"></div>

**Kerning** is the amount of space between two glyphs (or the representation of a character). This is not to be confused with _tracking_, which is the consistent degree of space between all characters.

<img src="../img/typography-kerning.jpg" style="height: 200px; margin: auto" alt="kerning" title="kerning"/>

To adjust how glyphs are spaced, use the `font-kerning: ` property.

<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
* {
  font-kerning: auto;
}
```

`font-kerning:` accepts these term values:
- `auto` (default, the browser determines)
- `normal` (use information stored in the font)
- `none` (disable font's kerning)


### “Should I adjust the kerning?”

Adjusting the kerning of a font in web typography is not often needed.

You'll notice that adjusting the kerning below creates only a subtle difference. Well-kerned fonts are uniform and pleasant to read and have specified kerning stored in them, which is applied by default.

This does not mean you shouldn't consider kerning the font or changing it; just that your decision should be an informed one.


<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="dyXNwQE" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Kerning (Toggle)" class="codepen"></p>
</div>
