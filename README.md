## Build
```Bash
$ sudo apt-get install ros-kinetic-joint_state_publisher_gui
$ cd ~/catkin_ws/src
$ git clone https://gitee.com/harbin-institute-of-technology-csc/rotor_simulator.git
$ cd ~/catkin_ws
$ catkin_make
```
## Run
�鿴ģ��
```Bash
$ roslaunch rotor_description display.launch
```
���������ֱ�����
```Bash
$ roslaunch rotor_gazebo laser_weapon_maunal.launch
```
���������Ӿ��ŷ�
```Bash
$ roslaunch rotor_gazebo laser_weapon_auto.launch
```