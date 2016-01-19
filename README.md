# ros-quadcopter-tx-keyboard-controler
Model airplane TX style keyboard controler for quadcopter in ROS

This Python script publish /cmd_vel (geometry_msgs/Twist) according to keyboard input.
Usage mimic a model airplane TX in mode 2 : throttle and yaw left hand, pitch and roll right and
Warning : key position is from an AZERTY keyboard.
    --------------------------------------------------
    h:       Print this menu
    Moving around:
        z               i
    q   s   d       j   k   l
    
    z : Up
    s : Down
    q : Turn left
    d : Turn right

    i : Forward
    k : Backward
    j : Slide left
    l : Slide right

    z : up
    anything else : stop moving
 
    x :   Exit
    --------------------------------------------------
     Released under BSD License
