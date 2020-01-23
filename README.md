# install.me
Here I would collect any guides for installation of different software, middleware, OS...

# MSI GS65 + Ubuntu 18.04 =
## https://medium.com/@carlosero/making-ubuntu-18-04-work-on-msi-gs65-8re-9818f4d9dc9d 
## with
## https://www.reddit.com/r/linux_gaming/comments/8oy876/failed_installing_ubuntu_1604_on_my_new_msi_gs65/

# DELL XPS 15 9570 + Ubuntu 18.04 = 
## https://medium.com/@peterpang_84917/personal-experience-of-installing-ubuntu-18-04-lts-on-xps-15-9570-3e53b6cfeefe 
## with few deviations (no drama)

# ROS intsall 
## http://wiki.ros.org/ROS/Installation

# YARP
## see other file
while installing YARP from sources, 
1) remove libtiff from conda and install libtiff5 (not sure if required) 
2) remove Anaconda from path for this bash session
3) you would probably need few qt libraries (launch yarpview from cli and see error messages)

# CLion, PyCharm
download http://www.jetbrains.com/toolbox/app , install, login and go
CLion + ROS = https://www.jetbrains.com/help/clion/ros-setup-tutorial.html Did not manage to make a startup icon, but starting from shell is OK. 
basically: 
cd /usr/local/bin 
echo "bash PATH_TO_CLION/bin/clion.sh" > clion
sudo chmod +x clion

now use clion from command line


# Don't forget to...
sudo apt-get install vim 
telegram.org

## Pop!_os and dell xps 7590
sudo apt install ubuntu-restricted-extras
