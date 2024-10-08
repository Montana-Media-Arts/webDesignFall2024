---
title: Formats and Browser Support
module: topic-07
permalink: /topic-07/audio-formats/
---

<div class="divider-heading"></div>

Even more so than with video, audio should always be offered in multiple formats.

## Audio Formats
Best included self-hosted audio formats:

- MP3: Good quality for file size, but proprietary.
- OGG Audio: Open-sourced.
- Wav<a href="#lossless-formats">*</a>: Lossless, but larger files.

Audio files can be rendered to many file formats. The most popular and well-known is likely `.mp3`.

This is because the compression achieved creates smaller file sizes without comprising audio quality too greatly. However, `.mp3` is technically a proprietary format, and as such, some people are hesitant to use it.

If you find yourself working for an audio-based client, they may also have strong opinions about what file types they want prioritized. For example, they may want to use `.ogg` as this is an open-source based audio format.

<p id="lossless-formats">*Your clients may also insist that you include lossless or uncompressed audio file formats such as <code>.wav</code>, <code>.aiff</code>, or <code>.flac</code>.</p>


## “Not Supported!”
Notice that the `<audio>` element is not an "empty element" and requires both an opening and closing tag. This serves a number of purposes, but the most important is that the developer can include content between the tags that will be displayed or called in the case that an end-user's browser does not support the `<audio>` element or audio file format.

You should always include extra markup inside the tags for this potential case.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<audio src="#" preload controls>
  <p>A quick description of the song...</p>
  <p>Sorry, your browser does not support our audio format.</p>
</audio>
```
