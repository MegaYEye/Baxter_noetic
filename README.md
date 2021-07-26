# Baxter_noetic

This is how to install. The code uploaded is wrong and may not be valid 

## Solve QT issue:
```
sudo add-apt-repository ppa:rock-core/qt4
sudo apt-get update
sudo apt-get install libqtcore4 qt4-qmake libqt4-dev
export QT_SELECT=4
```

also, fix:
```
OSError, e -> OSError as e
```

## effort controller
sudo apt-get install ros-noetic-effort-controllers


For SDK, use this:
https://nu-msr.github.io/me495_site/lecture13_rethink.html
and also read:
https://nu-msr.github.io/me495_site/lecture13_rethink.html#using-the-robots



For simulatior, replace the baxter_simulator with this:
git clone https://github.com/EmaroLab/baxter_simulator

then directly do a catkin_make

OPENCV: replace that "NOCHANGES" with -1

quick test:
First, set ROS_MASTER_URI, enable the robot, then
```
rosrun baxter_examples joint_position_keyboard.py

```
