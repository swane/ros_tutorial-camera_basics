Installed from link in 'ROS by example'

Terminal: roslaunch rbx1_vision usb_cam.launch video_device:=/dev/video0
but get an outbuf size mismatch error.

Another terminal to view: rosrun image_view image_view image:=/camera/rgb/imagcolor
Turns on camera but cannot see an image

answer is here:
https://github.com/bosch-ros-pkg/usb_cam/issues/35

so updated the .launch file usb_cam.launch, others may need updating

Launch files reside in:
~/catkin_ws/src/rbx1/rbx1_vision/launch$



