---
title: Rows
module: topic-06
permalink: /topic-06/table-rows/
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
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width: 50%">
      <span class="sr-only">50% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body" style="font-size: large; margin: 0;">
      <span style="color: #999">&lt;table&gt;</span>
      <span style="color: #999">
          <span class="indent-sm"><span style="color: #79AF33; font-weight: bold;">&lt;tr&gt;</span></span>
            <span class="indent-lg">&lt;th&gt;&lt;/th&gt;</span>
            <span class="indent-lg">&lt;th scope="col"&gt;Column A&lt;/th&gt;</span>
          <span class="indent-sm"><span style="color: #79AF33; font-weight: bold;">&lt;/tr&gt;</span></span>
          <span class="indent-sm"><span style="color: #79AF33; font-weight: bold;">&lt;tr&gt;</span></span>
            <span class="indent-lg">&lt;th scope="row"&gt;Row 1&lt;/th&gt;</span>
            <span class="indent-lg">&lt;td&gt;Cell A1&lt;/td&gt;</span>
          <span class="indent-sm"><span style="color: #79AF33; font-weight: bold;">&lt;/tr&gt;</span></span>
      </span>
      <span style="color: #999">&lt;/table&gt;</span>
  </div>
</div>


**Table rows** are created using the `<tr>...</tr>` element. Inside each <tr> are individual cells, which represent the columns of the table. These cells are created using <td> tags.
