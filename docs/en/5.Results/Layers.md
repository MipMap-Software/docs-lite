---
title: Layers
sidebar_position: 1
---

## Layers

**Click** ![](/img/en-img/collapselayer.png) **to collapse/expand layer contents, or click** ![](/img/en-img/check.png) **to show/hide a layer.**

### Annotation

![](/img/en-img/Layer.png)

![](/img/en-img/exportannotation2.png): Export all annotations for the current task; choose the desired format and coordinate system.

![](/img/en-img/delete.png): Delete all or selected annotations in the current task.

![](/img/en-img/createfolder.png): Create a folder to organize annotations.

![](/img/en-img/zoomannotation.png): Zoom to the annotation.

![](/img/en-img/editannotation.png): Edit the annotation; add or move vertices.

![](/img/en-img/showimg.png): Show all images that can see this annotation.

Click an annotation to view its details on the right, where you can edit its name and color.

> For more annotation operations see: [Point Measure](../6.Mark&Measure/PointMeasure.md), [Line Measure](../6.Mark&Measure/LineMeasure.md), [Area Measure](../6.Mark&Measure/AreaMeasure.md), [Volume Measure](../6.Mark&Measure/VolumeMeasure.md)

### Result Layers

![](/img/en-img/resultlayer.png)

Click a result layer to modify its visibility and rendering mode in the right panel.

3D models and 3D point clouds can be displayed together.

**3D Model:**

When double-sided rendering is enabled, the model will display texture back faces; when disabled, back faces are not shown.

When wireframe is enabled, the model structure is shown on the map as a triangular mesh wireframe.

**3D Point Cloud:**

When EDL rendering is enabled, the point cloud displays enhanced depth and outlines terrain features, improving 3D perception.

When height rendering is enabled, the point cloud maps elevation values to colors, making terrain relief easy to interpret.

### Dataset

![](/img/en-img/dataset.png)

When photo display is enabled, the map shows the solved poses of registered images.

You can visually assess bundle-adjustment quality: whether image stitching is consistent, if there are misalignments, and whether camera poses match acquisition.

Drag the ![](/img/en-img/imgsize.png) slider to control the display size of photos on the map.