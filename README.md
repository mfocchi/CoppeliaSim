# CoppeliaSim 4.6.0

This version works with ROS1

This need to be cloned inside Locosim folder to be able to use tractor_simulator.py



to install for ROS2 (ros2 compile only with version 4.5.1 and with clang):

1) checkout branch ros2 (Coppelia 4.5.1)

3) remove ros_packages folder

4) Install these dependencies

   1) lua5.3: `sudo apt install lua5.3 liblua5.3-dev`
   2) luarocks: `sudo apt install luarocks`
   3) xsltproc: `sudo apt install xsltproc`
   4) xmlschema: `pip install xmlschema`

5) export COPPELIASIM_ROOT_DIR=~/ros2_ws/src/CoppeliaSim

6) sudo apt install clang
   export CXX=clang++
   colcon build 

   