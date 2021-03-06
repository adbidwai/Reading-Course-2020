# Reading-Course-2020
Project repository for the reading course 2020

## Instructions to run the final project

* Install ROS Melodic on your Ubuntu 18.04 OS by following the instructions on official [ROSWIki](http://wiki.ros.org/melodic/Installation/Ubuntu)
* Clone this repository : </br>
  ```
  git clone https://github.com/adbidwai/Reading-Course-2020.git
  ```
* Build the `smart_wheelchair` package inside the `rc_ws` workspace : </br>
  ```
  cd Reading-Course-2020
  cd rc_ws
  catkin build
  ```
* To start the simulation launch the robot in the world file and run the `start.py` script after sourcing your workspace : </br>
  ```
  source ./devel/setup.bash
  roslaunch smart_wheelchair line_follower_world.launch 
  rosrun smart_wheelchair start.py
  ```
* Youtube video link for project demo : https://www.youtube.com/watch?v=wA5UWTaoHeA&feature=youtu.be 

## Contributors : 
* [Eash Vrudhula](https://github.com/evrudhula)
* [Wahib Kapdi](https://github.com/Kanchuking1)
* [Aditya Bidwai](https://github.com/adbidwai)
* [Vishal Singh](https://github.com/vishalbhsc)
* [Aadhar Sharma](https://github.com/aadhar218)
* [Anirudh Panwar](https://github.com/AnirudhPanwar)
* [Advait Kulkarni](https://github.com/advaitkulkarni2000)

