---
layout: page-fullwidth
show_meta: false
title: "Nameplate Generator"
subheadline: "Generate a nameplate for your office"
teaser: ""
header:
   image_fullwidth: "header_unsplash_about.jpg"
permalink: /nameplate/
---

This program will generate a nameplate for your office. 
Cut on outer line (so that outer line is not visible on sides).

Originally created by Milo Martin and Craig Zilles with help from
Glenn Ammons and Brian Forney. Fixed a couple times by Jaime Frey.

Enter one or more names and e-mail addresses:

<form action="nameplate.cgi" method="post">
<table>

<tr>
  <td>Name:</td>
  <td><input type="text" name="name1" size="50" /></td>
</tr>
<tr>
  <td>E-Mail (optional):</td>
  <td><input type="text" name="email1" size="50" /></td>
</tr>

<tr>
  <td>Name:</td>
  <td><input type="text" name="name2" size="50" /></td>
</tr>
<tr>
  <td>E-Mail (optional):</td>
  <td><input type="text" name="email2" size="50" /></td>
</tr>

<tr>
  <td>Name:</td>
  <td><input type="text" name="name3" size="50" /></td>
</tr>
<tr>
  <td>E-Mail (optional):</td>
  <td><input type="text" name="email3" size="50" /></td>
</tr>

<tr>
  <td>Name:</td>
  <td><input type="text" name="name4" size="50" /></td>
</tr>
<tr>
  <td>E-Mail (optional):</td>
  <td><input type="text" name="email4" size="50" /></td>
</tr>

<tr>
  <td>Name:</td>
  <td><input type="text" name="name5" size="50" /></td>
</tr>
<tr>
  <td>E-Mail (optional):</td>
  <td><input type="text" name="email5" size="50" /></td>
</tr>

<tr>
  <td>Name:</td>
  <td><input type="text" name="name6" size="50" /></td>
</tr>
<tr>
  <td>E-Mail (optional):</td>
  <td><input type="text" name="email6" size="50" /></td>
</tr>
<tr>
  <td>Output type:</td>
  <td>
    <input type="radio" checked="checked" name="color" value="bw" label="Black and White" />Black and White
    &nbsp;
    &nbsp;
    &nbsp;
    &nbsp;
    <input type="radio" name="color" value="color" label="Color" />Color
  </td>
</tr>
</table>

<input class="radius button small" type="submit" value="Generate PDF">
<input class="radius button small" type="submit" value="Generate LaTeX" name="type">

</form>
