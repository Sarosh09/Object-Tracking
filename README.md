# Object-Tracking

## Optical Flow
To characterize and quantify the motion of objects in a video stream

## Dense Optical Flow
Lucas-Kanade method computes optical flow for a sparse feature set (in our example, corners detected using Shi-Tomasi algorithm). OpenCV provides another algorithm to find the dense optical flow. It computes the optical flow for all the points in the frame.

## MeanShift Tracking
The mean-shift algorithm is an efficient approach to tracking objects whose appearance is defined by histograms.

## CamShift Tracking(Continuously Adaptive Mean Shift)
This algorithm tracks an object based on color. This algorithm is based on object hue value
from HSV image. 
