# M2DGR： a Multi-modal and Multi-scenario Dataset for Ground Robots 

## Abstract:

  Intelligent ground robots  have significant application prospects due to their capability to fulfill special missions in complex and dangerous environments.Simultaneous Localization and Mapping (SLAM) is a critical module of robot navigation.Although the research of SLAM has achieved great progress in the past decades,it still has a long way towards mature deployment.Unfortunately, most of the existing datasets of ground robots have limited scenes and scarce categories of sensors, which restricts the development of localization algorithms for ground robots in variable and complex real-world environments,especially in darkness,fog,sharp turns.
Here we introduce M2DGR:a new large-scale dataset collected by a ground robot which contains a full sensor-suite include surrounding and sky-pointing RGB cameras,an infrared camera,an event camera,an inertial measurement unit(IMU),a LIDAR,a consumer grade Global Navigation Satellite System (GNSS) receiver and a GNSS-IMU navigation system with real-time kinematic (RTK) GNSS suite providing centimetre accurate global positioning.The dataset include ample trajectories in highly diverse scenes covering rooms, elevators, streets, parking lots and so on.

  Based on M2DGR, we evaluate the performance of a few state-of-the-art of SLAM algorithms in a few real-world environments, and analyze the scenarios where ground robots are not robust to.For the benefit of the research community,we make the dataset and evaluation results public.Our dataset,development toolkits and more infomation are now available through the link in the footnote.

keywords:Dataset, Multi-model, Multi-scenario,Ground Robot

## 1.Sensor Setup

## 2.Dataset Sequences

### 2.1 Outdoors
![image](https://github.com/sjtuyinjie/mypics/blob/master/outdoortraj.jpg)
Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
gate_01|2021-07-31|16.4g|172s|dark,around gate|[To be done](https://github.com/sjtuyinjie/M2DGR)
gate_02|2021-07-31|27.3g|327s|dark,loop back|[To be done](https://github.com/sjtuyinjie/M2DGR)
gate_03|2021-08-04|21.9g|283s|day|[To be done](https://github.com/sjtuyinjie/M2DGR)


Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
rotation_01|2021-08-03|23.3g|234s|rotation,figure of 8|[To be done](https://github.com/sjtuyinjie/M2DGR)
rotation_02|2021-08-07|27.3g|244s|rotation,figure of 8|[To be done](https://github.com/sjtuyinjie/M2DGR)

Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
street_01|2021-08-06|75.8g|1028s|street and buildings,night,zigzag,long-term|[To be done](https://github.com/sjtuyinjie/M2DGR)
street_02|2021-08-03|83.2g|1227s|day,long-term|[To be done](https://github.com/sjtuyinjie/M2DGR)
street_03|2021-08-06|21.3g|354s|night,back and fourth,full speed|[To be done](https://github.com/sjtuyinjie/M2DGR)
street_04|2021-08-03|48.7g|858s|night,around lawn,loop back|[To be done](https://github.com/sjtuyinjie/M2DGR)
street_05|2021-08-04|27.4g|469s|night,staight line|[To be done](https://github.com/sjtuyinjie/M2DGR)
street_06|2021-08-04|35.0g|494s|night,one turn|[To be done](https://github.com/sjtuyinjie/M2DGR)
street_07|2021-08-06|77.2g|929s|dawn,zigzag,sharp turns|[To be done](https://github.com/sjtuyinjie/M2DGR)
street_08|2021-08-06|31.2g|491s|night,loop back,zigzag|[To be done](https://github.com/sjtuyinjie/M2DGR)
street_09|2021-08-07|83.2g|907s|day,zigzag|[To be done](https://github.com/sjtuyinjie/M2DGR)
street_010|2021-08-07|86.2g|910s|day,zigzag|[To be done](https://github.com/sjtuyinjie/M2DGR)
walk_01|2021-08-04|21.5g|291s|day,back and fourth|[To be done](https://github.com/sjtuyinjie/M2DGR)
### 2.2 Indoors
Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
hall_01|2021-08-01|29.1g|351s|randon walk|[To be done](https://github.com/sjtuyinjie/M2DGR)
hall_02|2021-08-08|15.0g|128s|randon walk|[To be done](https://github.com/sjtuyinjie/M2DGR)
hall_03|2021-08-08|20.5g|164s|randon walk|[To be done](https://github.com/sjtuyinjie/M2DGR)
hall_04|2021-08-15|17.7g|181s|randon walk|[To be done](https://github.com/sjtuyinjie/M2DGR)
hall_05|2021-08-15|35.1g|402s|circle|[To be done](https://github.com/sjtuyinjie/M2DGR)

Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
lift_01|2021-08-04|18.4g|225s|randon walk|[To be done](https://github.com/sjtuyinjie/M2DGR)
lift_02|2021-08-04|43.6g|488s|randon walk|[To be done](https://github.com/sjtuyinjie/M2DGR)
lift_03|2021-08-15|22.3g|252s|randon walk|[To be done](https://github.com/sjtuyinjie/M2DGR)
lift_04|2021-08-15|27.8g|299s|randon walk|[To be done](https://github.com/sjtuyinjie/M2DGR)

Sequence Name|Collection Date|Total Size|Duration|Features
--|:--|:--:|--:|--:
room_01|2021-07-30|14.0g|72s|street and buildings,night,zigzag,long-term
room_02|2021-07-30|15.2g|75s|day,long-term
room_03|2021-07-30|26.1g|128s|night,back and fourth,full speed
room_dark_01|2021-07-30|20.2g|111s|street and buildings,night,zigzag,long-term
room_dark_02|2021-07-30|30.3g|165s|day,long-term
room_dark_03|2021-07-30|22.7g|116s|night,back and fourth,full speed
room_dark_04|2021-08-15|29.3g|143s|street and buildings,night,zigzag,long-term
room_dark_05|2021-08-15|33.0g|159s|day,long-term
room_dark_06|2021-08-15|35.6g|172s|night,back and fourth,full speed

### 2.3 alternative indoors and outdoors
Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
door_01|2021-08-04|35.5g|461s|outdoor to indoor to outdoor,long-term|[To be done](https://github.com/sjtuyinjie/M2DGR)
door_02|2021-08-04|10.5g|127s|outdoor to indoor,short-term|[To be done](https://github.com/sjtuyinjie/M2DGR)


## 3.Development Toolkits
### 3.1 to fetch images
For rosbag users,just type 
rosrun
### 3.2 to get renix files
### 3.3 ROS drivers for UVC cameras 
### 3.4 other tools
