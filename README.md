# ת̨ģ����
## ����
```Bash
$ sudo apt-get install ros-kinetic-joint-state-publisher-gui
$ cd ~/catkin_ws/src
$ git clone https://gitee.com/harbin-institute-of-technology-csc/rotor_simulator.git
$ git clone https://gitee.com/harbin-institute-of-technology-csc/drone_simulator.git
$ cd ~/catkin_ws
$ catkin_make
```
## ���н��
�鿴ģ��
```Bash
$ roslaunch et_description display.launch
```
![image](https://gitee.com/harbin-institute-of-technology-csc/rotor_simulator/raw/master/rotor2_rviz.png)
���������ֱ�����
```Bash
$ roslaunch et_simulator laser_weapon_maunal.launch
```
![image](https://gitee.com/harbin-institute-of-technology-csc/rotor_simulator/raw/master/laser_weapon_manual.png)
���������Ӿ��ŷ�
```Bash
$ roslaunch et_simulator laser_weapon_auto.launch
```
