# Autolabor-Simulation
## Introduction
The project is the simualtion of SLAM (including positioning and mapping、path planning).what's more,we also implement the object detection function on the Autolabor car. Here's what we did:
- Positioning and mapping indoors using Gmapping algorithm
- Positioning and mapping outdoors using catographer algorithm
- path planing using DWA and A* algorithms
- object detection using YoloV3 algorithm
- modeling of Autolabor car in solidworks2018
## Requirement
- Ubuntu16.04LTS
- ROS-kinetic
- A GPU with 2GB memory minimum
- Python3
- GCC
## Content Tree
```
|-- src
|   |-- CMakeLists.txt
|   |-- autolabor_description       Autolabor model
|   |-- autolabor_driver            Autolabor driver
|   |-- autolabor_keyboard_control  keyboard_control 
|   |-- autolabor_navigation        path planing
|   |-- autolabor_teleop            keyboard_control 
|   |-- autolabor_world             the world map
|-- build                           config 
|-- devel                           config
```
## Results
**Autolabor Model**
![model](./images/autorlabor.png)
**Gmapping**
![Gmapping](./images/gmapping.png)
**Catographer**
![catographer](./images/catorgraph.png)
**Navigation**
![navigation](./images/nav.png)
**World_map**
![map](./images/map.png)
**YoloV3**
![yolo](./images/yolo.png)
