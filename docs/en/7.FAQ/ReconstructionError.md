---
title: Reconstruction errors
sidebar_position: 3
---

## Reconstruction errors

Reconstruction errors are usually caused by problems with the input data or the computer environment and configuration. When an error occurs, first check whether the imported data is correct, whether antivirus or other security software is blocking the program, and whether the system configuration meets the reconstruction requirements.

If you have ruled out these issues, click ![](/img/en-img/support2.png) Contact us via email, describe the issues you encountered or provide logs to receive technical assistance.

Click ![](/img/en-img/log.png) to export the log files and send them to technical support to help analyze the cause of the reconstruction error.

![](/img/en-img/support.png)

### Photo reading error

![](/img/en-img/imgerror.png)

Solutions:

- Check whether photo files have been moved and whether they can be opened normally.
- Photo paths or filenames may contain unsupported special characters (for example, certain symbols); rename files or folders to remove special characters.
- Reading directly from a memory card can be unstable and slow; it is recommended to copy photos to a local disk before processing.
- Some images may be corrupted, causing read errors; try opening the images to verify integrity.
- The image may be 4-band (e.g., multispectral); the software does not support 4-band images currently.

### Point cloud and POS timestamp mismatch

![](/img/en-img/poserror.png)

Cause: The timestamps recorded in the POS file do not match the timestamps recorded in the LAS file.

Solution: Check whether the correct timestamp column is selected in the POS import interface, and verify that the timestamp field format in the LAS file matches the POS timestamp format.
