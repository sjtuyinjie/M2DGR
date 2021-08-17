# M2DGR： a Multi-modal and Multi-scenario Dataset for Ground Robots 

## Abstract:

  Intelligent ground robots  have significant application prospects due to their capability to fulfill special missions in complex and dangerous environments.Simultaneous Localization and Mapping (SLAM) is a critical module of robot navigation.Although the research of SLAM has achieved great progress in the past decades,it still has a long way towards mature deployment.Unfortunately, most of the existing datasets of ground robots have limited scenes and scarce categories of sensors, which restricts the development of localization algorithms for ground robots in variable and complex real-world environments,especially in darkness,fog,sharp turns.
Here we introduce M2DGR:a new large-scale dataset collected by a ground robot which contains a full sensor-suite include surrounding and sky-pointing RGB cameras,an infrared camera,an event camera,an inertial measurement unit(IMU),a LIDAR,a consumer grade Global Navigation Satellite System (GNSS) receiver and a GNSS-IMU navigation system with real-time kinematic (RTK) GNSS suite providing centimetre accurate global positioning.The dataset include ample trajectories in highly diverse scenes covering rooms, elevators, streets, parking lots and so on.

  Based on M2DGR, we evaluate the performance of a few state-of-the-art of SLAM algorithms in a few real-world environments, and analyze the scenarios where ground robots are not robust to.For the benefit of the research community,we make the dataset and evaluation results public.Our dataset,development toolkits and more infomation are now available through the link in the footnote.

keywords:Dataset, Multi-model, Multi-scenario,Ground Robot

## 1.Sensor Setup

## 2.Dataset Sequences
[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
### 2.1 Outdoors
Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
gate_01|2021-07-31|16.4g|172s|dark,around gate|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/ET3mU1rvdTpEl8VYvC25q7YByl369y6Hx_OQScBkKlnHXA?e=tSMlqz)
gate_02|2021-07-31|27.3g|327s|dark,loop back|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/EY7fHSh4NnxBvemze1JS8TEBGovus_Lis_gFOyUOm5dK6A?e=cRsdo4)
gate_03|2021-08-04|21.9g|283s|day|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/EUthdjvVIVdFmFxR82jzVqUBubziK6mUbj3tp5gtLqO9rw?e=HLEwuj)


Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
rotation_01|2021-08-03|23.3g|234s|rotation,figure of 8|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
rotation_02|2021-08-07|27.3g|244s|rotation,figure of 8|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)

Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
street_01|2021-08-06|75.8g|1028s|street and buildings,night,zigzag,long-term|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
street_02|2021-08-03|83.2g|1227s|day,long-term|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
street_03|2021-08-06|21.3g|354s|night,back and fourth,full speed|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
street_04|2021-08-03|48.7g|858s|night,around lawn,loop back|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
street_05|2021-08-04|27.4g|469s|night,staight line|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
street_06|2021-08-04|35.0g|494s|night,one turn|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
street_07|2021-08-06|77.2g|929s|dawn,zigzag,sharp turns|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
street_08|2021-08-06|31.2g|491s|night,loop back,zigzag|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
street_09|2021-08-07|83.2g|907s|day,zigzag|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
street_010|2021-08-07|86.2g|910s|day,zigzag|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
walk_01|2021-08-04|21.5g|291s|day,back and fourth|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
### 2.2 Indoors
Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
hall_01|2021-08-01|29.1g|351s|randon walk|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/EWQ2bcxWRgZLtK_eSIgnNmoB-pfPRP57bhaVO5r44dDqkQ?e=uf1GIx)
hall_02|2021-08-08|15.0g|128s|randon walk|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/EaAEMKhvsgJCn0bSvlNOENkBLopgtrR9GRBdUW1MWWFCNA?e=Xyxcdo)
hall_03|2021-08-08|20.5g|164s|randon walk|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
hall_04|2021-08-15|17.7g|181s|randon walk|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/EV0oYa2MNi1HqmhvCM1pbboB1YH9Jn8hhL04IAc-64duUg?e=tadCxw)
hall_05|2021-08-15|35.1g|402s|circle|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/EQRFrzmO2BxFmeAZV_ifTpsBtxG5PoeejazNE7CvyDyqYA?e=8YNKsa)

Sequence Name|Collection Date|Total Size|Duration|Features|Download Link
--|:--|:--:|--:|--:|--:
lift_01|2021-08-04|18.4g|225s|randon walk|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/EZp-yCPxrxNBg5cM_aWualABPM3A3mUHHk0SeQoaxaBClA?e=WqrNwI)
lift_02|2021-08-04|43.6g|488s|randon walk|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/EfXP5V6Yi3tEvQL-Gbaq4QcBldgfv5zXEID_WlNtefAT5A?e=X6QvcW)
lift_03|2021-08-15|22.3g|252s|randon walk|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/EWWG7OgCmTpIj_VZixYTkzsBpuAJtJKO2rNe-EzhHubjwA?e=XnOARY)
lift_04|2021-08-15|27.8g|299s|randon walk|[Download Link](https://sjtueducn-my.sharepoint.com/:u:/g/personal/594666_sjtu_edu_cn/ETrPaBIVaV1EtTVUG9effPIBK1LiJ3pGK93jAdhLZU_Pjg?e=ekVtWl)

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
door_01|2021-08-04|35.5g|461s|outdoor to indoor to outdoor,long-term|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)
door_02|2021-08-04|10.5g|127s|outdoor to indoor,short-term|[Download Link](https://sjtueducn-my.sharepoint.com/:f:/g/personal/594666_sjtu_edu_cn/EstgRJm8ufVIhiol5_D47pwBy94k-uKVH6IFYe5p95hqdw?e=SkYPSe)


## 3.Development Toolkits
### 3.1 to fetch images
### 3.2 to get renix files
### 3.3 ROS drivers for UVC cameras 
### 3.4 other tools
