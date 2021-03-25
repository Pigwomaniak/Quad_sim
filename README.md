# drone_sim
Repository with Gazebo models and worlds 

To start using:
cd catkin_ws/src
git clone https://github.com/Pigwomaniak/drone_sim.git


To add models:
echo "GAZEBO_MODEL_PATH=${GAZEBO_MODEL_PATH}:$HOME/catkin_ws/src/drone_sim/models" >> ~/.bashrc
source ~/.bashrc


To start simulation:
roslaunch drone_sim runway3.launch
