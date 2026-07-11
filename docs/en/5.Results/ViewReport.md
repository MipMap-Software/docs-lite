---
title: View Report
sidebar_position: 5
---

## View report

![](/img/en-img/viewreport.png)

Click "View Report" to see the reconstruction report and the annotation report for the task.

Use the selector in the upper-left to switch between reports. Click ![](/img/en-img/download.png) in the upper-right to download the report as a PDF.

### Reconstruction report

#### Task Overview

Shows task name, task type, data acquisition time, number of photos, task start/end time, total duration, and the time spent on photogrammetric processing and reconstruction.

The thumbnail image shows the task thumbnail.

![](/img/en-img/reconstructionreport.png)

#### Overview and Coverage

Lists photo count, flight altitude, number of tie points, ground sampling distance, survey area, and reprojection error.

> Smaller reprojection error indicates more accurate camera poses and better reconstruction quality. Typically around 1 pixel; if larger than 2 pixels, check data import for issues.

Thumbnail shows the overlap/coverage distribution.

![](/img/en-img/overview.png)

#### Camera Calibration

Reports the number of cameras, number of photos, images registered in the reconstruction, unregistered images, registration rate, and a table of distortion calibration parameters per camera.

> Unregistered images are photos for which camera poses were not solved during photogrammetry. A high number of unregistered images reduces the registration rate and may cause gaps in the results.

Thumbnail shows the camera residuals distribution.

![](/img/en-img/camera.png)

#### Photo Positions

Shows the root-mean-square difference between photo positions after photogrammetric adjustment and the original POS-provided positions.

> This error only reflects the difference between image positions and POS positions and does not represent absolute accuracy.

![](/img/en-img/positions.png)

#### Reconstruction Quality Report

Runtime environment: records hardware (CPU, GPU, memory), software version, and SDK version.

Reconstruction parameters: records reconstruction quality, number of blocks, 3D output coordinate system, and output types.

![](/img/en-img/qualityreport.png)

### Annotation Report

#### Task overview

Shows task name, task type, data acquisition time, and reconstruction completion time.

The thumbnail image shows the task thumbnail.

![](/img/en-img/annotationreport.png)

#### Annotation list and details

The annotation list provides a table of all annotations; the annotation details view breaks down each annotation with details and a thumbnail on the right.

![](/img/en-img/annotationlist.png)
