**MockBot Project - URDF Development**

This repository documents the process of developing a **<robotname>_description** launch, urdf, rviz files for the **MockBot** robot that uses a **iRobot Create1 chassis base, lidar, imu, camera**. The development process described here is based on the simple 2 wheel differential drive robot, **sam_bot**, described in Open Navigation NAV2 Tutorial. https://navigation.ros.org/setup_guides/urdf/setup_urdf.html. This package code is deployed with **ros2 Humble** distribution. Different varients document the progress from the basic **sam_bot_description** package configuration to the more complex packge to ne used in a **mockbot_description** package.

For initial installation on a **Ubuntu 22.04 Desktop/ros2 Humble** Workstation, it is suggested that this repository be cloned into a **ROS 2** workspace, e.g. ~/sambot_ws/src. For convenient development, it is suggested to install and configure the Workstation with a **Local** **Git** and **VSCode**, applications and to include a .gitignore ignore file in the **Local** repository as follows to prevent Git from tracking files that are only relevent to the **Local** repository.

**Reference web sites:**
**Git**, Setting up: https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu 

**Configure secure SSH key passphrases**: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/working-with-ssh-key-passphrases 

**VSCode and ssh-key**: https://code.visualstudio.com/docs/setup/linux, https://stackoverflow.com/questions/65113978/vscode-remote-developement-using-ssh-with-passphrase-protected-ssh-key.

**.gitignore:** This file contents are listed below, is saved into the **Local** Desktop **Repository root directory**. Note that the .gitignore file itself is NOT tracked and does not appear in your **Remote** github.com Repository. https://www.w3schools.com/git/git_ignore.asp

#ROS
devel/
log/
build/
install/

#VSCode
.vscode/
**/.vscode/

#.gitignore
/.gitignore
