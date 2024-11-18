---
title: Navigation Menu with CSS
module: topic-12
permalink: /topic-12/nav-menu-about/
---

<div class="divider-heading"></div>

The primary navigation, or main site menu, contains all of your site's major pages (or resources) and should be available on every page at all times. This means that visitors should be able to visit all important site pages independently of whatever page they're currently on.

So, what makes up a good site menu?

For our purposes, the **nav bar** contains individual links to pages that deserve a spot in the main navigation. This is usually represented by a horizontal bar across the top of the site or a vertical list in a right sidebar and often includes:
- The home page.
- An “about us” page.
- A contact page.
- A showcase page, such as services, portfolio, gallery, blog, or other collected works.

But your site will often have related materials that you also want in the main navigation, but they are too secondary to need their own parking spot in the nav bar. We can group these links inside a **dropdown menu**, hidden inside a broad term in the nav bar. Dropdowns usually require the user to hover their mouse over to make visible:

<img src="../img/dropdown.gif" alt="blocks of the site navigation bar" title="Site Navigation" />
<p class="img-caption">Source: <a href="https://codemyui.com/material-design-drop-down-navigation-menu/">Code My UI</a></p>

Lastly, most sites have a _constantly_ available menu regardless of where a visitor is currently scrolling. This site, for example, uses **fixed menu** - no matter how far you scroll down any page, you still see the main site navigation. This is done by setting the position of that element in your CSS.
