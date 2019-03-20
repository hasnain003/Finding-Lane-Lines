# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

Overview
---

When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

In this project I have detected lane lines in images and videos using Python and OpenCV.  OpenCV means "Open-Source Computer Vision", which is a package that has many useful tools for analyzing images.  


Pipeline Description
======================
This pipline consist of 6 steps:
1. Converting the images into grayscale.
2. Defining a kernel size and apply Gaussian smoothing.
3. Defining our parameters for Canny Edge Detection and apply.
4. Selecting the region of interest.
5. Applying Hough Tranform line detection.
6. Combining the images

Result
========
![](https://github.com/hasnain003/Finding-Lane-Lines/blob/master/test_videos_output/demo.gif?raw=true)

Potential Shortcoming with current pipeline
===========================================
* Don't work well on curve lane lines on the road

Contribute
==============
1. Fork it
2. Create your feature branch: `git checkout -b my_new_feature`
3. Commit your changes: `git commit -m "Add some feature"`
4. Push to the branch: `git push origin my_new_feature`
5. Submit a Pull Request :sunglasses:


