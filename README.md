# 2017_fsae_gazebo
# partially working simulator
# has 2017 fsae model
# works with ros indigo and ubuntu 14.04 only
 
based on CAT Vehicle Testbed https://cps-vo.org/node/26591<br/>
<br/>
install ros additional packages from https://cps-vo.org/node/26602 <br/>
mkdir -p ~/catvehicle_ws/src <br/>
cd ~/catvehicle_ws/ <br/>
catkin_make <br/>
copy contents to src <br/>
catkin_make

rosrun teleop_twist_keyboard teleop_twist_keyboard.py <br/>
roslaunch catvehicle catvehicle_skidpan.launch <br/>
gzclient <br/>

