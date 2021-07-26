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
