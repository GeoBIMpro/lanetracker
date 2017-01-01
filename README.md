Detects lanes on for an autonomous gokart(plus more!). It contains a lot of experimental code for creating a self driving gokart. The code needs some work to become a demoable project. But the code that exists provides a lot of the base functionality. Someone just needs to go in and plug it all together.

For more information click through the directories

TODO

Improve lane tracker with kmean segmentation
Thread navigation.py and allow for heading nudging
Mathematically solve camera projection matrix

**lanedetect_edges.py** uses edge detection and hough lines to detect lane edges

**lanedetect_threshold.py** uses HSV thresholding. Blue is the left lane. Red is the right lane. Teal is the center lane

## Dependencies:  
- python2.7
- numpy
- opencv3.1.0

## Test Footage
- [test.mp4](https://drive.google.com/file/d/0B75b5hNZE7szZlJTZ09MZG9JT0E/view?usp=sharing)
