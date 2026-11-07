# MIMO-SAR × Camera Fusion — Paper List (2024–2026)

204 papers from CVPR · ICCV · ECCV · NeurIPS · ICML · AAAI · ACM MM · ICRA · IROS, 2024–2026. Each entry: authors · first affiliation.

**Finding:** zero MIMO-SAR imaging papers. SAR appears as a downstream modality (detection, segmentation, generation), never as an imaging problem.

**Legend**

- `★★` **directly actionable** — MIMO, imaging/reconstruction, calibration, optical–SAR. (19 papers)
- `★` **adjacent** — detection-level radar–camera fusion, depth, point-cloud enhancement. (49 papers)
- `☆` **SAR/ISAR, downstream only** — detection, segmentation, generation. (11 papers)

---

## Contents

[CVPR (40)](#cvpr) · [ICCV (11)](#iccv) · [ECCV (8)](#eccv) · [NeurIPS (11)](#neurips) · [ICML (5)](#icml) · [AAAI (25)](#aaai) · [ACM MM (10)](#acm-mm) · [ICRA (58)](#icra) · [IROS (36)](#iros)

---


## CVPR


### 2024 (9)

- ★★ [DART: Implicit Doppler Tomography for Radar Novel View Synthesis](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_DART_Implicit_Doppler_Tomography_for_Radar_Novel_View_Synthesis_CVPR_2024_paper.html) — Tianshu Huang, John Miller, Akarsh Prabhakara et al. · *Carnegie Mellon University*
- ★ [RCBEVDet: Radar-camera Fusion in Bird's Eye View for 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2024/html/Lin_RCBEVDet_Radar-camera_Fusion_in_Birds_Eye_View_for_3D_Object_CVPR_2024_paper.html) — Zhiwei Lin, Zhe Liu, Zhongyu Xia et al. · *Wangxuan Institute of Computer Technology, Peking University*
- ★ [Towards Robust 3D Object Detection with LiDAR and 4D Radar Fusion in Various Weather Conditions](https://openaccess.thecvf.com/content/CVPR2024/html/Chae_Towards_Robust_3D_Object_Detection_with_LiDAR_and_4D_Radar_CVPR_2024_paper.html) — Yujeong Chae, Hyeonseong Kim, Kuk-Jin Yoon · *KAIST*
- ☆ [Unleashing Channel Potential: Space-Frequency Selection Convolution for SAR Object Detection](https://openaccess.thecvf.com/content/CVPR2024/html/Li_Unleashing_Channel_Potential_Space-Frequency_Selection_Convolution_for_SAR_Object_Detection_CVPR_2024_paper.html) — Ke Li, Di Wang, Zhangyuan Hu et al. · *School of Computer Science and Technology, Xidian University, Xi’an, China*
- [CRKD: Enhanced Camera-Radar Object Detection with Cross-modality Knowledge Distillation](https://openaccess.thecvf.com/content/CVPR2024/html/Zhao_CRKD_Enhanced_Camera-Radar_Object_Detection_with_Cross-modality_Knowledge_Distillation_CVPR_2024_paper.html) — Lingjun Zhao, Jingyu Song, Katherine A. Skinner · *University of Michigan, Ann Arbor, MI, USA*
- [RadarDistill: Boosting Radar-based Object Detection Performance via Knowledge Distillation from LiDAR Features](https://openaccess.thecvf.com/content/CVPR2024/html/Bang_RadarDistill_Boosting_Radar-based_Object_Detection_Performance_via_Knowledge_Distillation_from_CVPR_2024_paper.html) — Geonho Bang, Kwangjin Choi, Jisong Kim et al. · *Hanyang University, Korea*
- [RadSimReal: Bridging the Gap Between Synthetic and Real Data in Radar Object Detection With Simulation](https://openaccess.thecvf.com/content/CVPR2024/html/Bialer_RadSimReal_Bridging_the_Gap_Between_Synthetic_and_Real_Data_in_CVPR_2024_paper.html) — Oded Bialer, Yuval Haitman · *General Motors, Technical Center Israel*
- [SIRA: Scalable Inter-frame Relation and Association for Radar Perception](https://openaccess.thecvf.com/content/CVPR2024/html/Yataka_SIRA_Scalable_Inter-frame_Relation_and_Association_for_Radar_Perception_CVPR_2024_paper.html) — Ryoma Yataka, Pu Wang, Petros Boufounos et al. · *Mitsubishi Electric Research Laboratories (MERL), Cambridge, MA, USA, 02139*
- [TransLoc4D: Transformer-based 4D Radar Place Recognition](https://openaccess.thecvf.com/content/CVPR2024/html/Peng_TransLoc4D_Transformer-based_4D_Radar_Place_Recognition_CVPR_2024_paper.html) — Guohao Peng, Heshan Li, Yangyang Zhao et al. · *Nanyang Technological University, Singapore*


### 2025 (8)

- ★★ [Cross-Rejective Open-Set SAR Image Registration](https://openaccess.thecvf.com/content/CVPR2025/html/Mao_Cross-Rejective_Open-Set_SAR_Image_Registration_CVPR_2025_paper.html) — Shasha Mao, Shiming Lu, Zhaolong Du et al. · *Xidian University*
- ★★ [RC-AutoCalib: An End-to-End Radar-Camera Automatic Calibration Network](https://openaccess.thecvf.com/content/CVPR2025/html/Luu_RC-AutoCalib_An_End-to-End_Radar-Camera_Automatic_Calibration_Network_CVPR_2025_paper.html) — Van-Tin Luu, Yon-Lin Cai, Vu-Hoang Tran et al. · *National Yang Ming Chiao Tung University, Taiwan*
- ★ [RaCFormer: Towards High-Quality 3D Object Detection via Query-based Radar-Camera Fusion](https://openaccess.thecvf.com/content/CVPR2025/html/Chu_RaCFormer_Towards_High-Quality_3D_Object_Detection_via_Query-based_Radar-Camera_Fusion_CVPR_2025_paper.html) — Xiaomeng Chu, Jiajun Deng, Guoliang You et al. · *University of Science and Technology of China*
- ★ [TacoDepth: Towards Efficient Radar-Camera Depth Estimation with One-stage Fusion](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_TacoDepth_Towards_Efficient_Radar-Camera_Depth_Estimation_with_One-stage_Fusion_CVPR_2025_paper.html) — Yiran Wang, Jiaqi Li, Chaoyi Hong et al. · *Nanyang Technological University, S-Lab*
- ★ [V2X-R: Cooperative LiDAR-4D Radar Fusion with Denoising Diffusion for 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2025/html/Huang_V2X-R_Cooperative_LiDAR-4D_Radar_Fusion_with_Denoising_Diffusion_for_3D_CVPR_2025_paper.html) — Xun Huang, Jinlong Wang, Qiming Xia et al. · *Xiamen University, Fujian Key Laboratory of Sensing and Computing for Smart Cities*
- ☆ [RSAR: Restricted State Angle Resolver and Rotated SAR Benchmark](https://openaccess.thecvf.com/content/CVPR2025/html/Zhang_RSAR_Restricted_State_Angle_Resolver_and_Rotated_SAR_Benchmark_CVPR_2025_paper.html) — Xin Zhang, Xue Yang, Yuxuan Li et al. · *Nankai University, VCIP, CS*
- [MVDoppler-Pose: Multi-Modal Multi-View mmWave Sensing for Long-Distance Self-Occluded Human Walking Pose Estimation](https://openaccess.thecvf.com/content/CVPR2025/html/Choi_MVDoppler-Pose_Multi-Modal_Multi-View_mmWave_Sensing_for_Long-Distance_Self-Occluded_Human_Walking_CVPR_2025_paper.html) — Jaeho Choi, Soheil Hor, Shubo Yang et al. · *DGIST*
- [RICCARDO: Radar Hit Prediction and Convolution for Camera-Radar 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2025/html/Long_RICCARDO_Radar_Hit_Prediction_and_Convolution_for_Camera-Radar_3D_Object_CVPR_2025_paper.html) — Yunfei Long, Abhinav Kumar, Xiaoming Liu et al. · *Michigan State University*


### 2026 (23)

- ★★ [MM-OVSeg: Multimodal Optical-SAR Fusion for Open-Vocabulary Segmentation in Remote Sensing](https://openaccess.thecvf.com/content/CVPR2026/html/Wei_MM-OVSeg_Multimodal_Optical-SAR_Fusion_for_Open-Vocabulary_Segmentation_in_Remote_Sensing_CVPR_2026_paper.html) — Yimin Wei, Aoran Xiao, Hongruixuan Chen et al. · *The University of Tokyo 2 RIKEN AIP*
- ★★ [MOS: Mitigating Optical-SAR Modality Gap for Cross-Modal Ship Re-Identification](https://openaccess.thecvf.com/content/CVPR2026/html/Zhao_MOS_Mitigating_Optical-SAR_Modality_Gap_for_Cross-Modal_Ship_Re-Identification_CVPR_2026_paper.html) — Yujian Zhao, Hankun Liu, Guanglin Niu et al. · *School of Artificial Intelligence, Beihang University*
- ★★ [Rascene: High-Fidelity 3D Scene Imaging with mmWave Communication Signals](https://openaccess.thecvf.com/content/CVPR2026/html/Song_Rascene_High-Fidelity_3D_Scene_Imaging_with_mmWave_Communication_Signals_CVPR_2026_paper.html) — Kunzhe Song, Geo Jie Zhou, Xiaoming Liu et al. · *Department of Computer Science and Engineering, Michigan State University*
- ★★ [Seeing through boxes: Non-Line-of-Sight 3D Reconstruction from Radar Signals](https://openaccess.thecvf.com/content/CVPR2026/html/Lu_Seeing_through_boxes_Non-Line-of-Sight_3D_Reconstruction_from_Radar_Signals_CVPR_2026_paper.html) — Jiachen Lu, Hailan Shanbhag, Haitham Al Hassanieh et al. · *Recently, there has been a growing interest in neural reconstruction methods for radio…*
- ★★ [X-band Radar Non-Line-of-Sight Imaging](https://openaccess.thecvf.com/content/CVPR2026/html/Du_X-band_Radar_Non-Line-of-Sight_Imaging_CVPR_2026_paper.html) — Dongyu Du, Mingkun Zhao, Yutong Yang et al. · *Princeton University*
- ★ [Hybrid Robust Collaborative Perception with LiDAR-4D Radar Fusion under Adverse Weather Conditions](https://openaccess.thecvf.com/content/CVPR2026/html/Yang_Hybrid_Robust_Collaborative_Perception_with_LiDAR-4D_Radar_Fusion_under_Adverse_CVPR_2026_paper.html) — Yuquan Yang, Hui Zhang, Wenyu Lu et al. · *School of Computer Science and Technology, University of Science and Technology of China*
- ★ [M4Human: A Large-Scale Multimodal mmWave Radar Benchmark for Human Mesh Reconstruction](https://openaccess.thecvf.com/content/CVPR2026/html/Fan_M4Human_A_Large-Scale_Multimodal_mmWave_Radar_Benchmark_for_Human_Mesh_CVPR_2026_paper.html) — Junqiao Fan, Yunjiao Zhou, Yizhuo Yang et al. · *NTU 2 University of Edinburgh 3 UPenn 4 UCL 5 MIT*
- ★ [R4Det: 4D Radar-Camera Fusion for High-Performance 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2026/html/Xia_R4Det_4D_Radar-Camera_Fusion_for_High-Performance_3D_Object_Detection_CVPR_2026_paper.html) — Zhongyu Xia, Yousen Tang, Yongtao Wang et al. · *Wangxuan Institute of Computer Technology, Peking University 2 EBTech Co. Ltd*
- ★ [Radar-Guided Polynomial Fitting for Metric Depth Estimation](https://openaccess.thecvf.com/content/CVPR2026/html/Rim_Radar-Guided_Polynomial_Fitting_for_Metric_Depth_Estimation_CVPR_2026_paper.html) — Patrick Rim, Hyoungseob Park, Vadim Ezhov et al. · *Yale University*
- ★ [RPGFusion: 4D Radar Prior-Guided Multi-Modal Fusion for 3D Detection](https://openaccess.thecvf.com/content/CVPR2026/html/Qiu_RPGFusion_4D_Radar_Prior-Guided_Multi-Modal_Fusion_for_3D_Detection_CVPR_2026_paper.html) — Xin Qiu, Wenjie Liu, Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) et al. · *Zhejiang University, China*
- ☆ [FUSAR-GPT: A Spatiotemporal Feature-Embedded and Two-Stage Decoupled Visual Language Model for SAR Imagery](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_FUSAR-GPT_A_Spatiotemporal_Feature-Embedded_and_Two-Stage_Decoupled_Visual_Language_Model_CVPR_2026_paper.html) — Xiaokun Zhang, Yi Yang, Ziqi Ye et al. · *Discipline and Technology Center of Microwave Vision Intelligent Sensing, Fudan…*
- ☆ [SARMAE: Masked Autoencoder for SAR Representation Learning](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_SARMAE_Masked_Autoencoder_for_SAR_Representation_Learning_CVPR_2026_paper.html) — Danxu Liu, Di Wang, Hebaixu Wang et al. · *School of Information and Electronics, Beijing Institute of Technology, Beijing, China*
- [AdaRadar: Rate Adaptive Spectral Compression for Radar-based Perception](https://openaccess.thecvf.com/content/CVPR2026/html/Park_AdaRadar_Rate_Adaptive_Spectral_Compression_for_Radar-based_Perception_CVPR_2026_paper.html) — Jinho Park, Se Young Chun, Mingoo Seok et al. · *Columbia University*
- [DSERT-RoLL: Robust Multi-Modal Perception for Diverse Driving Conditions with Stereo Event-RGB-Thermal Cameras, 4D Radar, and Dual-LiDAR](https://openaccess.thecvf.com/content/CVPR2026/html/Cho_DSERT-RoLL_Robust_Multi-Modal_Perception_for_Diverse_Driving_Conditions_with_Stereo_CVPR_2026_paper.html) — Hoonhee Cho, Jae-Young Kang, Yuhwan Jeong et al. · *Visual Intelligence Lab, KAIST*
- [Expanding mmWave Datasets for Human Pose Estimation with Unlabeled Data and LiDAR Datasets](https://openaccess.thecvf.com/content/CVPR2026/html/Peng_Expanding_mmWave_Datasets_for_Human_Pose_Estimation_with_Unlabeled_Data_CVPR_2026_paper.html) — Zhuoxuan Peng, Boan Zhu, Xingjian Zhang et al. · *The Hong Kong University of Science and Technology*
- [MARSS: Radar Semantic Segmentation via Modular Attention and State Space Models](https://openaccess.thecvf.com/content/CVPR2026/html/Chen_MARSS_Radar_Semantic_Segmentation_via_Modular_Attention_and_State_Space_CVPR_2026_paper.html) — Fengyu Chen, Tiao Tan, Teng Li et al. · *Tsinghua University SIGS*
- [mmWaveFlow: Unified Enhancement and Generation of mmWave Human Point Clouds](https://openaccess.thecvf.com/content/CVPR2026/html/Su_mmWaveFlow_Unified_Enhancement_and_Generation_of_mmWave_Human_Point_Clouds_CVPR_2026_paper.html) — Chang Su, Beihong Jin, Qiwen Shi et al. · *Institute of Software, Chinese Academy of Sciences*
- [RaGS: Unleashing 3D Gaussian Splatting from 4D Radar and Monocular Cue for 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2026/html/Bai_RaGS_Unleashing_3D_Gaussian_Splatting_from_4D_Radar_and_Monocular_CVPR_2026_paper.html) — Xiaokai Bai, Chenxu Zhou, Lianqing Zheng et al. · *College of Information Science and Electronic Engineering, Zhejiang University*
- [RaUF: Learning the Spatial Uncertainty Field of Radar](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_RaUF_Learning_the_Spatial_Uncertainty_Field_of_Radar_CVPR_2026_paper.html) — Shengpeng Wang, Kuangyu Wang, Wei Wang et al. · *Wuhan University*
- [RAVEN: Radar Adaptive Vision Encoders for Efficient Chirp-wise Object Detection and Segmentation](https://openaccess.thecvf.com/content/CVPR2026/html/Sen_RAVEN_Radar_Adaptive_Vision_Encoders_for_Efficient_Chirp-wise_Object_Detection_CVPR_2026_paper.html) — Anuvab Sen, Mir Sayeed Mohammad, Saibal Mukhopadhyay et al. · *Georgia Institute of Technology, Atlanta, Georgia, USA*
- [RF4D:Neural Radar Fields for Novel View Synthesis in Outdoor Dynamic Scenes](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_RF4DNeural_Radar_Fields_for_Novel_View_Synthesis_in_Outdoor_Dynamic_CVPR_2026_paper.html) — Jiarui Zhang, Zhihao Li, Chong Wang et al. · *Nanyang Technological University, Singapore*
- [RISE: Single Static Radar-based Indoor Scene Understanding](https://openaccess.thecvf.com/content/CVPR2026/html/Zhou_RISE_Single_Static_Radar-based_Indoor_Scene_Understanding_CVPR_2026_paper.html) — Kaichen Zhou, Laura Dodds, Sayed Saad Afzal et al. · *Massachusetts Institute of Technology*
- [Underground Plant Exploration: Non-Destructive 3D Root Assessment with GPR Based on Point Graph Neural Network](https://openaccess.thecvf.com/content/CVPR2026/html/Zhou_Underground_Plant_Exploration_Non-Destructive_3D_Root_Assessment_with_GPR_Based_CVPR_2026_paper.html) — Yuwei Zhou, Guoyu Lu, Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) et al. · *Rochester Institute of Technology*


## ICCV


### 2025 (11)

- ★★ [RadarSplat: Radar Gaussian Splatting for High-Fidelity Data Synthesis and 3D Reconstruction of Autonomous Driving Scenes](https://openaccess.thecvf.com/content/ICCV2025/html/Kung_RadarSplat_Radar_Gaussian_Splatting_for_High-Fidelity_Data_Synthesis_and_3D_ICCV_2025_paper.html) — Pou-Chun Kung, Skanda Harisha, Ram Vasudevan et al. · *University of Michigan, USA*
- ★ [CVFusion: Cross-View Fusion of 4D Radar and Camera for 3D Object Detection](https://openaccess.thecvf.com/content/ICCV2025/html/Zhong_CVFusion_Cross-View_Fusion_of_4D_Radar_and_Camera_for_3D_ICCV_2025_paper.html) — Hanzhi Zhong, Zhiyu Xiang, Ruoyu Xu et al. · *Zhejiang University, China*
- ★ [Doppler-Aware LiDAR-RADAR Fusion for Weather-Robust 3D Detection](https://openaccess.thecvf.com/content/ICCV2025/html/Chae_Doppler-Aware_LiDAR-RADAR_Fusion_for_Weather-Robust_3D_Detection_ICCV_2025_paper.html) — Yujeong Chae, Heejun Park, Hyeonseong Kim et al. · *Korea Advanced Institute of Science and Technology*
- ★ [RCTDistill: Cross-Modal Knowledge Distillation Framework for Radar-Camera 3D Object Detection with Temporal Fusion](https://openaccess.thecvf.com/content/ICCV2025/html/Bang_RCTDistill_Cross-Modal_Knowledge_Distillation_Framework_for_Radar-Camera_3D_Object_Detection_ICCV_2025_paper.html) — Geonho Bang, Minjae Seong, Jisong Kim et al. · *Seoul National University*
- ☆ [Cross-modal Ship Re-Identification via Optical and SAR Imagery: A Novel Dataset and Method](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_Cross-modal_Ship_Re-Identification_via_Optical_and_SAR_Imagery_A_Novel_ICCV_2025_paper.html) — Han Wang, Shengyang Li, Jian Yang et al. · *Technology and Engineering Center for Space Utilization, Chinese Academy of Sciences,…*
- ☆ [Ph-GAN: Physics-Inspired GAN for Generating SAR Images Under Limited Data](https://openaccess.thecvf.com/content/ICCV2025/html/Zhang_Ph-GAN_Physics-Inspired_GAN_for_Generating_SAR_Images_Under_Limited_Data_ICCV_2025_paper.html) — Xidan Zhang, Yihan Zhuang, Qian Guo et al. · *School of Automation, Northwestern Polytechnical University*
- [DoppDrive: Doppler-Driven Temporal Aggregation for Improved Radar Object Detection](https://openaccess.thecvf.com/content/ICCV2025/html/Haitman_DoppDrive_Doppler-Driven_Temporal_Aggregation_for_Improved_Radar_Object_Detection_ICCV_2025_paper.html) — Yuval Haitman, Oded Bialer · *General Motors, Technical Center Israel*
- [S3E: Self-Supervised State Estimation for Radar-Inertial System](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_S3E_Self-Supervised_State_Estimation_for_Radar-Inertial_System_ICCV_2025_paper.html) — Shengpeng Wang, Yulong Xie, Qing Liao et al. · *Huazhong University of Science and Technology*
- [Spatial Alignment and Temporal Matching Adapter for Video-Radar Remote Physiological Measurement](https://openaccess.thecvf.com/content/ICCV2025/html/Liang_Spatial_Alignment_and_Temporal_Matching_Adapter_for_Video-Radar_Remote_Physiological_ICCV_2025_paper.html) — Qian Liang, Ruixu Geng, Jinbo Chen et al. · *University of Science and Technology of China*
- [TARS: Traffic-Aware Radar Scene Flow Estimation](https://openaccess.thecvf.com/content/ICCV2025/html/Wu_TARS_Traffic-Aware_Radar_Scene_Flow_Estimation_ICCV_2025_paper.html) — Jialong Wu, Marco Braun, Dominic Spata et al. · *University of Wuppertal*
- [Towards Foundational Models for Single-Chip Radar](https://openaccess.thecvf.com/content/ICCV2025/html/Huang_Towards_Foundational_Models_for_Single-Chip_Radar_ICCV_2025_paper.html) — Tianshu Huang, Akarsh Prabhakara, Chuhan Chen et al. · *Carnegie Mellon University*


## ECCV

_CCF-B, kept for the CV-trio scope._


### 2024 (8)

- ★ [Sparse Beats Dense: Rethinking Supervision in Radar-Camera Depth Completion](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/6528_ECCV_2024_paper.php) — Huadong Li, Minhao Jing, Wang Jin et al. · *The University of Hong Kong*
- [CARB-Net: Camera-Assisted Radar-Based Network for Vulnerable Road User Detection](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/8101_ECCV_2024_paper.php) — Wei-Yu Lee, Martin Dimitrievski, David Van Hamme et al. · *TELIN-IPI, Ghent University-IMEC, Gent, Belgium*
- [LEROjD: Lidar Extended Radar-Only Object Detection](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/7776_ECCV_2024_paper.php) — Patrick Palmer, Martin Krüger, Stefan Schütte et al. · *Institute of Control Theory and Systems Engineering, TU Dortmund University*
- [LiDAR-based All-weather 3D Object Detection via Prompting and Distilling 4D Radar](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/7349_ECCV_2024_paper.php) — Yujeong Chae, Hyeonseong Kim, Changgyoon Oh et al. · *Visual Intelligence Lab., KAIST*
- [milliFlow: Scene Flow Estimation on mmWave Radar Point Cloud for Human Motion Sensing](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/3470_ECCV_2024_paper.php) — Fangqiang Ding, Zhen Luo, Peijun Zhao et al. · *University of Edinburgh*
- [MMVR: Millimeter-wave Multi-View Radar Dataset and Benchmark for Indoor Perception](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/10205_ECCV_2024_paper.php) — M. Mahbubur Rahman, Ryoma Yataka, Sorachi Kato et al. · *Mitsubishi Electric Research Laboratories (MERL), Cambridge, MA 02139*
- [RT-Pose: A 4D Radar-Tensor based 3D Human Pose Estimation and Localization Benchmark](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/7989_ECCV_2024_paper.php) — Yuan-Hao Ho, Jen-Hao Cheng, Sheng Yao Kuan et al. · *National Cheng Kung University*
- [SparseRadNet: Sparse Perception Neural Network on Subsampled Radar Data](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/11537_ECCV_2024_paper.php) — Jialong Wu, Mirko Meuter, Markus Schoeler et al. · *University of Wuppertal, Germany*


## NeurIPS


### 2024 (7)

- ★ [CRT-Fusion: Camera, Radar, Temporal Fusion Using  Motion Information  for 3D Object Detection](https://proceedings.neurips.cc/paper_files/paper/2024/hash/c49a28241640407b23bba8f2495f4bc9-Abstract-Conference.html) — Jisong Kim, Minjae Seong, Jun Won Choi · *Hanyang University 2 Seoul National University*
- ★ [RadarOcc: Robust 3D Occupancy Prediction with 4D Imaging Radar](https://proceedings.neurips.cc/paper_files/paper/2024/hash/b81d83165e3145a2e7d33bb5e33ea913-Abstract-Conference.html) — Fangqiang Ding, Xiangyu Wen, Yunzhou Zhu et al. · *University of Edinburgh 2 Georgia Institute of Technology 3 New York University*
- ☆ [M3LEO: A Multi-Modal, Multi-Label Earth Observation Dataset Integrating Interferometric SAR and Multispectral Data](https://proceedings.neurips.cc/paper_files/paper/2024/hash/bd194b579f60879e04ca9ce8a4ea5da1-Abstract-Datasets_and_Benchmarks_Track.html) — Matt Allen, Francisco Dorr, Joseph Gallego-Mejia et al. · *University of Cambridge, UK*
- ☆ [SARDet-100K: Towards Open-Source Benchmark and ToolKit for Large-Scale SAR Object Detection](https://proceedings.neurips.cc/paper_files/paper/2024/hash/e7eb8128eb26eafbe901348df1dbacdc-Abstract-Conference.html) — Yuxuan Li, Xiang Li, Weijie Li et al. · *PCA Lab, VCIP, CS, Nankai University*
- [AdaPKC: PeakConv with Adaptive Peak Receptive Field for Radar Semantic Segmentation](https://proceedings.neurips.cc/paper_files/paper/2024/hash/f6b22ac37beb5da61efd4882082c9ecd-Abstract-Conference.html) — Teng Li, Liwen Zhang, Youcheng Zhang et al. · *Intelligent Science and Technology Academy of CASIC*
- [RETR: Multi-View Radar Detection Transformer for Indoor Perception](https://proceedings.neurips.cc/paper_files/paper/2024/hash/2341b14df6b4f684a30eb4e99807bea6-Abstract-Conference.html) — Ryoma Yataka, Adriano Cardace, Pu Wang et al. · *Mitsubishi Electric Research Laboratories (MERL), USA*
- [TARSS-Net: Temporal-Aware Radar Semantic Segmentation Network](https://proceedings.neurips.cc/paper_files/paper/2024/hash/08a362bd4ae1934e099ce025f06039fe-Abstract-Conference.html) — Youcheng Zhang, Liwen Zhang, Zijun Hu et al. · *Intelligent Science and Technology Academy of CASIC*


### 2025 (4)

- ★★ [Non-Line-of-Sight 3D Reconstruction with Radar](https://neurips.cc/virtual/2025/poster/116868) — Haowen Lai, Zitong Lan, Mingmin Zhao · *University of Pennsylvania*
- [RadarQA: Multi-modal Quality Analysis of Weather Radar Forecasts](https://neurips.cc/virtual/2025/poster/117566) — Xuming He, Zhiyuan You, Junchao Gong et al. · *ShanghaiTech University*
- [RAPTR: Radar-based 3D Pose Estimation using Transformer](https://neurips.cc/virtual/2025/poster/119916) — Sorachi Kato, Ryoma Yataka, Pu Wang et al. · *The University of Osaka*
- [V2X-Radar: A Multi-modal Dataset with 4D Radar for Cooperative Perception](https://neurips.cc/virtual/2025/poster/121426) — Lei Yang, Xinyu Zhang, Jun Li et al. · *Hong Kong Polytechnic University*


## ICML


### 2025 (1)

- ☆ [Gamma Distribution PCA-Enhanced Feature Learning for Angle-Robust SAR Target Recognition](https://proceedings.mlr.press/v267/) — Rogelio A. Mancisidor, Robert Jenssen, Shujian Yu et al. · *(ELBO). Current methods, the product and mixture of experts, aggregate single-modality…*


### 2026 (4)

- [Cardio-mmFlow: A Gaussian-Prior-Free Physics-Informed Flow Matching Framework for Electrocardiogram to mmWave Radar Synthesis](https://proceedings.mlr.press/v306/liu26ey.html) — Ziyang Liu, Ruiqiang Xiao, Chang Huang et al. · *technology, researchers have explored RF signals as a way*
- [Doppler Prompting for Stable mmWave-based Human Pose Estimation](https://proceedings.mlr.press/v306/zheng26g.html) — Shuntian Zheng, Jiaqi Li, Xiaoman Lu et al. · *signatures for motion-related cues. However, existing mmWave-based HPE methods either…*
- [Frequency Matching in Spiking Neural Networks for mmWave Sensing](https://proceedings.mlr.press/v306/liao26e.html) — Zhenyu Liao, Di Yu, Changze Lv et al. · *—*
- [Weakly Supervised Cross-Modal Learning for 4D Radar Scene Flow Estimation](https://proceedings.mlr.press/v306/fu26r.html) — Jingyun Fu, Zhiyu Xiang, Na Zhao · *methods typically rely on either self-supervised*


## AAAI


### 2024 (2)

- ☆ [Statistically Principled Deep Learning for SAR Image Segmentation](https://ojs.aaai.org/index.php/AAAI/article/view/30549) — Cassandra Goldberg · *—*
- [RadarMOSEVE: A Spatial-Temporal Transformer Network for Radar-Only Moving Object Segmentation and Ego-Velocity Estimation](https://ojs.aaai.org/index.php/AAAI/article/view/28240) — Changsong Pang, Xieyuanli Chen, Yimin Liu et al. · *Northwestern Polytechnical University*


### 2025 (5)

- ★ [HGSFusion: Radar-Camera Fusion with Hybrid Generation and Synchronization for 3D Object Detection](https://ojs.aaai.org/index.php/AAAI/article/view/32328) — Zijian Gu, Jianwei Ma, Yan Huang et al. · *Southeast University 2 Washington State University*
- ☆ [Dual Information Purification for Lightweight SAR Object Detection](https://ojs.aaai.org/index.php/AAAI/article/view/33004) — Xi Yang, Jiachen Sun, Songsong Duan et al. · *—*
- [EDENet: Echo Direction Encoding Network for Place Recognition Based on Ground Penetrating Radar](https://ojs.aaai.org/index.php/AAAI/article/view/33092) — Pengyu Zhang, Xieyuanli Chen, Yuwei Chen et al. · *National University of Defense Technology, Changsha, 410073, China*
- [RCTrans: Radar-Camera Transformer via Radar Densifier and Sequential Decoder for 3D Object Detection](https://ojs.aaai.org/index.php/AAAI/article/view/32535) — Yiheng Li, Yang Yang, Zhen Lei · *State Key Laboratory of Multimodal Artificial Intelligence Systems (MAIS),*
- [SCKD: Semi-Supervised Cross-Modality Knowledge Distillation for 4D Radar Object Detection](https://ojs.aaai.org/index.php/AAAI/article/view/32966) — Ruoyu Xu, Zhiyu Xiang, Chenwei Zhang et al. · *Zhejiang University, China*


### 2026 (18)

- ★★ [DenoDet V2: Phase-Amplitude Cross Denoising for SAR Object Detection](https://ojs.aaai.org/index.php/AAAI/article/view/37761) — Kang Ni, Minrui Zou, Yuxuan Li et al. · *School of Computer Science, Nanjing University of Posts and Telecommunications, 2 VCIP…*
- ★★ [HiFC-GAN: Hierarchical Feature-Constrained GAN for Optical-to-SAR Transfer in SAR Target Classification](https://ojs.aaai.org/index.php/AAAI/article/view/38342) — Hao Zheng, Meiguang Zheng, Zhigang Hu et al. · *—*
- ★★ [Multi-Window Gabor Transform Network for Ground Penetrating Radar B-Scan Image Reconstruction](https://ojs.aaai.org/index.php/AAAI/article/view/37947) — Huabin Wang, Yu Yang, Xinran Zhong et al. · *—*
- ★★ [SOMA: Feature Gradient Enhanced Affine-Flow Matching for SAR-Optical Registration](https://ojs.aaai.org/index.php/AAAI/article/view/37939) — Haodong Wang, Tao Zhuo, Xiuwei Zhang et al. · *School of Computer Science, Northwestern Polytechnical University*
- ★ [Indoor Multi-View Radar Object Detection via 3D Bounding Box Diffusion](https://ojs.aaai.org/index.php/AAAI/article/view/38939) — Ryoma Yataka, Pu (Perry) Wang, Petros Boufounos et al. · *Information Technology R&D Center (ITC), Mitsubishi Electric Corporation (MELCO),…*
- ★ [RaLD: Generating High-Resolution 3D Radar Point Clouds with Latent Diffusion](https://ojs.aaai.org/index.php/AAAI/article/view/38946) — Ruijie Zhang, Bixin Zeng, Shengpeng Wang et al. · *Huazhong University of Science and Technology,*
- ★ [SAR-DisentDM: A Semantic-Disentangled Diffusion Model for Limited-Data SAR Image Synthesis](https://ojs.aaai.org/index.php/AAAI/article/view/38165) — Yue Yang, Song Tang, Qijun Zhao et al. · *—*
- [DNOI-4DRO: Deep 4D Radar Odometry with Differentiable Neural-Optimization Iterations](https://ojs.aaai.org/index.php/AAAI/article/view/38914) — Shouyi Lu, Huanyu Zhou, Guirong Zhuo et al. · *School of Automotive Studies, Tongji University*
- [Learning 3D Occupancy from Beam Overlap in 2D Rotating mmWave Radar](https://ojs.aaai.org/index.php/AAAI/article/view/37371) — Yu Du, Ruifeng Nie, Long Ma et al. · *—*
- [mmJEPA-ECG: Cross-Posture Robust Contactless Electrocardiogram Monitoring via Millimeter Wave Radar Sensing](https://ojs.aaai.org/index.php/AAAI/article/view/41242) — Ziyang Liu, Siyuan He, Feng Liang et al. · *—*
- [mmPred: Radar-based Human Motion Prediction in the Dark](https://ojs.aaai.org/index.php/AAAI/article/view/37378) — Junqiao Fan, Haocong Rao, Jiarui Zhang et al. · *attempt to use single-view RGB images, these methods struggle under adverse…*
- [Radar Instance Transformer: Reliable Moving Instance Segmentation in Sparse Radar Point Clouds (Abstract Reprint)](https://ojs.aaai.org/index.php/AAAI/article/view/41421) — Matthias Zeller, Vardeep Singh Sandhu, Benedikt Mersch et al. · *—*
- [Radar-APLANC: Unsupervised Radar-based Heartbeat Sensing via Augmented Pseudo-Label and Noise Contrast](https://ojs.aaai.org/index.php/AAAI/article/view/37996) — Ying Wang, Zhaodong Sun, Xu Cheng et al. · *(a) Traditional Radar Heartbeat Sensing Method*
- [RadarLLM: Empowering Large Language Models to Understand Human Motion from Millimeter-wave Point Cloud Sequence](https://ojs.aaai.org/index.php/AAAI/article/view/37500) — Zengyuan Lai, Jiarui Yang, Songpengcheng Xia et al. · *Shanghai Jiao Tong University*
- [RadarMP: Motion Perception for 4D mmWave Radar in Autonomous Driving](https://ojs.aaai.org/index.php/AAAI/article/view/37323) — Ruiqi Cheng, Huijun Di, Jian Li et al. · *School of Computer Science and Technology, Beijing Institute of Technology, Beijing,…*
- [RaLiFlow: Scene Flow Estimation with 4D Radar and LiDAR Point Clouds](https://ojs.aaai.org/index.php/AAAI/article/view/37404) — Jingyun Fu, Zhiyu Xiang, Na Zhao · *Zhejiang University*
- [Towards Accurate 3D Object Detection in Adverse Weather by Leveraging 4D Radar for LiDAR Geometry Enhancement](https://ojs.aaai.org/index.php/AAAI/article/view/37916) — Tianxu Tong, Xinrun Liu, Hongmin Liu et al. · *—*
- [WaveC2R: Wavelet-Driven Coarse-to-Refined Hierarchical Learning for Radar Retrieval](https://ojs.aaai.org/index.php/AAAI/article/view/37850) — Chunlei Shi, Han Xu, Yinghao Li et al. · *School of Automation, Southeast University*


## ACM MM


### 2024 (3)

- ★★ [Interpretable Matching of Optical-SAR Image via Dynamically Conditioned Diffusion Models](https://doi.org/10.1145/3664647.3681700) — Shuiping Gou, Xin Wang, Xinlin Wang et al. · *Xidian University, Xi'an, China*
- ★ [FARFusion V2: A Geometry-based Radar-Camera Fusion Method on the Ground for Roadside Far-Range 3D Object Detection](https://doi.org/10.1145/3664647.3681128) — Yao Li, Jiajun Deng, Yuxuan Xiao et al. · *University of Science and Technology of China, Hefei, China*
- [SparseInteraction: Sparse Semantic Guidance for Radar and Camera 3D Object Detection](https://doi.org/10.1145/3664647.3681565) — Shaoqing Xu, Shengyin Jiang, Fang Li et al. · *University of Macau, Macau, China*


### 2025 (3)

- [FGRFlow: Learning Fine-Grained Rigidity Scene Flow from 4D Radar Point Cloud](https://doi.org/10.1145/3746027.3755042) — Mingliang Zhai, Yiheng Wang, Haidong Hu et al. · *Nanjing University of Posts and Telecommunications, Nanjing, China*
- [Radar-Mamba: 4D Millimeter-Wave Point Cloud Enhancement via State Space Models](https://doi.org/10.1145/3746027.3755431) — Hong Gao, Xiangkai Xu, Tianqi Zhu et al. · *Southeast University, Nanjing, China*
- [Venus: Generating Large-scale mmWave Radar Data via Few 2D Videos for Gesture Recognition While Lying Down](https://doi.org/10.1145/3746027.3755399) — Yue Ling, Dong Zhao, Kaikai Deng et al. · *Beijing University of Posts and Telecommunications, Beijing, China*


### 2026 (4)

- ★ [ElevC2F: Elevation-Aware Coarse-to-Fine Fusion of 4D Radar and Camera for 3D Object Detection](https://doi.org/10.1145/3767308.3836599) — Yuzhe Song, Dexing Lin, Jian Chen et al. · *Fuzhou University, Fuzhou, China*
- ★ [SPRFusion: Semantic and Physics-driven Robust Radar-Camera Fusion for 3D Object Detection](https://doi.org/10.1145/3767308.3835982) — Ze Zhou, Run Zhou, Xianghao Zhou et al. · *School of Automation Science and Electrical Engineering, Beihang University, Beijing,…*
- [Cross-Modal Generation: From Commodity WiFi to High-Fidelity mmWave and RFID Sensing](https://doi.org/10.1145/3767308.3836022) — Zhixiong Yang, Long Jing, Yao Li et al. · *Xinjiang University, Urumqi, Xinjiang, China*
- [RemoPhysEmo: A Multimodal Emotion Dataset with Remotely Sensed Physiological Signals via Video and Radar](https://doi.org/10.1145/3767308.3838666) — Zheng Gao, Xiaobai Li, Jieyi Ge et al. · *Zhejiang University, Hangzhou, Zhejiang, China*


## ICRA

_CCF-B robotics venue, added by request._


### 2024 (20)

- ★ [Diffusion-Based Point Cloud Super-Resolution for mmWave Radar Data](https://doi.org/10.1109/icra57147.2024.10611026) — Kai Luan, Chenghao Shi, Neng Wang et al. · *National University of Defense Technology, College of Intelligence Science and…*
- ★ [LiRaFusion: Deep Adaptive LiDAR-Radar Fusion for 3D Object Detection](https://doi.org/10.1109/icra57147.2024.10611436) — Jingyu Song, Lingjun Zhao, Katherine A. Skinner · *University of Michigan, Department of Robotics, Ann Arbor, MI, USA*
- ★ [Multi-Radar Inertial Odometry for 3D State Estimation using mmWave Imaging Radar](https://doi.org/10.1109/icra57147.2024.10611194) — Jui-Te Huang, Ruoyang Xu, Akshay Hinduja et al. · *Carnegie Mellon University, Robotics Institute, Pittsburgh, PA, USA, 15213*
- ★ [RadarCam-Depth: Radar-Camera Fusion for Depth Estimation with Learned Metric Scale](https://doi.org/10.1109/icra57147.2024.10610929) — Han Li, Yukai Ma, Yaqing Gu et al. · *Zhejiang University, Institute of Cyber-Systems and Control, Hangzhou, China*
- ★ [RCM-Fusion: Radar-Camera Multi-Level Fusion for 3D Object Detection](https://doi.org/10.1109/icra57147.2024.10611449) — Jisong Kim, Minjae Seong, Geonho Bang et al. · *Hanyang University, Department of Electrical Engineering, Seoul, South Korea, 04763*
- [Degradation Resilient LiDAR-Radar-Inertial Odometry](https://doi.org/10.1109/icra57147.2024.10611444) — Morten Nissov, Nikhil Khedekar, Kostas Alexis · *Norwegian University of Science and Technology (NTNU), Trondheim, Norway, 7034*
- [Do we need scan-matching in radar odometry?](https://doi.org/10.1109/icra57147.2024.10610666) — Vladimír Kubelka, Emil Fritz, Martin Magnusson · *MRO lab of the AASS Research Centre at Örebro University, Sweden*
- [Doppler-only Single-scan 3D Vehicle Odometry](https://doi.org/10.1109/icra57147.2024.10611199) — Andres Galeote-Luque, Vladimír Kubelka, Martin Magnusson et al. · *University of Malaga, Machine Perception and Intelligent Robotics (MAPIR) Group, System…*
- [Dynamic Occupancy Grids for Object Detection: A Radar-Centric Approach](https://doi.org/10.1109/icra57147.2024.10610514) — Max Peter Ronecker, Markus Schratter, Lukas Kuschnig et al. · *SETLabs Research GmbH, Munich, Germany, 80687*
- [Enhancing mmWave Radar Point Cloud via Visual-inertial Supervision](https://doi.org/10.1109/icra57147.2024.10610091) — Cong Fan, Shengkai Zhang, Kezhong Liu et al. · *Wuhan University of Technology, Wuhan, China*
- [Less is More: Physical-Enhanced Radar-Inertial Odometry](https://doi.org/10.1109/icra57147.2024.10611471) — Qiucan Huang, Yuchen Liang, Zhijian Qiao et al. · *Hong Kong University of Science and Technology, Cheng Kar-Shun Robotics Institute, Hong…*
- [MTRadSSD: A Multi-Task Single-Stage Detector for Object Detection and Free Space Analysis in Radar Point Clouds *](https://doi.org/10.1109/icra57147.2024.10611324) — Yinbao Li, Songshan Yu, Dongfeng Wang et al. · *Joospeed Electronic Technology Co., Ltd, R&D Department of Jiaxing, Beijing, China,…*
- [Odometry Estimation by Fusing Multiple Radar Sensors and an Inertial Measurement Unit](https://doi.org/10.1109/icra57147.2024.10610446) — Tim Brühl, Tim Dieter Eberhardt, Robin Schwager et al. · *Dr. Ing. h.c. F. Porsche AG, Dept. of Highly Automated Driving Systems, Weissach,…*
- [PillarGen: Enhancing Radar Point Cloud Density and Quality via Pillar-based Point Generation Network](https://doi.org/10.1109/icra57147.2024.10611144) — Jisong Kim, Geonho Bang, Kwangjin Choi et al. · *Hanyang University, Department of Electrical Engineering, Seoul, Korea, 04763*
- [Radar Tracker: Moving Instance Tracking in Sparse and Noisy Radar Point Clouds](https://doi.org/10.1109/icra57147.2024.10610198) — Matthias Zeller, Daniel Casado Herraez, Jens Behley et al. · *University of Bonn, CARIAD SE and Center for Robotics, Germany*
- [Radar-Only Odometry and Mapping for Autonomous Vehicles](https://doi.org/10.1109/icra57147.2024.10610311) — Daniel Casado Herraez, Matthias Zeller, Le Chang et al. · *CARIAD SE and With the University of Bonn, Germany*
- [RaLF: Flow-based Global and Metric Radar Localization in LiDAR Maps](https://doi.org/10.1109/icra57147.2024.10610626) — Abhijeet Nayak, Daniele Cattaneo, Abhinav Valada · *University of Freiburg, Department of Computer Science, Germany*
- [RaTrack: Moving Object Detection and Tracking with 4D Radar Point Cloud](https://doi.org/10.1109/icra57147.2024.10610368) — Zhijun Pan, Fangqiang Ding, Hantao Zhong et al. · *Royal College of Art, Computer Science Research Centre, United Kingdom*
- [Robust 3D Object Detection from LiDAR-Radar Point Clouds via Cross-Modal Feature Augmentation](https://doi.org/10.1109/icra57147.2024.10610775) — Jianning Deng, Gabriel Chan, Hantao Zhong et al. · *University of Edinburgh, United Kingdom*
- [Subsurface Feature-based Ground Robot/Vehicle Localization Using a Ground Penetrating Radar](https://doi.org/10.1109/icra57147.2024.10611579) — Haifeng Li, Jiajun Guo, Dezhen Song · *Civil Aviation University of China, Department of Computer Science, Tianjin, China,…*


### 2025 (24)

- ★★ [RLCNet: A Novel Deep Feature-Matching-Based Method for Online Target-Free Radar-LiDAR Calibration](https://doi.org/10.1109/icra55743.2025.11127342) — Kai Luan, Chenghao Shi, Xieyuanli Chen et al. · *College of Intelligence Science and Technology, National University of Defense…*
- ★ [AF-RLIO: Adaptive Fusion of Radar-LiDAR-Inertial Information for Robust Odometry in Challenging Environments](https://doi.org/10.1109/icra55743.2025.11128046) — Chenglong Qian, Yang Xu, Xiufang Shi et al. · *College of Information Engineering, Zhejiang University of Technology, Hangzhou, China,…*
- ★ [CRAB: Camera-Radar Fusion for Reducing Depth Ambiguity in Backward Projection Based View Transformation](https://doi.org/10.1109/icra55743.2025.11128369) — In-Jae Lee, Sihwan Hwang, Youngseok Kim et al. · *Seoul National University, Interdisciplinary Program in Artificial intelligence*
- ★ [Human Activity Recognition by Using Enhanced Radar Point Cloud 2D Histograms and Doppler Feature Fusion](https://doi.org/10.1109/icra55743.2025.11128165) — Guanghang Liao, Jieming Ma, Fei Luo · *School of Computing and Information Technology, Great Bay University, Dongguan, China,…*
- ★ [Introspective Loop Closure for SLAM with 4D Imaging Radar](https://doi.org/10.1109/icra55743.2025.11127330) — Maximilian Hilger, Vladimír Kubelka, Daniel Adolfsson et al. · *Technical University of Munich, Munich Institute for Robotics and Machine Intelligence…*
- ★ [mmDEAR: mmWave Point Cloud Density Enhancement for Accurate Human Body Reconstruction](https://doi.org/10.1109/icra55743.2025.11127877) — Jiarui Yang, Songpengcheng Xia, Zengyuan Lai et al. · *School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong…*
- ★ [Structure-Aware Radar-Camera Depth Estimation](https://doi.org/10.1109/icra55743.2025.11128760) — Fuyi Zhang, Zhu Yu, Chunhao Li et al. · *College of Information Science and Electronic Engineering, Zhejiang University,…*
- ★ [UniBEVFusion: Unified Radar-Vision Bevfusion for 3D Object Detection](https://doi.org/10.1109/icra55743.2025.11128067) — Haocheng Zhao, Runwei Guan, Taoyu Wu et al. · *Institute of Deep Perception Technology, JITRI, Wuxi, China*
- ★ [Unleashing HyDRa: Hybrid Fusion, Depth Consistency and Radar for Unified 3D Perception](https://doi.org/10.1109/icra55743.2025.11127412) — Philipp Wolters, Johannes Gilg, Torben Teepe et al. · *Technical University of Munich, Germany*
- [4DRadDet: Cluster-Queried Enhanced 3D Object Detection with 4D Radar](https://doi.org/10.1109/icra55743.2025.11127889) — Caien Weng, Xin Bi, Panpan Tong et al. · *School of Automotive Studies, Tongji University, Shanghai, China, 201804*
- [CAO-RONet: A Robust 4D Radar Odometry with Exploring More Information from Low-Quality Points](https://doi.org/10.1109/icra55743.2025.11128487) — Zhiheng Li, Yubo Cui, Ningyuan Huang et al. · *Northeastern University, Faculty of Robot Science and Engineering, Shenyang, China*
- [CubeDN: Real-Time Drone Detection in 3D Space from Dual mmWave Radar Cubes](https://doi.org/10.1109/icra55743.2025.11127766) — Yuan Fang, Fangzhan Shi, Xijia Wei et al. · *University College London, Department of Security and Crime Science, United Kingdom*
- [Digital Beamforming Enhanced Radar Odometry](https://doi.org/10.1109/icra55743.2025.11127292) — Jingqi Jiang, Shida Xu, Kaicheng Zhang et al. · *Imperial College London, I-X and Department of Electrical and Electronic Engineering, UK*
- [Doppler Former: Velocity Supervision of Raw Radar Data](https://doi.org/10.1109/icra55743.2025.11127345) — Shuo Zhao, Wei Sun, Huadong Li et al. · *MEGVII Technology, China*
- [GaRLIO: Gravity Enhanced Radar-LiDAR-Inertial Odometry](https://doi.org/10.1109/icra55743.2025.11128334) — Chiyun Noh, Wooseong Yang, Minwoo Jung et al. · *SNU, Dept. of Mechanical Engineering, Seoul, S. Korea*
- [Ground-Aware Automotive Radar Odometry](https://doi.org/10.1109/icra55743.2025.11128161) — Daniel Casado Herraez, Franz Kaschner, Matthias Zeller et al. · *CARIAD SE, Germany*
- [Ground-Optimized 4D Radar-Inertial Odometry Via Continuous Velocity Integration Using Gaussian Process](https://doi.org/10.1109/icra55743.2025.11127572) — Wooseong Yang, Hyesu Jang, Ayoung Kim · *SNU, Dept. of Mechanical Engineering, Seoul, S. Korea*
- [HeRCULES: Heterogeneous Radar Dataset in Complex Urban Environment for Multi-Session Radar SLAM](https://doi.org/10.1109/icra55743.2025.11128678) — Hanjun Kim, Minwoo Jung, Chiyun Noh et al. · *SNU, Dept. of Future Automotive Mobility, Seoul, S. Korea*
- [Radar Teach and Repeat: Architecture and Initial Field Testing](https://doi.org/10.1109/icra55743.2025.11128412) — Xinyuan Qiao, Alexander Krawciw, Sven Lilge et al. · *University of Toronto Robotics Institute, University of Toronto, Toronto, Ontario,…*
- [Radar4VoxMap: Accurate Odometry from Blurred Radar Observations](https://doi.org/10.1109/icra55743.2025.11128118) — Jiwon Seok, Soyeong Kim, Jaeyoung Jo et al. · *Hanyang University, Department of Automotive Engineering, Seoul, Republic of Korea*
- [RadarMask: A Novel End-to-End Sparse Millimeter-Wave Radar Sequence Panoptic Segmentation and Tracking Method](https://doi.org/10.1109/icra55743.2025.11128555) — Yubo Guo, Gang Peng, Qiang Gao · *School of Artificial Intelligence and Automation, Huazhong University of Science and…*
- [Robust 4D Radar-Aided Inertial Navigation for Aerial Vehicles](https://doi.org/10.1109/icra55743.2025.11128496) — Jinwen Zhu, Jun Hu, Xudong Zhao et al. · *Meituan UAV, Beijing, China*
- [Talk2Radar: Bridging Natural Language with 4D mmWave Radar for 3D Referring Expression Comprehension](https://doi.org/10.1109/icra55743.2025.11128399) — Runwei Guan, Ruixiao Zhang, Ningwei Ouyang et al. · *Institute of Deep Perception Technology, JITRI, Wuxi, China*
- [TDFANet: Encoding Sequential 4D Radar Point Clouds Using Trajectory-Guided Deformable Feature Aggregation for Place Recognition](https://doi.org/10.1109/icra55743.2025.11127648) — Shouyi Lu, Guirong Zhuo, Haitao Wang et al. · *School of Automotive Studies, Tongji University, Shanghai, China*


### 2026 (14)

- ★★ [View Synthesis and 6DoF Pose Estimation in mmWave Radar Neural Radiance Fields](https://doi.org/10.1109/icra57385.2026.11696279) — Ahmad Kamari, Hemant Kumar Narsani, Nan Wu et al. · *George Mason University*
- ★ [4D Radar Diffusion with Adaptive Visual-Aided Condition for Point Cloud Enhancement](https://doi.org/10.1109/icra57385.2026.11696452) — Renxiang Xiao, Yuanfan Zhang, Wei Liu et al. · *Harbin Institute of Technology*
- ★ [MSDNet: Efficient 4D Radar Super-Resolution via Multi-Stage Distillation](https://doi.org/10.1109/icra57385.2026.11697541) — Minqing Huang, Shouyi Lu, Boyuan Zheng et al. · *Tongji University*
- ★ [RadarSFD: Single-Frame Diffusion with Pretrained Priors for Radar Point Clouds](https://doi.org/10.1109/icra57385.2026.11695739) — Bin Zhao, Nakul Garg · *Rice University*
- ★ [SpaRC: Sparse Radar-Camera Fusion for 3D Object Detection](https://doi.org/10.1109/icra57385.2026.11696130) — Philipp Wolters, Johannes Gilg, Torben Teepe et al. · *Technical University of Munich*
- ★ [SRCF-UAV: Sparse Radar-Camera Fusion for 3D UAV Detection](https://doi.org/10.1109/icra57385.2026.11696672) — Yiming Zhao, Zijun Gong, Yang Yang et al. · *The Hong Kong University of Science and Technology (Guangzhou)*
- [4DRaL: Bridging 4D Radar with LiDAR for Place Recognition using Knowledge Distillation](https://doi.org/10.1109/icra57385.2026.11696222) — Ningyuan Huang, Zhiheng Li, Zheng Fang · *Northeastern University*
- [CFEAR-Teach-and-Repeat: Fast and Accurate Radar-only Localization](https://doi.org/10.1109/icra57385.2026.11697231) — Maximilian Hilger, Daniel Adolfsson, Ralf Becker et al. · *Technical University of Munich*
- [Dr-PoGO: Direct Radar Pose-Graph Optimization](https://doi.org/10.1109/icra57385.2026.11696879) — Cedric Le Gentil, Weican Li, Leonardo Brizi et al. · *University of Toronto*
- [Fully Polar Coordinate Object Detection: A Constraint-Based Polar Bounding Box Approach for LiDAR and Scanning Radar](https://doi.org/10.1109/icra57385.2026.11696654) — Shu-Heng Lin, Chieh-Chih Wang, Wen-Chieh Lin · *National Yang Ming Chiao Tung University*
- [How IMU Drift Influences Multi-Radar Inertial Odometry for Ground Robots in Subterranean Terrains](https://doi.org/10.1109/icra57385.2026.11695852) — Moumita Mukherjee, Magnus Norén, Anton Koval et al. · *Luleå University of Technology*
- [MotionNet-PGA: MotionNet with Polar-Guided Attention for Moving Object Segmentation in Scanning Radar](https://doi.org/10.1109/icra57385.2026.11696301) — Ren-Yi Yuan, Chieh-Chih Wang, Wen-Chieh Lin · *National Yang Ming Chiao Tung University*
- [Omnidirectional Solid-State mmWave Radar Perception for UAV Power Line Collision Avoidance](https://doi.org/10.1109/icra57385.2026.11696714) — Nicolaj Haarhøj Malle, Emad Ebeid · *University of Southern*
- [RaCo-SLAM: A Physics-Informed 4D Radar SLAM with Co-visibility Consistency Factor](https://doi.org/10.1109/icra57385.2026.11697519) — Zishun Deng, Wanbiao Lin, Can Li et al. · *Nankai University*


## IROS

_CCF-B robotics venue, added by request._


### 2024 (18)

- ★★ [Automatic Spatial Calibration of Near-Field MIMO Radar With Respect to Optical Depth Sensors](https://doi.org/10.1109/iros58592.2024.10801705) — Vanessa Wirth, Johanna Bräunig, Danti Khouri et al. · *Friedrich-Alexander-Universität, Visual Computing Erlangen (VCE), Erlangen-Nürnberg,…*
- ★★ [NeRF-enabled Analysis-Through-Synthesis for ISAR Imaging of Small Everyday Objects with Sparse and Noisy UWB Radar Data](https://doi.org/10.1109/iros58592.2024.10801921) — Md Farhan Tasnim Oshim, Albert Reed, Suren Jayasuriya et al. · *University of Massachusetts, Manning College of Information and Computer Sciences,…*
- ★ [Adaptive Visual-Aided 4D Radar Odometry Through Transformer-Based Feature Fusion](https://doi.org/10.1109/iros58592.2024.10802367) — Yuanfan Zhang, Renxiang Xiao, Ziyang Hong et al. · *Harbin Institute of Technology, School of Computer Science and Technology, Shenzhen,…*
- ★ [AnytimeFusion: Parameter-free RGB Camera-Radar Sensor Fusion Algorithm in Complex Maritime Situations](https://doi.org/10.1109/iros58592.2024.10801864) — Yeongha Shin, Hanguen Kim, Jinwhan Kim · *Seadronix Corp, South Korea*
- ★ [ASY-VRNet: Waterway Panoptic Driving Perception Model based on Asymmetric Fair Fusion of Vision and 4D mmWave Radar](https://doi.org/10.1109/iros58592.2024.10802447) — Runwei Guan, Shanliang Yao, Ka Lok Man et al. · *University of Liverpool, Department of EEE, Liverpool, UK*
- ★ [BEVCar: Camera-Radar Fusion for BEV Map and Object Segmentation](https://doi.org/10.1109/iros58592.2024.10802147) — Jonas Schramm, Niclas Vödisch, Kürsat Petek et al. · *University of Freiburg, Department of Computer Science, Germany*
- ★ [CR3DT: Camera-RADAR Fusion for 3D Detection and Tracking](https://doi.org/10.1109/iros58592.2024.10801848) — Nicolas Baumann, Michael Baumgartner, Edoardo Ghignone et al. · *ETH Zurich, Center for Project-Based Learning, D-ITET*
- ★ [CRPlace: Camera-Radar Fusion with BEV Representation for Place Recognition](https://doi.org/10.1109/iros58592.2024.10802267) — Shaowei Fu, Yifan Duan, Yao Li et al. · *University of Science and Technology of China, School of Computer Science and…*
- [Advancements in Radar Odometry](https://doi.org/10.1109/iros58592.2024.10802141) — Matteo Frosi, Mirko Usuelli, Matteo Matteucci · *Politecnico di Milano, Department of Electronics Information and Bioengineering, Milan,…*
- [Augmenting Vision with Radar for All-weather Geo-localization without a Prior HD Map](https://doi.org/10.1109/iros58592.2024.10802744) — Can Dong, Ziyang Hong, Siru Li et al. · *Harbin Institute of Technology, School of Mechanical Engineering and Automation,…*
- [Autonomous Power Line Tracking with mmWave Radar](https://doi.org/10.1109/iros58592.2024.10802812) — Nicolaj Haarhøj Malle, Emad Ebeid · *University of Southern Denmark, Drone Infrastructure Inspection and Interaction Group*
- [Co-RaL: Complementary Radar-Leg Odometry with 4-DoF Optimization and Rolling Contact](https://doi.org/10.1109/iros58592.2024.10801960) — Sangwoo Jung, Wooseong Yang, Ayoung Kim · *SNU, Department of Mechanical Engineering, Seoul, S. Korea*
- [DeRO: Dead Reckoning Based on Radar Odometry With Accelerometers Aided for Robot Localization](https://doi.org/10.1109/iros58592.2024.10801645) — Hoang Viet Do, Yong Hun Kim, Joo Han Lee et al. · *Sejong University, Intelligent Navigation and Control Systems Laboratory (iNCSL),…*
- [RaNDT SLAM: Radar SLAM Based on Intensity-Augmented Normal Distributions Transform](https://doi.org/10.1109/iros58592.2024.10802458) — Maximilian Hilger, Nils Mandischer, Burkhard Corves · *RWTH Aachen University, Institute of Mechanism Theory, Machine Dynamics and Robotics,…*
- [RMap: Millimeter-Wave Radar Mapping Through Volumetric Upsampling](https://doi.org/10.1109/iros58592.2024.10801827) — Ajay Narasimha Mopidevi, Kyle Harlow, Christoffer Heckman · *University of Colorado Boulder, Department of Computer Science, Boulder, CO, USA*
- [Road Boundary Estimation Using Sparse Automotive Radar Inputs](https://doi.org/10.1109/iros58592.2024.10802490) — Aaron Kingery, Dezhen Song · *Texas A&M University, CSE Department, College Station, TX, USA, 77843*
- [Roofus: Learning-based Robotic Moisture Mapping on Flat Rooftops with Ground Penetrating Radar](https://doi.org/10.1109/iros58592.2024.10802148) — Kevin Lee, Wei-Heng Lin, Talha Javed et al. · *Building Diagnostic Robotics, Inc., Brooklyn, NY, USA, 11201*
- [Tightly-Coupled Factor Graph Formulation For Radar-Inertial Odometry](https://doi.org/10.1109/iros58592.2024.10801945) — Jan Michalczyk, Julius Quell, Florian Steidle et al. · *University of Klagenfurt, Control of Networked Systems Group, Austria*


### 2025 (18)

- ★ [R2LDM: An Efficient 4D Radar Super-Resolution Framework Leveraging Diffusion Model](https://doi.org/10.1109/iros60139.2025.11246739) — Boyuan Zheng, Shouyi Lu, Renbo Huang et al. · *Tongji University, School of Automotive Studies, Shanghai, China, 201804*
- ★ [REOcc: Camera-Radar Fusion with Radar Feature Enrichment for 3D Occupancy Prediction](https://doi.org/10.1109/iros60139.2025.11246246) — Chaehee Song, Sanmin Kim, Hyeonjun Jeong et al. · *Korea Advanced Institute of Science and Technology (KAIST), School of Electrical…*
- [Class-Aware PillarMix: Can Mixed Sample Data Augmentation Enhance 3D Object Detection with Radar Point Clouds?](https://doi.org/10.1109/iros60139.2025.11246852) — Miao Zhang, Sherif Abdulatif, Benedikt Loesch et al. · *Robert Bosch GmbH, Corporate Research, Germany, 71272*
- [CORENet: Cross-Modal 4D Radar Denoising Network with LiDAR Supervision for Autonomous Driving](https://doi.org/10.1109/iros60139.2025.11246433) — Fuyang Liu, Jilin Mei, Fangyuan Mao et al. · *Institute of Computing Technology, Chinese Academy of Sciences, China*
- [Design and Development of a GPR-Equipped Robot for Full-space External Diseases Detection in Drainage Pipelines](https://doi.org/10.1109/iros60139.2025.11246503) — Yuanjin Fang, Feng Yang, Xu Qiao et al. · *China University of Mining and Technology-Beijing, School of Artificial Intelligence,…*
- [ELMAR: Enhancing LiDAR Detection with 4D Radar Motion Awareness and Cross-modal Uncertainty](https://doi.org/10.1109/iros60139.2025.11246399) — Xiangyuan Peng, Miao Tang, Huawei Sun et al. · *Technical University of Munich and Infineon Technologies AG*
- [Impact of Temporal Delay on Radar-Inertial Odometry](https://doi.org/10.1109/iros60139.2025.11246946) — Vlaho-Josip Štironja, Luka Petrović, Juraj Peršić et al. · *University of Zagreb, Faculty of Electrical Engineering and Computing, Laboratory for…*
- [Indoor FireRescue Radar: 4D Indoor Millimeter Wave Dataset and Analysis for Hazardous Environment Perception](https://doi.org/10.1109/iros60139.2025.11246924) — Kangkang Duan, Zehao Zhu, Zhengbo Zou · *The University of British Columbia, Vancouver, Canada, V6T 1Z4*
- [Learning Point Correspondences In Radar 3D Point Clouds For Radar-Inertial Odometry](https://doi.org/10.1109/iros60139.2025.11246451) — Jan Michalczyk, Stephan Weiss, Jan Steinbrener · *University of Klagenfurt, Control of Networked Systems Group, Austria*
- [LGDD: Local-Global Synergistic Dual-Branch 3D Object Detection Using 4D Radar](https://doi.org/10.1109/iros60139.2025.11246504) — Xiaokai Bai, Qin Yang, Zili Zhou et al. · *Zhejiang University, College of Information Science and Electronic Engineering,…*
- [mmWave Radar-Based Non-Line-of-Sight Pedestrian Localization at T-Junctions Utilizing Road Layout Extraction via Camera](https://doi.org/10.1109/iros60139.2025.11246461) — Byeonggyu Park, Hee-Yeun Kim, Byonghyok Choi et al. · *Seoul National University*
- [NanoMVG: USV-Centric Low-Power Multi-Task Visual Grounding based on Prompt-Guided Camera and 4D mmWave Radar](https://doi.org/10.1109/iros60139.2025.11246532) — Runwei Guan, Jianan Liu, Liye Jia et al. · *University of Liverpool, Department of EEE, Liverpool, UK*
- [RaGNNarok: A Light-Weight Graph Neural Network for Enhancing Radar Point Clouds on Unmanned Ground Vehicles](https://doi.org/10.1109/iros60139.2025.11245944) — David Hunt, Shaocheng Luo, Spencer Hallyburton et al. · *Duke University, Department of Electrical and Computer Engineering, Durham, NC, USA,…*
- [RDN: An Efficient Denoising Network for 4D Radar Point Clouds](https://doi.org/10.1109/iros60139.2025.11246274) — Ningyuan Huang, Zhiheng Li, Chenglin Pang et al. · *Northeastern University, Faculty of Robot Science and Engineering, Shenyang, China*
- [RoCaRS: Robust Camera-Radar BEV Segmentation for Sensor Failure Scenarios](https://doi.org/10.1109/iros60139.2025.11246952) — Byounghun Park, Jeongtae Kim, Yongjae Cho et al. · *Hanyang University, Department of Future Mobility, Seoul, Republic of Korea, 04763*
- [Simulating Automotive Radar with Lidar and Camera Inputs](https://doi.org/10.1109/iros60139.2025.11247276) — Peili Song, Dezhen Song, Yifan Yang et al. · *Nankai University, Institute of Robotics and Automatic Information System, Tianjin,…*
- [VISC: mmWave Radar Scene Flow Estimation using Pervasive Visual-Inertial Supervision](https://doi.org/10.1109/iros60139.2025.11246830) — Kezhong Liu, Yiwen Zhou, Mozi Chen et al. · *Wuhan University of Technology, State Key Laboratory of Maritime Technology and Safety,…*
- [VoxEKF-RIO: A 4D Radar Inertial Odometry Based on Incremental Voxel Map and Iterated Kalman Filter](https://doi.org/10.1109/iros60139.2025.11247427) — Jiawei Shen, Chenyu Shen, Zishun Deng et al. · *Nankai University, Institute of Robotics & Automatic Information System, Tianjin, CHN*


---

## Notes

- Snapshot: 2026-11-07. Authors and first affiliations from Crossref, publisher pages, and PDF first pages.
- CVPR / ICCV / ECCV / NeurIPS / ICML: full title scan (37,560 titles).
- AAAI: full Crossref harvest by ISSN (11,273 records). ACM MM: Crossref proceedings 2024–2026.
- ICRA 2024–2026 / IROS 2024–2025: full proceedings harvest via Crossref (7,939 papers).
- `—` marks a few entries whose publisher hides the affiliation (mostly AAAI).
- ECCV 2026 not yet indexed by ECVA; IJCAI excluded by scope; ICLR is not a CCF-A venue.

## Contributing

Open a PR adding one line under the right venue and year: `- [Title](url) — Authors · Affiliation`, prefixed with `★★` / `★` / `☆`.

## License

[CC BY 4.0](LICENSE).
