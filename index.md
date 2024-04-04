# SlicerTrack

## About

SlicerTrack is open-source, extendable, developed in Python as an extension on the highly successful 3D Slicer platform. SlicerTrack is built for target tracking visualization by replaying cine 2D images and overlays the outline of the Region of interest (ROI) using a displacement data file. We open source the code of SlicerTrack on [GitHub](https://github.com/laboratory-for-translational-medicine/SlicerTrack) for compilation and further development.

![SlicerTrack Screenshot 1](resources/screenshots/ST1.png)

## What can SlicerTrack do?

The extension accepts three inputs from the user:

- A set of cine MR images
- A segmentation of the ROI
- The transformation data reflects the amount of displacement of the ROI expressed in the DICOM coordinate system. It can be in csv, txt, xlsx or xls format.

![Slicer Track Inputs](resources/screenshots/ST_inputs.png)

Users can change playback speed, overmask mask outline or opacity. Once the user presses play, the extension will go through the series of MR images with the segmentation overlaid on the current image. Users can decide to pause at any frame or go to any particular MR image using the sequence slider.

![SlicerTrack Media Control](resources/screenshots/ST_mediaControl.png)

## Tutorials (WIP)

### Pre-requisites

- 3D Slicer software version 5.6.1 installed
- Recommended Hardware: (get Jacqueline computer's spec)

### Install the Extension

- Get the extension install
- Sample Data set can be download from [here](https://drive.google.com/drive/folders/1qJj53YfGM4Q7atsI-XZyySvR-F98ENXA?usp=sharing)
- Might use this doc for helping users [link](https://docs.google.com/document/d/1u4LpEE9t-0blBPqisjiCp-MqHs5etJD8cEsEMPEoC9U/edit)
## Contact us

If you encounter any problem, please contact:

[SlicerTrack@cs.torontomu.ca](mailto:SlicerTrack@cs.torontomu.ca)