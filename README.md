# M2DGR： a Multi-modal and Multi-scenario Dataset for Ground Robots 

## Abstract:

  $~$ Intelligent ground robots  have significant application prospects due to their capability to fulfill special missions in complex and dangerous environments.Simultaneous Localization and Mapping (SLAM) is a critical module of robot navigation.Although the research of SLAM has achieved great progress in the past decades,it still has a long way towards mature deployment.Unfortunately, most of the existing datasets of ground robots have limited scenes and scarce categories of sensors, which restricts the development of localization algorithms for ground robots in variable and complex real-world environments,especially in darkness,fog,sharp turns.
Here we introduce M2DGR:a new large-scale dataset collected by a ground robot which contains a full sensor-suite include surrounding and sky-pointing RGB cameras,an infrared camera,an event camera,an inertial measurement unit(IMU),a LIDAR,a consumer grade Global Navigation Satellite System (GNSS) receiver and a GNSS-IMU navigation system with real-time kinematic (RTK) GNSS suite providing centimetre accurate global positioning.The dataset include ample trajectories in highly diverse scenes covering rooms, elevators, streets, parking lots and so on.

  Based on M2DGR, we evaluate the performance of a few state-of-the-art of SLAM algorithms in a few real-world environments, and analyze the scenarios where ground robots are not robust to.For the benefit of the research community,we make the dataset and evaluation results public.Our dataset,development toolkits and more infomation are now available through the link in the footnote.

keywords:Dataset, Multi-model, Multi-scenario,Ground Robot

## 1.Sensor Setup

## 2.Dataset Sequences
[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
### 2.1 Outdoors
Sequence Name|Collection Date|Total Size|Duration|Features
--|:--|:--:|--:|--:
street_01|2021-08-14|xxg|xxs|street and buildings,night,zigzag,long-term
street_02|2021-08-14|xxg|xxs|day,long-term
street_03|2021-08-14|xxg|xxs|night,back and fourth,full speed
street_04|2021-08-14|xxg|xxs|night,around lawn,loop back
street_05|2021-08-14|xxg|xxs|night,staight line
street_06|2021-08-14|xxg|xxs|night,one turn
street_07|2021-08-14|xxg|xxs|dawn,zigzag,sharp turns
street_08|2021-08-14|xxg|xxs|night,loop back,zigzag
street_09|2021-08-14|xxg|xxs|day,zigzag
street_010|2021-08-14|xxg|xxs|day,zigzag



## 3.Development Toolkits
### 3.1 to fetch images
### 3.2 to get kml files
