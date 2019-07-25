# Accelerating-Inference-in-Tensorflow-using-TensorRT

## What is TensorRT?

TensorRT is an optimization tool provided by NVIDIA that applies graph optimization and layer fusion, and finds the fastest implementation of a deep learning model. In other words, TensorRT will optimize our deep learning model so that we expect a faster inference time than the original model (before optimization), such as 5x faster or 2x faster. The bigger model we have, the bigger space for TensorRT to optimize the model. Furthermore, this TensorRT supports all NVIDIA GPU devices, such as 1080Ti, Titan XP for Desktop, and Jetson TX1, TX2 for embedded device.

## Library used

Pre-requrement: Install TensorRT by following this tutorial here for Ubuntu dekstop or here for Jetson devices

    Tensorflow 1.12
    OpenCV 3.4.5
    Pillow 5.2.0
    Numpy 1.15.2
    Matplotlib 3.0.0
