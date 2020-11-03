# ME495 Image Example
A basic example of a ROS image processing node

# Usage
To blur a face:
`roslaunch me495_image usb_cam.launch video_device:=/dev/videoX`
* `video_device` specifies which video device to open

`nodes/bridge` demonstrates the basic cv bridge functionality