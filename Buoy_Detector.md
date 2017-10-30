# Buoy Detector

Action server to detect buoy objects in an image and classify them by colour. It uses trained neural networks for detection.

## Usage

```
rosrun state_estimation buoy_detector.py
```

## Goal

### Image
* sensor_msgs/Image:
	* ROS image from the front camera

## Result

## Bounding Boxes

* buoy_msgs/BoundingBoxes:
	* BoundingBox[]
* buoy_msgs/BoundingBox: 
	* int64 xmin
	* int64 ymin
	* int64 xmax
	* int64 ymax
	* float64 probability
	* string colour

