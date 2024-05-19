# *Build* 
1. Create a Work Space
```sh
  mkdir -p ~/ros2_ws/src
```
2. cd into src of Workspace
```sh
  cd ~/ros2_ws/src
```
3. Clone the repo
```sh
  git clone https://github.com/Ali-Eimaan/six_dof_arm_pkgs.git
```
4. cd to Workspace
```sh
  cd ~/ros2_ws
```
5. Build The pkgs
```sh
  colcon build
```
6. Source setup.bash of pkgs
```sh
  source install/setup.bash
```
# *Usage*
To launch simulation in gazebo and rviz the following command needs to be executed. 
```sh
  ros2 launch six_dof_arm launch_sim.launch.py
```
This command will,
1. Run Gazebo
2. Spawn Robot
3. Launch Rviz
