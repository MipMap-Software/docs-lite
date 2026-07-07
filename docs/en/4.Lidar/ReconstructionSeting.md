---
title: Reconstruction Settings
sidebar_position: 2
---

## Reconstruction Settings

![](/img/en-img/reconstruction2.png)

### Reconstruction quality

<table>
<colgroup>
<col style="width: 23%" />
<col style="width: 24%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th>Quality</th>
<th>Ultra High</th>
<th>High</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Rendering</td>
<td>Full-resolution rendering</td>
<td><p>Resampled rendering at 2x interval from original images</p></td>
</tr>
<tr class="even">
<td>Texture and structure quality</td>
<td>Ultra High</td>
<td>High</td>
</tr>
</tbody>
</table>

### 3D Outputs

Click the icon ![](/img/en-img/enable.png) to enable output for model, point cloud, or Gaussian splatting.

**Textured Model:**

By default, B3DM and OSGB formats are produced. Click ![](/img/en-img/check.png) to select additional formats.

**Point Cloud:**

By default, PNTS and LAS formats are produced.

**Gaussian Splatting:**

- By default, SOGTiles and PLY formats are produced. Click ![](/img/en-img/check.png) to choose output formats.

- People Removal: Click the icon ![](/img/en-img/enable.png) to enable removal of people from Gaussian Splatting results.

### Output coordinate system

Choose the coordinate system and vertical datum for 3D outputs; you can search by keyword. If the 3D output uses a custom coordinate system, import a PRJ file.

<div style="display:flex;">

<img src="/img/en-img/coordinatasystem.png" style="width:50%;">

<img src="/img/en-img/coordinatasystem2.png" style="width:50%;">

</div>
