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
## Content tree
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
![model](https://pic.imgdb.cn/item/60a9d8d535c5199ba7b68077.png)
**Gmapping**
![Gmapping](https://pic.imgdb.cn/item/60a9d91435c5199ba7b89c72.png)
**Catographer**
![catographer](https://pic.imgdb.cn/item/60a9eb0a35c5199ba76647d3.png)
**Navigation**
![navigation](https://pic.imgdb.cn/item/60a9eb3935c5199ba7680874.png)
**World_map**
![map](https://pic.imgdb.cn/item/60a9eb6d35c5199ba76a02e6.png)
**YoloV3**
![yolo](https://pic.imgdb.cn/item/60a9eba335c5199ba76c0ae2.png)