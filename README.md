<!--Overview-->
# RadarSurvey-Autonomous
Survey list for radar datasets, papers, and codes (**Autonomous+Robot**)  
Contact: jhchoi93@postech.ac.kr

<!--Dataset-->
## Datasets
| Dataset | Year | Data Type | Annot. Type | Modality | Other | Link | Remarks |
| :----: | :----: | :----: | :----: | :----: | :----: | :----: | :---- |
| nuScenes | 2019 | PC | 3D bbox | C+L+O | T | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Caesar_nuScenes_A_Multimodal_Dataset_for_Autonomous_Driving_CVPR_2020_paper.pdf)<br> [Website](https://www.nuscenes.org/) | * Motional<br> * 23 Class |
| Astyx | 2019 | PC | 3D bbox | C+L | - | [Paper](https://ieeexplore.ieee.org/document/8904734)<br> [Github](https://github.com/under-the-radar/radar_dataset_astyx) | * Astyx<br> * 7 Class |
| Radar-Lidar | 2019 | RA | - | L+O | T, S, E | [Website](https://sites.google.com/view/dgbicra2019-radar-lidar) | * KAIST<br> * Contact |
| Radar RobotCar | 2020 | RA | - | C+L+O | T, S | [Paper](https://arxiv.org/pdf/1909.01300.pdf)<br> [Website](https://oxford-robotics-institute.github.io/radar-robotcar-dataset/documentation) | * Oxford Univ. |
| MulRan | 2020 | RA | - | L+O | T, S | [Paper](https://rpm.snu.ac.kr/publications/gskim-2020-icra.pdf)<br> [Website](https://sites.google.com/view/mulran-pr/home) | * Seoul Nat. Univ.<br> * Contact |
| CARRADA | 2020 | RAD, (RA+RD), PC | 2D bbox (RA, RD), Seg.mask | C | T | [Paper](https://arxiv.org/pdf/2005.01456.pdf)<br> [Github](https://github.com/valeoai/carrada_dataset) | * Valeo AI<br> * 3 Class |
| CRUW | 2021 | RA | Confidence map | C | T | [Paper](https://openaccess.thecvf.com/content/WACV2021/papers/Wang_RODNet_Radar_Object_Detection_Using_Cross-Modal_Supervision_WACV_2021_paper.pdf)<br> [Website](https://www.cruwdataset.org/home) | * Univ. Washington<br> * 3 Class |
| RadarScenes | 2021 | PC | Point-wise | C+O | T | [Paper](https://arxiv.org/pdf/2104.02493.pdf)<br> [Website](https://radar-scenes.com/) | * Mercedes-Benz AG<br> * 11 Class |
| RADDet | 2021 | RAD, (RA+RD) | 3D bbox (RAD) | C | T | [Paper](https://arxiv.org/pdf/2105.00363.pdf)<br> [Github](https://github.com/ZhangAoCanada/RADDet) | * Univ. Ottawa |
| RaDICaL | 2021 | ADC | 2D bbox (RA) | C+D | C, T | [Paper](https://ieeexplore.ieee.org/document/9361086)<br> [Website](https://publish.illinois.edu/radicaldata/) | * UIUC |
| RADIal | 2022 | ADC, RAD, (RA+RD), PC | 2D bbox (RA, RD), Seg. mask | C+L+O | C, T, E | [Paper](https://arxiv.org/pdf/2112.10646.pdf)<br> [Github](https://github.com/valeoai/RADIal) | * Valeo AI<br> * 1 Class |

> **Description for Abbreviations**
> * **[Data Type]** ADC: analog-to-digital converted data, RAD: range-angle-Doppler tensor, PC: point cloud
> * **[Annot. Type]** bbox: bounding box, seg. mask: segmentation mask
> * **[Modality]** C: camera, D: stereo-depth, L: lidar, O: odometry
> * **[Other]** C: complex (magnitude+phase) data, T: temporal data, S: scanned data, E: elevation dimensions are added
> * **[Remarks]** Contact: must contact to authors for data acquisition