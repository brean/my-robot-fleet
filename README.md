# robot-fleet
Information of the robots (and useful robotic hardware) I privately own.

|Name|Description|possible/planned custom Software|
|--|--|--|
|OmniBot|Omniwheel-platform controlled by Raspberry Pi 4 and Raspberry Pico, SLAMTEC RPLidar for Navigation|(**planned**) custom µROS to control the wheels, wifi-connection from the Raspberry Pi 4, ROS2 navigation stack see [robot](../../../robot)|
|SpaceBot light|A robot based on the [VATOS Remote Control Car](https://vatostoys.com/collections/rc-toys/products/vatos-brushless-rc-car-1-16) and a raspberry pi with [camera](https://www.amazon.de/-/en/dp/B095NQT3GJ)|(**planned**) autonomous navigation testbed for SLAM/Visual Odometry|
|cheap-bot "prototype #1"|Cheapest possible robot (< 40 Euro), just a MDF plate with an ESP32-CAM with 2 motors/wheels as teaching platform to give to children who want to learn programming|(**planned**) custom control software, maybe microROS ROS2 nodes|
|ROZMO|Anki COZMO robot|(**planned**) pycozmo Integration with ros2|
|ARDrone|AR.Drone 2.0 Elite Edition quadcopter|(**maybe**) ROS2 AR.Drone Integration|
|DirtBot|Just my vacuum (for now)|(**maybe**)upgrade with raspberry pi, RP-LIDAR trolley and custom ROS2 behavior node|

## fleet control
All robots should be controlable using the [robot-fleet-control](https://github.com/Fleet-Control).
