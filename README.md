# Baxter_noetic

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

For simulatior, replace the baxter_simulator with this:
git clone https://github.com/EmaroLab/baxter_simulator

then directly do a catkin_make

OPENCV: replace that "NOCHANGES" with -1
