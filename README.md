# armrobot_moveit
Using moveit for motion planning

## Dependencies

For moveit setup tutorial, click [here](http://docs.ros.org/en/kinetic/api/moveit_tutorials/html/doc/setup_assistant/setup_assistant_tutorial.html). (make sure select the right version of your ros(ex) kinetic,melodic,noetic)
  
  You don't need to know just for using.
  
For moveit installation guide, click [here](http://docs.ros.org/en/melodic/api/moveit_tutorials/html/doc/getting_started/getting_started.html).

    sudo apt-get install ros-melodic-catkin python-catkin-tools
    sudo apt install ros-melodic-moveit

if your ros version is kinetic or noetic, change melodic to your installed ros version.

## How to install

Move to your workspace

    cd ~/catkin_ws/src
    git clone https://github.com/yongarry/armrobot_moveit.git
    catkin_make

## How to launch

    roslaunch armrobot_moveit demo.launch
