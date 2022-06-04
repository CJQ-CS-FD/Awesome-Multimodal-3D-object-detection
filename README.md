# Awesome-Multi-modal-3D-object-detection

![img](https://raw.githubusercontent.com/GewelsJI/VPS/main/assets/the-reading-list.png)

This repository will share the classification, paper, code, and notes of awesome multi-modal 3D object detection papers for everyone interested in multi-modal 3D object detection. In the tables, 'M' denotes modality, 'T' denotes task and 'w/o code' means no code is available yet.

## Transformer based 3D detection methods

| Paper | Method | Code and Result | Notes |
| ----- | ------ | --------------- | ----- |
|       |        |                 |       |

## BEV-based 3D detection methods

| Paper                                                        | Method    | M & T   | Code and Result                                              | Notes |
| ------------------------------------------------------------ | --------- | ------- | ------------------------------------------------------------ | ----- |
| BEVFusion: Multi-Task Multi-Sensor Fusion with Unified Bird's-Eye View Representation [(arxiv 2022)](https://bevfusion.mit.edu/) | BEVFusion | L+C,D+S | [w/o code]([mit-han-lab/bevfusion: BEVFusion: Multi-Task Multi-Sensor Fusion with Unified Bird's-Eye View Representation (github.com)](https://github.com/mit-han-lab/bevfusion)), nuScenes det mAP: 70.2, val map seg mIoU 62.7 |       |
| BEVFormer: Learning Bird’s-Eye-View Representation from Multi-Camera Images via Spatiotemporal Transformers [(arxiv 2022)](https://arxiv.org/pdf/2203.17270.pdf) | BEVFormer | C,D+S   | [w/o code](https://github.com/zhiqi-li/BEVFormer), nuScenes mAP 0.412, val |       |



## Temporal object detection methods

| Paper                                                        | Method | Code and Result | Notes |
| ------------------------------------------------------------ | ------ | --------------- | ----- |
| Joint 3D Object Detection and Tracking Using Spatio-Temporal Representation of Camera Image and LiDAR Point Clouds [(AAAI 22)](https://arxiv.org/pdf/2112.07116.pdf) |        |                 |       |
| PolarStream: Streaming Lidar Object Detection and Segmentation with Polar Pillars [(NeurIPS 21)](https://arxiv.org/pdf/2106.07545.pdf) |        |                 |       |
| Offboard 3D Object Detection from Point Cloud Sequencess [(CVPR 21)](https://openaccess.thecvf.com/content/CVPR2021/papers/Qi_Offboard_3D_Object_Detection_From_Point_Cloud_Sequences_CVPR_2021_paper.pdf) |        |                 |       |
| 3D-MAN: 3D Multi-frame Attention Network for Object Detection [(CVPR 21)](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_3D-MAN_3D_Multi-Frame_Attention_Network_for_Object_Detection_CVPR_2021_paper.pdf) |        |                 |       |
| 4D-Net for Learned Multi-Modal Alignment [(ICCV 21)](https://openaccess.thecvf.com/content/ICCV2021/papers/Piergiovanni_4D-Net_for_Learned_Multi-Modal_Alignment_ICCV_2021_paper.pdf) |        |                 |       |
| Graph Neural Network and Spatiotemporal Transformer Attention for 3D Video Object Detection from Point Clouds [(T-PAMI 21)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9609569) |        |                 |       |
| LaserFlow: Efficient and Probabilistic Object Detection and Motion Forecasting [(RA-L 21)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9310205) |        |                 |       |
| VelocityNet: Motion-Driven Feature Aggregation for 3D Object Detection in Point Cloud Sequences [(ICRA 21)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9561644) |        |                 |       |
| RV-FuseNet: Range View Based Fusion of Time-Series LiDAR Data for Joint 3D Object Detection and Motion Forecasting [(IROS 21)](https://arxiv.org/pdf/2005.10863.pdf) |        |                 |       |
| LiDAR-based 3D Video Object Detection with Foreground Context Modeling and Spatiotemporal Graph Reasoning [(ITSC 21)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9565058) |        |                 |       |
| Temporal-Channel Transformer for 3D Lidar-Based Video Object Detection for Autonomous Driving [(T-CSVT 21)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9438625) |        |                 |       |
| Auto4D: Learning to Label 4D Objects from Sequential Point Clouds [(arXiv 21)]() |        |                 |       |
| STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction [(CVPR 20)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_STINet_Spatio-Temporal-Interactive_Network_for_Pedestrian_Detection_and_Trajectory_Prediction_CVPR_2020_paper.pdf) |        |                 |       |
| LiDAR-based Online 3D Video Object Detection with Graph-based Message Passing and Spatiotemporal Transformer Attention [(CVPR 20)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yin_LiDAR-Based_Online_3D_Video_Object_Detection_With_Graph-Based_Message_Passing_CVPR_2020_paper.pdf) |        |                 |       |
| An LSTM Approach to Temporal 3D Object Detection in LiDAR Point Clouds [(ECCV 20)](https://arxiv.org/pdf/2007.12392.pdf) |        |                 |       |
| Streaming Object Detection for 3-D Point Clouds [(ECCV 20)](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123630409.pdf) |        |                 |       |
| Kinematic 3D Object Detection in Monocular Video [(ECCV 20)](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680137.pdf) |        |                 |       |
| STROBE: Streaming Object Detection from LiDAR Packets [(CoRL 20)](https://arxiv.org/pdf/2011.06425.pdf) |        |                 |       |
| 3D Object Detection and Tracking Based on Streaming Data [(ICRA 20)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9197183) |        |                 |       |
| 3D Object Detection For Autonomous Driving Using Temporal Lidar Data [(ICIP 20)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9191134) |        |                 |       |
| Deep SCNN-Based Real-Time Object Detection for Self-Driving Vehicles Using LiDAR Temporal Data [(IEEE Access 20)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9078792) |        |                 |       |
| 4D Spatio-Temporal ConvNets: Minkowski Convolutional Neural Networks [(CVPR 19)](https://arxiv.org/pdf/1904.08755.pdf) |        |                 |       |
| Joint Monocular 3D Vehicle Detection and Tracking [(ICCV 19)]() |        |                 |       |
|                                                              |        |                 |       |

