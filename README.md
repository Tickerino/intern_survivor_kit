# intern_survivor_kit
# This is a guide for intern dummies to deal with Robotics & IoT

Open Source Operating System: Linux Ubuntu basics
=================================================

FIRST IMPORTANT NOTE!!! INSTALL UBUNTU!!!

Ingredient:   
    i.  A workstation, either desktop or laptop  
    ii. An empty USB drive  

How:   
    i.   Ask your supervisor which version of Ubuntu will be used over the period and download it from Ubuntu site.  
    ii.  Burn the image file downloaded from the website to the USB drive,recommended application: Etcher.io  
    iii. Reboot your workstation with the USB drive plugged in, then go to BIOS and boot from the USB  
    iv.  Decide whether dual boot your workstation, if not, the pre-installed OS will be wiped off from your workstation.  

-------------------------------------------------------------------

Understand the basics command of Ubuntu Terminal!

The most used command and operation can be found in the link:
https://help.ubuntu.com/community/UsingTheTerminal

-------------------------------------------------------------------


Robotic Operating System: ROS basics
====================================

Installing ROS:

ROS can be easily installed by looking into URL below:
http://www.ros.org/install/

The thing that need to be noticed is which version you needed.
Because I use Kinetic, so I had wrote a script that allow you to install ROS with one execute command.

The scripts can be clone from github with URL:
https://github.com/Tickerino/ROS_kinetic_install

--------------------------------------------------------------------

Practice on ROS:

There are also a lot of useful tutorial at the ROS website, and it's good to learn the basic from there:
http://wiki.ros.org/ROS/Tutorials

--------------------------------------------------------------------

Useful ROS packages:

Besides tutorials, there are a lot of ROS packages which will be be used quite often provided on the ROS website.
m
Some of the example are:  
teleop_twist_keyboard - enable remote control robot with keyboard  
tf - let user track multiple coordinate frames of robot  
rviz - 3D visualization tools, good for AGV's map visualization  
robot_localization - Localizing robot by estimating the sensors data  

---------------------------------------------------------------------

Useful Tips
===========

i.  Always backup your work into github in case your workstation down.

The following command lines can check the history and update the repository:

git status  
git add -A  
git commit -m "filename"  
git log  
git push  

ii. Accessing file directory of micro-computer such as Raspberry Pi.

First step you need to connect to the micro-computer with Ethernet or Wifi and get the IP address of it.  
Next, open Linux file directory and select connect to server, key in the relevant IP address and connect.
Afterwards, the micro-computer folder will be shown on the directory and you can access the file within it.
