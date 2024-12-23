---
title: Href
module: topic-09
permalink: /topic-09/link-href/
---

<div class="divider-heading"></div>

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><link rel="stylesheet" type="text/css"></span> <span style="color: #79AF33; font-weight: bold;">href="#"</span> <span style="color: #999">/ ></span></p>
  </div>
</div>

Provide the relative or absolute URL as the value to the `href=""` attribute. This tells the browser where the document is located.

Linking CSS documents is the same process you've been using for other site files, such as images and videos.


### External Style Sheets
Many sites also link to external CSS documents, which will be linked via an _absolute URL_.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<head>
  <title>Tuna the Cat</title>
  <link rel="stylesheet" type="text/css" href="https://codepen.io/rachelnabors/pen/bpAJH.css">
</head>
```


### Internal Style Sheets
Internal files, like your own created CSS document, should be linked via _relative URL_.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<head>
  <title>Tuna the Cat</title>
  <link rel="stylesheet" type="text/css" href="./css/style.css">
</head>
```

<span class="label label-info">NOTE:</span> When linking the same stylesheet in your child pages, you would need to add an additional 'dot' to your file path (`../`) to move up a directory.
