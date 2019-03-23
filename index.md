## RoboCup Simulation (Secondary/Open)

This page gives some install, set up and introduction to use Webots for a Rescue based simulation setup. 

### About

This rescue scenario based simulation competition will use [Webots](https://cyberbotics.com/). Webots is an open-source robot simulator. It is widely used in industry, education and research. The Webots project started in 1996, initially developed at the Swiss Federal Institute of Technology (EPFL) in Lausanne, Switzerland.  The simulator uses the physics engine ODE (Open Dynamics Engine) for detecting of collisions and simulating rigid body dynamics. The ODE library allows one to accurately simulate physical properties of objects such as velocity, inertia and friction.  It is used widely in both research and teaching, examples of useage can be found [here](https://www.youtube.com/user/cyberboticswebots).

<iframe width="300" align="centre" src="https://www.youtube.com/embed/O7U3sX_ubGc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Controllers for robots can be developed in a variety of different lanugages including C, Python and MatLab.  Although Python will be used in these tuotorials, teams are welcome to use any of the alternative languages which are provided.  

![alt text](logo.jpg "Combination of Environments")


### Rules

This competitions focuses on an abstraction of a rescue scenario.  A world will be provided which includes 'victims' which are represented by balls.  These balls victims must be located, it must be determined if these balls are 'dead' or 'alive' and then the must bereturned to the starting point of each teams robot.  
* Dead victims will be represented by balls which are grey and have a sad face
* Alive victims will be represented by balls which are pink and have a happy face.

### Installation

The Webots software (which is free!) can be downloaded from [here](https://cyberbotics.com/download).  Installations are provided for Windows, Mac and Linux.  Further information on the installation process can be found [here](https://cyberbotics.com/doc/guide/installing-webots).  

Python should also be installed as Python is used to create the worlds.  Webots requires Pytohn 2.6 or 3.6, we will assume version 3.6 is used.  Instructions on installing Python can be found [here](M
https://cyberbotics.com/doc/guide/using-python).  For Windows PCs it is key that the PATH should include the location of the python installation.

Additionally if you would like to use Matlab/C/C++ more information can be found here:
* [Using Matlab.](https://cyberbotics.com/doc/guide/using-matlab) Version 2015b only
* [UsingC/C++.](https://cyberbotics.com/doc/guide/using-c) Webots includes C/C++ compiler


### Getting Started


### Initial Activities
* Navigate around (avoid walls using the ultasound sensor*
* 

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
