# drone_sim
## General info
This repository contains Gazebo models and worlds for drone simulation.

## Setup
To start start simulations is required to have installed:
* ArduCopter
* ardupilot_gazebo plugin
 
To download:
```
$ cd catkin_ws/src
$ git clone https://github.com/Pigwomaniak/drone_sim.git
```

To add models:
```
$ echo "GAZEBO_MODEL_PATH=${GAZEBO_MODEL_PATH}:$HOME/catkin_ws/src/drone_sim/models" >> ~/.bashrc
$ source ~/.bashrc
```
## Run
To start simulation at world named runway3:
```
$ roslaunch drone_sim runway3.launch
```
To start sitl copy startsitl.sh to home diredtory and run:
```
$ ./startsitl.sh
```
To start mavros (communication witch ardupilot):
```
$ roslaunch drone_sim apm.launch
```

