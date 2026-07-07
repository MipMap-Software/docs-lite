---
title: Volume Measure
sidebar_position: 4
---

## Volume measure

![](/img/en-img/volume.png)

### Steps

- Click the Volume tool, draw a polygon on the result, then click "Calculate volume". Choose a reference surface as needed to perform the volume measurement.
- Left-click to add vertices, right-click to undo the last vertex, and double-click the left mouse button to finish the polygon and complete the measurement. Press `Esc` to exit measurement mode.
- After clicking "Calculate volume", the left panel shows the area and volume measurements: planar area, 3D surface area, planar perimeter, 3D perimeter, minimum elevation, maximum elevation, elevation difference, cut volume, fill volume, total volume, and net volume.
- You can edit the volume label name and color.

### Definitions

- Cut volume: the volume of material above the reference surface within the selected polygon.
- Fill volume: the volume of material below the reference surface within the selected polygon.
- Total volume = Cut volume + Fill volume
- Net volume = Cut volume - Fill volume

### Reference surface options

- Triangulated Mesh Plane: an irregular surface automatically generated to follow the original terrain within the polygon.
- Fitted Plane: a single planar slope that approximates the overall inclination of the terrain inside the polygon, simplifying undulations to a single plane.
- Average Plane: a horizontal reference plane at the average elevation of all points within the polygon.
- Highest/Lowest Plane: a horizontal plane set to the elevation of the highest or lowest vertex within the polygon.
- Custom Plane: manually specify a reference elevation to create a horizontal plane at any desired height.
