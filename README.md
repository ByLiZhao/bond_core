# bond_core
A forked version of [ros/bond_core](https://github.com/ros/bond_core).

The purpose of this repo is to create and maintain a foxy-devel branch for ROS2-Foxy distribution. 
The "ros2" branch of the original repo builds against Rolling Ridley, the unstable distribution of ROS, and there is not a branch for Foxy distribution as of Dec. 28th, 2020.

## Assumptions:
1. OS: Ubuntu 20.04 (Focal Fossa)
2. ROS2 is installed from Debian packages from the official source, either with
```bash
sudo apt install ros-foxy-desktop
```
or 
```bash
sudo apt install ros-foxy-ros-base
```
