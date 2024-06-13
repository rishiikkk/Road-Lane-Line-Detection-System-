# Road-Lane-Line-Detection-System-
This repository contained an OpenCV version of YOLOP, a panoptic driving perception network that can handle simultaneously traffic target detection, drivable area segmentation, and lane line detection.

You can find joined to the repository, an onnx file created from the provided weight of YOLOP.

You will find in the repository, a C++ version (main.cpp), a Python version (main.py), an onnx file created from the provided weight of YOLOP and images folder that contains several test images from the bdd100k autopilot dataset.

This program is an opencv inference deployment program based on the recently released project YOLOP by the vision team of Huazhong University of Science and Technology. It can be run using only the opencv library, thus completely getting rid of the dependency of any deep learning framework.

This program has been tested with opencv 4.5.3. It doesn't work with opencv 4.2.0 and below.
