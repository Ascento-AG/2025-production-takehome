## 🚅 Quick start

**Clearpath** is a successful robotic company designing UGV for multiple applications. They provide a suite of software to 
communicate and interact with their robots. Like Ascento their on-robot software is based on ROS2 and leverages many 
standard tools common to the robotics industry.
We would like to test their open source implementation of the robotic stack, so we prepared this repo to install and run 
a simulation. 

In order to make reproducible experiments we are using [Docker :whale:](https://www.docker.com/) to generate a runnable container. 
We followed the instructions [Official Clearpath Documentation](https://docs.clearpathrobotics.com/docs) but something seems to not work yet.
The end goal is to spawn the simulation of the Husky robot and to be able to move it using the teleoperation panel.

<div align="center">
    <img src="https://docs.clearpathrobotics.com/assets/images/driving-7a95dd324bcf6be916e64c1202efb75a.gif" width=600px>
</div>

Unfortunately our engineer, after setting up the initial structure, has left us with little documentation. 
He is chilling in the Everest Mountains and there is no reception there.

Your tasks consists in:
* Understanding the structure of this repository and explaining what each file is responsible for
* Finding out which tools are required to run the simulation
* Fixing bugs in the installation process
* Writing documentation to guide a new developer to get started with the Husky simulation.

What you do not have to do:
* Create new files other than the existing ones
* Install additional packages

Create a new public repository, forking this one and invite `grizzi` and `migueldelaiv`. 
We expect you to take 2.5 hours at most. We appreaciate your effort in sticking to this time. 
It can be a long process to find all the details of a complex software package. If you are not able to solve it in the due time dont worry. We are interested to know the steps you took and how you planned your work.
