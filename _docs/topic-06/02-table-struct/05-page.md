---
title: Headings
module: topic-06
permalink: /topic-06/table-headings/
---

<style>
  .indent-sm {
    margin-left: 20px;
    display: block;
  }
  .indent-lg {
    margin-left: 40px;
    display: block;
  }
</style>

<div class="divider-heading"></div>


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body" style="font-size: large; margin: 0;">
      <span style="color: #999">&lt;table&gt;</span>
      <span style="color: #999">
          <span class="indent-sm">&lt;tr&gt;</span>
            <span style="color: #79AF33; font-weight: bold;"><span class="indent-lg">&lt;th&gt;&lt;/th&gt;</span></span>
            <span class="indent-lg"><span style="color: #79AF33; font-weight: bold;">&lt;th scope="col"&gt;</span>Column A<span style="color: #79AF33; font-weight: bold;">&lt;/th&gt;</span></span>
          <span class="indent-sm">&lt;/tr&gt;</span>
          <span class="indent-sm">&lt;tr&gt;</span>
            <span class="indent-lg"><span style="color: #79AF33; font-weight: bold;">&lt;th scope="row"&gt;</span>Row 1<span style="color: #79AF33; font-weight: bold;">&lt;/th&gt;</span></span>
            <span class="indent-lg">&lt;td&gt;Cell A1&lt;/td&gt;</span>
          <span class="indent-sm">&lt;/tr&gt;</span>
      </span>
      <span style="color: #999">&lt;/table&gt;</span>
  </div>
</div>


You should use **table headings** or `<th>` elements to provide structure and style to head your columns and rows. This is incredibly helpful for people who use screen readers and helps search engines index your page correctly.

We delineate columns and rows using the `scope=""` attribute; a column is headed using `<th scope="col">...</th>` and a row is headed using `<th scope="row">...</th>`

<span class="label label-danger">IMPORTANT:</span> Empty cells are not forgotten cells -  they still need to be created using `<th>` or `<td>` elements. Not including these elements will cause your table to be rendered improperly.
