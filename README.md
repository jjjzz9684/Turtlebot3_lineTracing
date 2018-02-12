# Turtlebot3_lineTracing

#### 사용한 open source

raspicam
 ```
$cd ~/catkin_ws/src
$git clone https://github.com/fpasteau/raspicam_node.git
$cm
 ```
#### 실행 (turtlebot side)
```
$roscore
$rosrun raspicam raspicam_raw_node
$rosservice call camera/start_capture
```
