# Stereolabs ZED - YOLO in Python or C++

This package lets you use YOLO the deep learning object detector using the ZED stereo camera in Python 3 or C++.

The left image will be used to display the detected objects alongside the distance of each, using the ZED Depth.


![](./preview.png "ZED YOLO")


## Prerequisites

- Windows 7 64bits or later, Ubuntu 16.04
- [ZED SDK](https://www.stereolabs.com/developers/) and its dependencies ([CUDA](https://developer.nvidia.com/cuda-downloads))

## Setup YOLO Python

Please refer to [darknet_zed_python](./darknet_zed_python)

## Setup YOLO C++

Please refer to [darknet_zed_cpp](./darknet_zed_cpp)

### Note

On Windows the C++ sample might crash at startup, it is recommended to use the python version instead