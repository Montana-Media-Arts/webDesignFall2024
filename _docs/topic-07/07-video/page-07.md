---
title: 5. Other Attributes
module: topic-07
permalink: /topic-07/video-other-att/
---

<div class="divider-heading"></div>

Several other attributes can be applied to the `<video>` to make it behave as intended.


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><video src="#" poster="#" width="..." height="..."</span> <span style="color: #79AF33; font-weight: bold;">preload controls ></span><span style="color: #999"></video></span></p>
  </div>
</div>


<div class="divider-pg"></div>


## Multiple-Source


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><video poster="#" width="..." height="..."</span> <span style="color: #79AF33; font-weight: bold;">preload controls</span> <span style="color: #999">></span>
        <br>
        <span style="color: #999; margin-left: 2em;">&lt;source src="#" type=""&gt;</span>
        <br>
        <span style="color: #999; margin-left: 2em;">&lt;source src="#" type=""&gt;</span>
        <br>
    <span style="color: #999;"></video></span></p>
  </div>
</div>


<div class="divider-pg"></div>


### preload
The `preload` attribute takes one of three values and tells the browser how to load the video file if `autoplay` is absent.

- `preload="none"` - tells the browser to do nothing until the user tells it to do so.
- `preload="auto"` - tells the browser to download the media file when the page loads.
- `preload="metadata"` - tells the browser only to collect metadata, such as size and length.


### controls
The `controls` attribute is passed alone and does not require a trailing value. This attribute indicates whether the player should display controls. If you do not use this attribute, no controls will be shown by default.


### loop
The `loop` attribute, when present, tells the browser to loop the file.


### autoplay
Like the `controls` attribute, the `autoplay` attribute is included as a single word or not at all. When present, this attribute tells the browser to start playing the file on load.

<span class="label label-info">Note:</span> This is considered poor practice, and in most cases, it is better to let the user choose whether to start the video or not.
