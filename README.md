<!--Overview-->
# RadarSurvey-Autonomous
Survey list for radar datasets, papers, and codes (**Autonomous+Robot**)  
Contact: jhchoi93@postech.ac.kr

<!--Dataset-->
## Datasets
| Dataset | Year | Data Type | Annot. Type | Modality | Other | Link | Remarks |
| :----: | :----: | :----: | :----: | :----: | :----: | :----: | :---- |
| nuScenes | 2019 | PC | 3D bbox | 6C+L+5R+O | T | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Caesar_nuScenes_A_Multimodal_Dataset_for_Autonomous_Driving_CVPR_2020_paper.pdf)<br> [Website](https://www.nuscenes.org/) | * Motional<br> * 23 Class |
| Astyx | 2019 | PC | 3D bbox | C+L+R | - | [Paper](https://ieeexplore.ieee.org/document/8904734)<br> [Github](https://github.com/under-the-radar/radar_dataset_astyx) | * Astyx<br> * 7 Class |
| Radar-Lidar | 2019 | RA | - | L+R+O | T, S, E | [Website](https://sites.google.com/view/dgbicra2019-radar-lidar) | * KAIST<br> * Contact |
| Radar RobotCar | 2020 | RA | - | 4C+4L+R+O | T, S | [Paper](https://arxiv.org/pdf/1909.01300.pdf)<br> [Website](https://oxford-robotics-institute.github.io/radar-robotcar-dataset/documentation) | * Oxford Univ. |
| MulRan | 2020 | RA | - | L+R+O | T, S | [Paper](https://rpm.snu.ac.kr/publications/gskim-2020-icra.pdf)<br> [Website](https://sites.google.com/view/mulran-pr/home) | * Seoul Nat. Univ.<br> * Contact |
| CARRADA | 2020 | RAD, (RA+RD), PC | 2D bbox (RA, RD), Seg.mask | C+R | T | [Paper](https://arxiv.org/pdf/2005.01456.pdf)<br> [Github](https://github.com/valeoai/carrada_dataset) | * Valeo AI<br> * 3 Class |
| CRUW | 2021 | RA | Confidence map | 2C+2R | T | [Paper](https://openaccess.thecvf.com/content/WACV2021/papers/Wang_RODNet_Radar_Object_Detection_Using_Cross-Modal_Supervision_WACV_2021_paper.pdf)<br> [Website](https://www.cruwdataset.org/home) | * Univ. Washington<br> * 3 Class |
| RadarScenes | 2021 | PC | Point-wise | C+4R+O | T | [Paper](https://arxiv.org/pdf/2104.02493.pdf)<br> [Website](https://radar-scenes.com/) | * Mercedes-Benz AG<br> * 11 Class |
| RADDet | 2021 | RAD, (RA+RD) | 3D bbox (RAD) | 2C+R | T | [Paper](https://arxiv.org/pdf/2105.00363.pdf)<br> [Github](https://github.com/ZhangAoCanada/RADDet) | * Univ. Ottawa<br> * 6 Class |
| RaDICaL | 2021 | ADC | 2D bbox (RA) | C+D+R | C, T | [Paper](https://ieeexplore.ieee.org/document/9361086)<br> [Website](https://publish.illinois.edu/radicaldata/) | * UIUC |
| RADIal | 2022 | ADC, RAD, (RA+RD), PC | 2D bbox (RA, RD), Seg. mask | C+L+R+O | C, T, E | [Paper](https://arxiv.org/pdf/2112.10646.pdf)<br> [Github](https://github.com/valeoai/RADIal) | * Valeo AI<br> * 1 Class |

> **Description & Abbreviations**
> * **[Data Type]** ADC: analog-to-digital converted data, RAD: range-angle-Doppler tensor, PC: point cloud
> * **[Annot. Type]** bbox: bounding box, seg. mask: segmentation mask
> * **[Modality]** C: camera, D: stereo-depth, L: lidar, R: radar, O: odometry
> * **[Other]** C: complex (magnitude+phase) data, T: temporal data, S: scanned data, E: elevation dimensions are added
> * **[Remarks]** Contact: must contact to authors for data acquisition

<!--Paper-->
## Papers
### AI+Radar (Encoding aspect)
| Year | Journal | Encoding | Dataset | Link |
| :----: | :----: | :----: | :----: | :----: |
| 2020 | IEEE RAL | 1xRxAxD : 3D CNN | Private | [Paper](https://arxiv.org/pdf/2004.12165.pdf)<br> [Github](https://github.com/tudelft-iv/RTCnet/blob/master/README.md) | 
| 2021 | CRV | DxRxA : 2D CNN | RADDet | [Paper](https://arxiv.org/pdf/2105.00363.pdf)<br> [Github](https://github.com/ZhangAoCanada/RADDet) | 
| 2021 | ICCV | TxAxD+TxRxD+TxRxA : 3D-2D CNN  | CARRADA | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Ouaknine_Multi-View_Radar_Semantic_Segmentation_ICCV_2021_paper.pdf)<br> [Github](https://github.com/valeoai/MVRSS) | 

> **Description & Abbreviations**
> * **[Encoding]** Left : Right corresponds to the dims. of input radar tensor and its encoding structure, respectively.
> * **[Encoding-Left]** R: range, A: azimuth angle, D: Doppler
