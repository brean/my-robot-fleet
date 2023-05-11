# robot-fleet
Information of the robots (and useful robotic hardware) I privately own.

|Name|Description|possible/planned custom Software|
|--|--|--|
|COZMO|Anki COZMO robot|(**planned**) pycozmo Integration with ros2|
|ARDrone|AR.Drone 2.0 Elite Edition quadcopter|(**maybe**) ROS2 AR.Drone Integration|
|"robot"|Omniwheel-platform controlled by arduino tiny and an ESP8266-cam|(**planned**) custom ardunio-c-control for the wheels, wifi-connection from the ESP to an external ROS1/ROS2 node, see [robot](../../../robot)|
|Deebot N97S|Just my vacuum (for now)|(**maybe**)upgrade with raspberry pi, RP-LIDAR and custom ROS2 behavior node|
|CuD bot "prototype #1"|Cheapest possible robot, just a paper box with an ESP32-CAM with 2 motors/wheels as teaching platform to give to children who want to learn programming|(**planned**) custom control software, maybe microROS ROS2 nodes|
|SPACE-light bot|A robot based on the [VATOS Remote Control Car](https://vatostoys.com/collections/rc-toys/products/vatos-brushless-rc-car-1-16) and a raspberry pi with [camera](https://www.amazon.de/-/en/dp/B095NQT3GJ)|(**planned**) autonomous navigation testbed for SLAM/Visual Odometry|

## fleet control
All robots should be controlable using the [robot-fleet-control](https://github.com/Fleet-Control).
