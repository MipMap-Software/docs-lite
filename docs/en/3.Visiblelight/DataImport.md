---
title: Data Import
sidebar_position: 1
---


## Data import

Create a new project and select Visible Light.

![](/img/en-img/newproject2.png)


### Import images and videos

![](/img/en-img/importdata.png)

**Import images:**

Select images to import into the current task.

**Import folder:**

Select a folder to import all images within it into the current task.

**Import video:**

Select a video file to import into the current task.

![](/img/en-img/extraction.png)

- Add Video: Continue adding video files to the frame-extraction list.

- Start and End: Set the frame-extraction start and end times as needed.

- Time Interval: Set the frame-extraction interval according to the camera movement speed during acquisition. The default is 1 second; if extracted frames do not overlap sufficiently, reduce the interval.

- Automatic Pose Extraction: When enabled, POS information from an SRT file with the same name as the video will be extracted automatically.

- Uniform Time Interval: After setting, all videos in the current list will be extracted using the specified interval.


### Edit camera

The software automatically parses the imported photos' file structure and metadata, and groups photos by camera based on camera parameters found in the photos (focal length, sensor size, intrinsics, distortion, etc.).

If camera parameters cannot be parsed from the photos or are incorrect, you need to edit the camera parameters.

>It is recommended to select the camera parameters for your device model from the database.

**Unknown camera parameters can be left unset.**

![](/img/en-img/editcamera.png)

- Choose the correct camera type and fill in focal length, principal point, and distortion parameters.

- Compute pixel focal length: Click the calculation icon to enter the camera's physical focal length and sensor size to compute the corresponding pixel focal length.

- Lock parameters: Select camera parameters to lock; locked parameters will not be optimized and will remain fixed.

- Import OPT file: Import an OPT file to auto-detect and fill camera parameters.

- Get from database: Select camera parameters from the built-in database; if the model is not in the database, it cannot be selected.

- Save to local database: Save the current camera parameters to the local database for later use.

- Merge cameras: In the left list, hold Shift and click cameras with identical parameters to merge them.

- Delete camera: Click the delete icon to remove the camera and its imported photos.


### Edit POS

The software automatically parses pose information included in the imported photos. If pose information cannot be parsed from the photos, you must manually import a POS file.

**Unknown POS can be left unset.**

![](/img/en-img/editpos.png)

![](/img/en-img/importpos.png)

- Import POS file: Click ![](/img/en-img/importposfile.png) to select a POS file to import. Use the attitude-angle dropdown to select the appropriate attitude angles, and map each column header to the corresponding POS field.

- Clear POS: Click ![](/img/en-img/clearpos.png) to clear POS information for all images in the current task.

- CRS: Click ![](/img/en-img/crs.png) to choose the coordinate system and vertical datum corresponding to the POS information; you can search by keyword. If the POS uses a custom coordinate system, import a PRJ file.

<div style="display:flex;">

<img src="/img/en-img/coordinatasystem.png" style="width:50%;">

<img src="/img/en-img/coordinatasystem2.png" style="width:50%;">

</div>

- Pos Accuracy: Select the accuracy level for the POS information. Choose according to the actual acquisition device; higher accuracy increases the POS weight during bundle adjustment.


![](/img/en-img/posaccuracy.png)

- Height offset: Enter an elevation offset value; all elevations in the current POS information will be shifted by this value.

- Export POS: Export the current POS information to a specified folder in CSV format.


### Delete images

If imported images are redundant or not required for reconstruction, you can delete them.

#### Delete from list
![](/img/en-img/editimg.png)

1. Delete images belonging to a specific camera.

2. Delete all images in the task.
#### Delete by selection

![](/img/en-img/editimg2.png)

- Click the ![](/img/en-img/image65.png) icon to draw a selection in the map preview to delete photos; deleted photos will not participate in reconstruction.

- On the map, left-click or click ![](/img/en-img/image66.png) to create a vertex; double-click to finish drawing. Right-click a vertex to delete it; hold the left mouse button to drag a vertex.

- Click ![](/img/en-img/image67.png) to delete photos inside the drawn area, click ![](/img/en-img/image68.png) to delete photos outside the drawn area, and click ![](/img/en-img/image69.png) to cancel the current operation.


