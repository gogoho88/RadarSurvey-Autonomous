<!--Overview-->
# RadarSurvey-Autonomous
Survey list for radar datasets, papers, and codes (**Autonomous**)  
made by Jae-Ho Choi

<!--Dataset-->
## Datasets
| Dataset | Year | Data Type | Annot. Type | Modality | Other | Link | Remarks |
| :----: | :----: | :----: | :----: | :----: | :----: | :----: | :---- |
| nuScenes | 2019 | PC | 3D bbox | C+L+O | Temporal | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Caesar_nuScenes_A_Multimodal_Dataset_for_Autonomous_Driving_CVPR_2020_paper.pdf)<br> [Website](https://www.nuscenes.org/) | * Motional |
| Radar RobotCar | 2020 | RA | - | C+L+O | Temporal, $360^{\circ}$ Scanned | [Paper](https://arxiv.org/pdf/1909.01300.pdf)<br> [Website](https://oxford-robotics-institute.github.io/radar-robotcar-dataset/documentation) | * Oxford Univ. |
| CARRADA | 2020 | RAD, (RA+RD), PC | 2D bbox (RA, RD), Seg.mask | C | Temporal | [Paper](https://arxiv.org/pdf/2005.01456.pdf)<br> [Github](https://github.com/valeoai/carrada_dataset) | * Valeo AI<br> * 3 Class |
| RADIal | 2022 | ADC, RAD, (RA+RD), PC | 2D bbox (RA, RD), Seg. mask | C+L+O | <span style="color:red">Complex</span>, Temporal | [Paper](https://arxiv.org/pdf/2112.10646.pdf)<br> [Github](https://github.com/valeoai/RADIal) | * Valeo AI |

> **Note:** Radar data can be realised in various formats according to the signal processing pipelines, e.g., analog-to-digital ('ADC') data, range-angle-Doppler ('RAD') tensor, point cloud ('PC'). Radar reflections are often acquired with other sensor modalities such as camera ('C'), lidar ('L'), and odometry ('O').