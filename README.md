# ros2cli-snap

Snap for [ros2cli](https://github.com/ros2/ros2cli), the ROS 2 command line interface tools] [1] included with a standard install of any ROS 2 distro.
  
The Snap does not support roslaunch, rospkg, rosrun and custom ROS messages as these require access to the host filesystem.

The [ros2-cheat-sheet](https://github.com/ubuntu-robotics/ros2_cheats_sheet/blob/master/cli/cli_cheats_sheet.pdf) provides examples for commands and their verbs.

Installation Instructions:

* Install ros2cli from a terminal,
  `    snap install ros2-cli --channel=foxy/beta`

* Test your installation,
  `   ros2-cli.ros2 --help`
