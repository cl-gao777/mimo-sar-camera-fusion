# MIMO-SAR × Camera Fusion — Paper List (2024–2026)

204 papers from CVPR · ICCV · ECCV · NeurIPS · ICML · AAAI · ACM MM · ICRA · IROS, 2024–2026.

**Finding:** zero MIMO-SAR imaging papers. SAR appears as a downstream modality (detection, segmentation, generation), never as an imaging problem. The closest existing work to camera-assisted MIMO radar is a near-field **MIMO radar ↔ optical depth sensor calibration** paper at IROS 2024.

`★` marks the 20 SAR/ISAR papers.

**Start here:** [SOMA](https://ojs.aaai.org/index.php/AAAI/article/view/37939) · [DenoDet V2](https://ojs.aaai.org/index.php/AAAI/article/view/37761) · [DART](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_DART_Implicit_Doppler_Tomography_for_Radar_Novel_View_Synthesis_CVPR_2024_paper.html) · [RC-AutoCalib](https://openaccess.thecvf.com/content/CVPR2025/html/Luu_RC-AutoCalib_An_End-to-End_Radar-Camera_Automatic_Calibration_Network_CVPR_2025_paper.html) · [MIMO radar–optical calibration](https://doi.org/10.1109/iros58592.2024.10801705) · [MM-OVSeg](https://openaccess.thecvf.com/content/CVPR2026/html/Wei_MM-OVSeg_Multimodal_Optical-SAR_Fusion_for_Open-Vocabulary_Segmentation_in_Remote_Sensing_CVPR_2026_paper.html)

---

## Contents

[CVPR (40)](#cvpr) · [ICCV (11)](#iccv) · [ECCV (8)](#eccv) · [NeurIPS (11)](#neurips) · [ICML (5)](#icml) · [AAAI (25)](#aaai) · [ACM MM (10)](#acm-mm) · [ICRA (58)](#icra) · [IROS (36)](#iros)

---


## CVPR


### 2024 (9)

- [CRKD: Enhanced Camera-Radar Object Detection with Cross-modality Knowledge Distillation](https://openaccess.thecvf.com/content/CVPR2024/html/Zhao_CRKD_Enhanced_Camera-Radar_Object_Detection_with_Cross-modality_Knowledge_Distillation_CVPR_2024_paper.html)
- [DART: Implicit Doppler Tomography for Radar Novel View Synthesis](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_DART_Implicit_Doppler_Tomography_for_Radar_Novel_View_Synthesis_CVPR_2024_paper.html)
- [RadarDistill: Boosting Radar-based Object Detection Performance via Knowledge Distillation from LiDAR Features](https://openaccess.thecvf.com/content/CVPR2024/html/Bang_RadarDistill_Boosting_Radar-based_Object_Detection_Performance_via_Knowledge_Distillation_from_CVPR_2024_paper.html)
- [RadSimReal: Bridging the Gap Between Synthetic and Real Data in Radar Object Detection With Simulation](https://openaccess.thecvf.com/content/CVPR2024/html/Bialer_RadSimReal_Bridging_the_Gap_Between_Synthetic_and_Real_Data_in_CVPR_2024_paper.html)
- [RCBEVDet: Radar-camera Fusion in Bird's Eye View for 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2024/html/Lin_RCBEVDet_Radar-camera_Fusion_in_Birds_Eye_View_for_3D_Object_CVPR_2024_paper.html)
- [SIRA: Scalable Inter-frame Relation and Association for Radar Perception](https://openaccess.thecvf.com/content/CVPR2024/html/Yataka_SIRA_Scalable_Inter-frame_Relation_and_Association_for_Radar_Perception_CVPR_2024_paper.html)
- [Towards Robust 3D Object Detection with LiDAR and 4D Radar Fusion in Various Weather Conditions](https://openaccess.thecvf.com/content/CVPR2024/html/Chae_Towards_Robust_3D_Object_Detection_with_LiDAR_and_4D_Radar_CVPR_2024_paper.html)
- [TransLoc4D: Transformer-based 4D Radar Place Recognition](https://openaccess.thecvf.com/content/CVPR2024/html/Peng_TransLoc4D_Transformer-based_4D_Radar_Place_Recognition_CVPR_2024_paper.html)
- ★ [Unleashing Channel Potential: Space-Frequency Selection Convolution for SAR Object Detection](https://openaccess.thecvf.com/content/CVPR2024/html/Li_Unleashing_Channel_Potential_Space-Frequency_Selection_Convolution_for_SAR_Object_Detection_CVPR_2024_paper.html)


### 2025 (8)

- ★ [Cross-Rejective Open-Set SAR Image Registration](https://openaccess.thecvf.com/content/CVPR2025/html/Mao_Cross-Rejective_Open-Set_SAR_Image_Registration_CVPR_2025_paper.html)
- [MVDoppler-Pose: Multi-Modal Multi-View mmWave Sensing for Long-Distance Self-Occluded Human Walking Pose Estimation](https://openaccess.thecvf.com/content/CVPR2025/html/Choi_MVDoppler-Pose_Multi-Modal_Multi-View_mmWave_Sensing_for_Long-Distance_Self-Occluded_Human_Walking_CVPR_2025_paper.html)
- [RaCFormer: Towards High-Quality 3D Object Detection via Query-based Radar-Camera Fusion](https://openaccess.thecvf.com/content/CVPR2025/html/Chu_RaCFormer_Towards_High-Quality_3D_Object_Detection_via_Query-based_Radar-Camera_Fusion_CVPR_2025_paper.html)
- [RC-AutoCalib: An End-to-End Radar-Camera Automatic Calibration Network](https://openaccess.thecvf.com/content/CVPR2025/html/Luu_RC-AutoCalib_An_End-to-End_Radar-Camera_Automatic_Calibration_Network_CVPR_2025_paper.html)
- [RICCARDO: Radar Hit Prediction and Convolution for Camera-Radar 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2025/html/Long_RICCARDO_Radar_Hit_Prediction_and_Convolution_for_Camera-Radar_3D_Object_CVPR_2025_paper.html)
- ★ [RSAR: Restricted State Angle Resolver and Rotated SAR Benchmark](https://openaccess.thecvf.com/content/CVPR2025/html/Zhang_RSAR_Restricted_State_Angle_Resolver_and_Rotated_SAR_Benchmark_CVPR_2025_paper.html)
- [TacoDepth: Towards Efficient Radar-Camera Depth Estimation with One-stage Fusion](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_TacoDepth_Towards_Efficient_Radar-Camera_Depth_Estimation_with_One-stage_Fusion_CVPR_2025_paper.html)
- [V2X-R: Cooperative LiDAR-4D Radar Fusion with Denoising Diffusion for 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2025/html/Huang_V2X-R_Cooperative_LiDAR-4D_Radar_Fusion_with_Denoising_Diffusion_for_3D_CVPR_2025_paper.html)


### 2026 (23)

- [AdaRadar: Rate Adaptive Spectral Compression for Radar-based Perception](https://openaccess.thecvf.com/content/CVPR2026/html/Park_AdaRadar_Rate_Adaptive_Spectral_Compression_for_Radar-based_Perception_CVPR_2026_paper.html)
- [DSERT-RoLL: Robust Multi-Modal Perception for Diverse Driving Conditions with Stereo Event-RGB-Thermal Cameras, 4D Radar, and Dual-LiDAR](https://openaccess.thecvf.com/content/CVPR2026/html/Cho_DSERT-RoLL_Robust_Multi-Modal_Perception_for_Diverse_Driving_Conditions_with_Stereo_CVPR_2026_paper.html)
- [Expanding mmWave Datasets for Human Pose Estimation with Unlabeled Data and LiDAR Datasets](https://openaccess.thecvf.com/content/CVPR2026/html/Peng_Expanding_mmWave_Datasets_for_Human_Pose_Estimation_with_Unlabeled_Data_CVPR_2026_paper.html)
- ★ [FUSAR-GPT: A Spatiotemporal Feature-Embedded and Two-Stage Decoupled Visual Language Model for SAR Imagery](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_FUSAR-GPT_A_Spatiotemporal_Feature-Embedded_and_Two-Stage_Decoupled_Visual_Language_Model_CVPR_2026_paper.html)
- [Hybrid Robust Collaborative Perception with LiDAR-4D Radar Fusion under Adverse Weather Conditions](https://openaccess.thecvf.com/content/CVPR2026/html/Yang_Hybrid_Robust_Collaborative_Perception_with_LiDAR-4D_Radar_Fusion_under_Adverse_CVPR_2026_paper.html)
- [M4Human: A Large-Scale Multimodal mmWave Radar Benchmark for Human Mesh Reconstruction](https://openaccess.thecvf.com/content/CVPR2026/html/Fan_M4Human_A_Large-Scale_Multimodal_mmWave_Radar_Benchmark_for_Human_Mesh_CVPR_2026_paper.html)
- [MARSS: Radar Semantic Segmentation via Modular Attention and State Space Models](https://openaccess.thecvf.com/content/CVPR2026/html/Chen_MARSS_Radar_Semantic_Segmentation_via_Modular_Attention_and_State_Space_CVPR_2026_paper.html)
- ★ [MM-OVSeg: Multimodal Optical-SAR Fusion for Open-Vocabulary Segmentation in Remote Sensing](https://openaccess.thecvf.com/content/CVPR2026/html/Wei_MM-OVSeg_Multimodal_Optical-SAR_Fusion_for_Open-Vocabulary_Segmentation_in_Remote_Sensing_CVPR_2026_paper.html)
- [mmWaveFlow: Unified Enhancement and Generation of mmWave Human Point Clouds](https://openaccess.thecvf.com/content/CVPR2026/html/Su_mmWaveFlow_Unified_Enhancement_and_Generation_of_mmWave_Human_Point_Clouds_CVPR_2026_paper.html)
- ★ [MOS: Mitigating Optical-SAR Modality Gap for Cross-Modal Ship Re-Identification](https://openaccess.thecvf.com/content/CVPR2026/html/Zhao_MOS_Mitigating_Optical-SAR_Modality_Gap_for_Cross-Modal_Ship_Re-Identification_CVPR_2026_paper.html)
- [R4Det: 4D Radar-Camera Fusion for High-Performance 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2026/html/Xia_R4Det_4D_Radar-Camera_Fusion_for_High-Performance_3D_Object_Detection_CVPR_2026_paper.html)
- [Radar-Guided Polynomial Fitting for Metric Depth Estimation](https://openaccess.thecvf.com/content/CVPR2026/html/Rim_Radar-Guided_Polynomial_Fitting_for_Metric_Depth_Estimation_CVPR_2026_paper.html)
- [RaGS: Unleashing 3D Gaussian Splatting from 4D Radar and Monocular Cue for 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2026/html/Bai_RaGS_Unleashing_3D_Gaussian_Splatting_from_4D_Radar_and_Monocular_CVPR_2026_paper.html)
- [Rascene: High-Fidelity 3D Scene Imaging with mmWave Communication Signals](https://openaccess.thecvf.com/content/CVPR2026/html/Song_Rascene_High-Fidelity_3D_Scene_Imaging_with_mmWave_Communication_Signals_CVPR_2026_paper.html)
- [RaUF: Learning the Spatial Uncertainty Field of Radar](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_RaUF_Learning_the_Spatial_Uncertainty_Field_of_Radar_CVPR_2026_paper.html)
- [RAVEN: Radar Adaptive Vision Encoders for Efficient Chirp-wise Object Detection and Segmentation](https://openaccess.thecvf.com/content/CVPR2026/html/Sen_RAVEN_Radar_Adaptive_Vision_Encoders_for_Efficient_Chirp-wise_Object_Detection_CVPR_2026_paper.html)
- [RF4D:Neural Radar Fields for Novel View Synthesis in Outdoor Dynamic Scenes](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_RF4DNeural_Radar_Fields_for_Novel_View_Synthesis_in_Outdoor_Dynamic_CVPR_2026_paper.html)
- [RISE: Single Static Radar-based Indoor Scene Understanding](https://openaccess.thecvf.com/content/CVPR2026/html/Zhou_RISE_Single_Static_Radar-based_Indoor_Scene_Understanding_CVPR_2026_paper.html)
- [RPGFusion: 4D Radar Prior-Guided Multi-Modal Fusion for 3D Detection](https://openaccess.thecvf.com/content/CVPR2026/html/Qiu_RPGFusion_4D_Radar_Prior-Guided_Multi-Modal_Fusion_for_3D_Detection_CVPR_2026_paper.html)
- ★ [SARMAE: Masked Autoencoder for SAR Representation Learning](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_SARMAE_Masked_Autoencoder_for_SAR_Representation_Learning_CVPR_2026_paper.html)
- [Seeing through boxes: Non-Line-of-Sight 3D Reconstruction from Radar Signals](https://openaccess.thecvf.com/content/CVPR2026/html/Lu_Seeing_through_boxes_Non-Line-of-Sight_3D_Reconstruction_from_Radar_Signals_CVPR_2026_paper.html)
- [Underground Plant Exploration: Non-Destructive 3D Root Assessment with GPR Based on Point Graph Neural Network](https://openaccess.thecvf.com/content/CVPR2026/html/Zhou_Underground_Plant_Exploration_Non-Destructive_3D_Root_Assessment_with_GPR_Based_CVPR_2026_paper.html)
- [X-band Radar Non-Line-of-Sight Imaging](https://openaccess.thecvf.com/content/CVPR2026/html/Du_X-band_Radar_Non-Line-of-Sight_Imaging_CVPR_2026_paper.html)


## ICCV


### 2025 (11)

- ★ [Cross-modal Ship Re-Identification via Optical and SAR Imagery: A Novel Dataset and Method](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_Cross-modal_Ship_Re-Identification_via_Optical_and_SAR_Imagery_A_Novel_ICCV_2025_paper.html)
- [CVFusion: Cross-View Fusion of 4D Radar and Camera for 3D Object Detection](https://openaccess.thecvf.com/content/ICCV2025/html/Zhong_CVFusion_Cross-View_Fusion_of_4D_Radar_and_Camera_for_3D_ICCV_2025_paper.html)
- [DoppDrive: Doppler-Driven Temporal Aggregation for Improved Radar Object Detection](https://openaccess.thecvf.com/content/ICCV2025/html/Haitman_DoppDrive_Doppler-Driven_Temporal_Aggregation_for_Improved_Radar_Object_Detection_ICCV_2025_paper.html)
- [Doppler-Aware LiDAR-RADAR Fusion for Weather-Robust 3D Detection](https://openaccess.thecvf.com/content/ICCV2025/html/Chae_Doppler-Aware_LiDAR-RADAR_Fusion_for_Weather-Robust_3D_Detection_ICCV_2025_paper.html)
- ★ [Ph-GAN: Physics-Inspired GAN for Generating SAR Images Under Limited Data](https://openaccess.thecvf.com/content/ICCV2025/html/Zhang_Ph-GAN_Physics-Inspired_GAN_for_Generating_SAR_Images_Under_Limited_Data_ICCV_2025_paper.html)
- [RadarSplat: Radar Gaussian Splatting for High-Fidelity Data Synthesis and 3D Reconstruction of Autonomous Driving Scenes](https://openaccess.thecvf.com/content/ICCV2025/html/Kung_RadarSplat_Radar_Gaussian_Splatting_for_High-Fidelity_Data_Synthesis_and_3D_ICCV_2025_paper.html)
- [RCTDistill: Cross-Modal Knowledge Distillation Framework for Radar-Camera 3D Object Detection with Temporal Fusion](https://openaccess.thecvf.com/content/ICCV2025/html/Bang_RCTDistill_Cross-Modal_Knowledge_Distillation_Framework_for_Radar-Camera_3D_Object_Detection_ICCV_2025_paper.html)
- [S3E: Self-Supervised State Estimation for Radar-Inertial System](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_S3E_Self-Supervised_State_Estimation_for_Radar-Inertial_System_ICCV_2025_paper.html)
- [Spatial Alignment and Temporal Matching Adapter for Video-Radar Remote Physiological Measurement](https://openaccess.thecvf.com/content/ICCV2025/html/Liang_Spatial_Alignment_and_Temporal_Matching_Adapter_for_Video-Radar_Remote_Physiological_ICCV_2025_paper.html)
- [TARS: Traffic-Aware Radar Scene Flow Estimation](https://openaccess.thecvf.com/content/ICCV2025/html/Wu_TARS_Traffic-Aware_Radar_Scene_Flow_Estimation_ICCV_2025_paper.html)
- [Towards Foundational Models for Single-Chip Radar](https://openaccess.thecvf.com/content/ICCV2025/html/Huang_Towards_Foundational_Models_for_Single-Chip_Radar_ICCV_2025_paper.html)


## ECCV

_CCF-B, kept for the CV-trio scope._


### 2024 (8)

- [CARB-Net: Camera-Assisted Radar-Based Network for Vulnerable Road User Detection](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/8101_ECCV_2024_paper.php)
- [LEROjD: Lidar Extended Radar-Only Object Detection](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/7776_ECCV_2024_paper.php)
- [LiDAR-based All-weather 3D Object Detection via Prompting and Distilling 4D Radar](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/7349_ECCV_2024_paper.php)
- [milliFlow: Scene Flow Estimation on mmWave Radar Point Cloud for Human Motion Sensing](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/3470_ECCV_2024_paper.php)
- [MMVR: Millimeter-wave Multi-View Radar Dataset and Benchmark for Indoor Perception](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/10205_ECCV_2024_paper.php)
- [RT-Pose: A 4D Radar-Tensor based 3D Human Pose Estimation and Localization Benchmark](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/7989_ECCV_2024_paper.php)
- [Sparse Beats Dense: Rethinking Supervision in Radar-Camera Depth Completion](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/6528_ECCV_2024_paper.php)
- [SparseRadNet: Sparse Perception Neural Network on Subsampled Radar Data](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/11537_ECCV_2024_paper.php)


## NeurIPS


### 2024 (7)

- [AdaPKC: PeakConv with Adaptive Peak Receptive Field for Radar Semantic Segmentation](https://proceedings.neurips.cc/paper_files/paper/2024/hash/f6b22ac37beb5da61efd4882082c9ecd-Abstract-Conference.html)
- [CRT-Fusion: Camera, Radar, Temporal Fusion Using  Motion Information  for 3D Object Detection](https://proceedings.neurips.cc/paper_files/paper/2024/hash/c49a28241640407b23bba8f2495f4bc9-Abstract-Conference.html)
- ★ [M3LEO: A Multi-Modal, Multi-Label Earth Observation Dataset Integrating Interferometric SAR and Multispectral Data](https://proceedings.neurips.cc/paper_files/paper/2024/hash/bd194b579f60879e04ca9ce8a4ea5da1-Abstract-Datasets_and_Benchmarks_Track.html)
- [RadarOcc: Robust 3D Occupancy Prediction with 4D Imaging Radar](https://proceedings.neurips.cc/paper_files/paper/2024/hash/b81d83165e3145a2e7d33bb5e33ea913-Abstract-Conference.html)
- [RETR: Multi-View Radar Detection Transformer for Indoor Perception](https://proceedings.neurips.cc/paper_files/paper/2024/hash/2341b14df6b4f684a30eb4e99807bea6-Abstract-Conference.html)
- ★ [SARDet-100K: Towards Open-Source Benchmark and ToolKit for Large-Scale SAR Object Detection](https://proceedings.neurips.cc/paper_files/paper/2024/hash/e7eb8128eb26eafbe901348df1dbacdc-Abstract-Conference.html)
- [TARSS-Net: Temporal-Aware Radar Semantic Segmentation Network](https://proceedings.neurips.cc/paper_files/paper/2024/hash/08a362bd4ae1934e099ce025f06039fe-Abstract-Conference.html)


### 2025 (4)

- [Non-Line-of-Sight 3D Reconstruction with Radar](https://neurips.cc/virtual/2025/poster/116868)
- [RadarQA: Multi-modal Quality Analysis of Weather Radar Forecasts](https://neurips.cc/virtual/2025/poster/117566)
- [RAPTR: Radar-based 3D Pose Estimation using Transformer](https://neurips.cc/virtual/2025/poster/119916)
- [V2X-Radar: A Multi-modal Dataset with 4D Radar for Cooperative Perception](https://neurips.cc/virtual/2025/poster/121426)


## ICML


### 2025 (1)

- ★ [Gamma Distribution PCA-Enhanced Feature Learning for Angle-Robust SAR Target Recognition](https://proceedings.mlr.press/v267/)


### 2026 (4)

- [Cardio-mmFlow: A Gaussian-Prior-Free Physics-Informed Flow Matching Framework for Electrocardiogram to mmWave Radar Synthesis](https://proceedings.mlr.press/v306/liu26ey.html)
- [Doppler Prompting for Stable mmWave-based Human Pose Estimation](https://proceedings.mlr.press/v306/zheng26g.html)
- [Frequency Matching in Spiking Neural Networks for mmWave Sensing](https://proceedings.mlr.press/v306/liao26e.html)
- [Weakly Supervised Cross-Modal Learning for 4D Radar Scene Flow Estimation](https://proceedings.mlr.press/v306/fu26r.html)


## AAAI


### 2024 (2)

- [RadarMOSEVE: A Spatial-Temporal Transformer Network for Radar-Only Moving Object Segmentation and Ego-Velocity Estimation](https://ojs.aaai.org/index.php/AAAI/article/view/28240)
- ★ [Statistically Principled Deep Learning for SAR Image Segmentation](https://ojs.aaai.org/index.php/AAAI/article/view/30549)


### 2025 (5)

- ★ [Dual Information Purification for Lightweight SAR Object Detection](https://ojs.aaai.org/index.php/AAAI/article/view/33004)
- [EDENet: Echo Direction Encoding Network for Place Recognition Based on Ground Penetrating Radar](https://ojs.aaai.org/index.php/AAAI/article/view/33092)
- [HGSFusion: Radar-Camera Fusion with Hybrid Generation and Synchronization for 3D Object Detection](https://ojs.aaai.org/index.php/AAAI/article/view/32328)
- [RCTrans: Radar-Camera Transformer via Radar Densifier and Sequential Decoder for 3D Object Detection](https://ojs.aaai.org/index.php/AAAI/article/view/32535)
- [SCKD: Semi-Supervised Cross-Modality Knowledge Distillation for 4D Radar Object Detection](https://ojs.aaai.org/index.php/AAAI/article/view/32966)


### 2026 (18)

- ★ [DenoDet V2: Phase-Amplitude Cross Denoising for SAR Object Detection](https://ojs.aaai.org/index.php/AAAI/article/view/37761)
- [DNOI-4DRO: Deep 4D Radar Odometry with Differentiable Neural-Optimization Iterations](https://ojs.aaai.org/index.php/AAAI/article/view/38914)
- ★ [HiFC-GAN: Hierarchical Feature-Constrained GAN for Optical-to-SAR Transfer in SAR Target Classification](https://ojs.aaai.org/index.php/AAAI/article/view/38342)
- [Indoor Multi-View Radar Object Detection via 3D Bounding Box Diffusion](https://ojs.aaai.org/index.php/AAAI/article/view/38939)
- [Learning 3D Occupancy from Beam Overlap in 2D Rotating mmWave Radar](https://ojs.aaai.org/index.php/AAAI/article/view/37371)
- [mmJEPA-ECG: Cross-Posture Robust Contactless Electrocardiogram Monitoring via Millimeter Wave Radar Sensing](https://ojs.aaai.org/index.php/AAAI/article/view/41242)
- [mmPred: Radar-based Human Motion Prediction in the Dark](https://ojs.aaai.org/index.php/AAAI/article/view/37378)
- [Multi-Window Gabor Transform Network for Ground Penetrating Radar B-Scan Image Reconstruction](https://ojs.aaai.org/index.php/AAAI/article/view/37947)
- [Radar Instance Transformer: Reliable Moving Instance Segmentation in Sparse Radar Point Clouds (Abstract Reprint)](https://ojs.aaai.org/index.php/AAAI/article/view/41421)
- [Radar-APLANC: Unsupervised Radar-based Heartbeat Sensing via Augmented Pseudo-Label and Noise Contrast](https://ojs.aaai.org/index.php/AAAI/article/view/37996)
- [RadarLLM: Empowering Large Language Models to Understand Human Motion from Millimeter-wave Point Cloud Sequence](https://ojs.aaai.org/index.php/AAAI/article/view/37500)
- [RadarMP: Motion Perception for 4D mmWave Radar in Autonomous Driving](https://ojs.aaai.org/index.php/AAAI/article/view/37323)
- [RaLD: Generating High-Resolution 3D Radar Point Clouds with Latent Diffusion](https://ojs.aaai.org/index.php/AAAI/article/view/38946)
- [RaLiFlow: Scene Flow Estimation with 4D Radar and LiDAR Point Clouds](https://ojs.aaai.org/index.php/AAAI/article/view/37404)
- ★ [SAR-DisentDM: A Semantic-Disentangled Diffusion Model for Limited-Data SAR Image Synthesis](https://ojs.aaai.org/index.php/AAAI/article/view/38165)
- ★ [SOMA: Feature Gradient Enhanced Affine-Flow Matching for SAR-Optical Registration](https://ojs.aaai.org/index.php/AAAI/article/view/37939)
- [Towards Accurate 3D Object Detection in Adverse Weather by Leveraging 4D Radar for LiDAR Geometry Enhancement](https://ojs.aaai.org/index.php/AAAI/article/view/37916)
- [WaveC2R: Wavelet-Driven Coarse-to-Refined Hierarchical Learning for Radar Retrieval](https://ojs.aaai.org/index.php/AAAI/article/view/37850)


## ACM MM


### 2024 (3)

- [FARFusion V2: A Geometry-based Radar-Camera Fusion Method on the Ground for Roadside Far-Range 3D Object Detection](https://doi.org/10.1145/3664647.3681128)
- ★ [Interpretable Matching of Optical-SAR Image via Dynamically Conditioned Diffusion Models](https://doi.org/10.1145/3664647.3681700)
- [SparseInteraction: Sparse Semantic Guidance for Radar and Camera 3D Object Detection](https://doi.org/10.1145/3664647.3681565)


### 2025 (3)

- [FGRFlow: Learning Fine-Grained Rigidity Scene Flow from 4D Radar Point Cloud](https://doi.org/10.1145/3746027.3755042)
- [Radar-Mamba: 4D Millimeter-Wave Point Cloud Enhancement via State Space Models](https://doi.org/10.1145/3746027.3755431)
- [Venus: Generating Large-scale mmWave Radar Data via Few 2D Videos for Gesture Recognition While Lying Down](https://doi.org/10.1145/3746027.3755399)


### 2026 (4)

- [Cross-Modal Generation: From Commodity WiFi to High-Fidelity mmWave and RFID Sensing](https://doi.org/10.1145/3767308.3836022)
- [ElevC2F: Elevation-Aware Coarse-to-Fine Fusion of 4D Radar and Camera for 3D Object Detection](https://doi.org/10.1145/3767308.3836599)
- [RemoPhysEmo: A Multimodal Emotion Dataset with Remotely Sensed Physiological Signals via Video and Radar](https://doi.org/10.1145/3767308.3838666)
- [SPRFusion: Semantic and Physics-driven Robust Radar-Camera Fusion for 3D Object Detection](https://doi.org/10.1145/3767308.3835982)


## ICRA

_CCF-B robotics venue, added by request._


### 2024 (20)

- [Degradation Resilient LiDAR-Radar-Inertial Odometry](https://doi.org/10.1109/icra57147.2024.10611444)
- [Diffusion-Based Point Cloud Super-Resolution for mmWave Radar Data](https://doi.org/10.1109/icra57147.2024.10611026)
- [Do we need scan-matching in radar odometry?](https://doi.org/10.1109/icra57147.2024.10610666)
- [Doppler-only Single-scan 3D Vehicle Odometry](https://doi.org/10.1109/icra57147.2024.10611199)
- [Dynamic Occupancy Grids for Object Detection: A Radar-Centric Approach](https://doi.org/10.1109/icra57147.2024.10610514)
- [Enhancing mmWave Radar Point Cloud via Visual-inertial Supervision](https://doi.org/10.1109/icra57147.2024.10610091)
- [Less is More: Physical-Enhanced Radar-Inertial Odometry](https://doi.org/10.1109/icra57147.2024.10611471)
- [LiRaFusion: Deep Adaptive LiDAR-Radar Fusion for 3D Object Detection](https://doi.org/10.1109/icra57147.2024.10611436)
- [MTRadSSD: A Multi-Task Single-Stage Detector for Object Detection and Free Space Analysis in Radar Point Clouds *](https://doi.org/10.1109/icra57147.2024.10611324)
- [Multi-Radar Inertial Odometry for 3D State Estimation using mmWave Imaging Radar](https://doi.org/10.1109/icra57147.2024.10611194)
- [Odometry Estimation by Fusing Multiple Radar Sensors and an Inertial Measurement Unit](https://doi.org/10.1109/icra57147.2024.10610446)
- [PillarGen: Enhancing Radar Point Cloud Density and Quality via Pillar-based Point Generation Network](https://doi.org/10.1109/icra57147.2024.10611144)
- [Radar Tracker: Moving Instance Tracking in Sparse and Noisy Radar Point Clouds](https://doi.org/10.1109/icra57147.2024.10610198)
- [Radar-Only Odometry and Mapping for Autonomous Vehicles](https://doi.org/10.1109/icra57147.2024.10610311)
- [RadarCam-Depth: Radar-Camera Fusion for Depth Estimation with Learned Metric Scale](https://doi.org/10.1109/icra57147.2024.10610929)
- [RaLF: Flow-based Global and Metric Radar Localization in LiDAR Maps](https://doi.org/10.1109/icra57147.2024.10610626)
- [RaTrack: Moving Object Detection and Tracking with 4D Radar Point Cloud](https://doi.org/10.1109/icra57147.2024.10610368)
- [RCM-Fusion: Radar-Camera Multi-Level Fusion for 3D Object Detection](https://doi.org/10.1109/icra57147.2024.10611449)
- [Robust 3D Object Detection from LiDAR-Radar Point Clouds via Cross-Modal Feature Augmentation](https://doi.org/10.1109/icra57147.2024.10610775)
- [Subsurface Feature-based Ground Robot/Vehicle Localization Using a Ground Penetrating Radar](https://doi.org/10.1109/icra57147.2024.10611579)


### 2025 (24)

- [4DRadDet: Cluster-Queried Enhanced 3D Object Detection with 4D Radar](https://doi.org/10.1109/icra55743.2025.11127889)
- [AF-RLIO: Adaptive Fusion of Radar-LiDAR-Inertial Information for Robust Odometry in Challenging Environments](https://doi.org/10.1109/icra55743.2025.11128046)
- [CAO-RONet: A Robust 4D Radar Odometry with Exploring More Information from Low-Quality Points](https://doi.org/10.1109/icra55743.2025.11128487)
- [CRAB: Camera-Radar Fusion for Reducing Depth Ambiguity in Backward Projection Based View Transformation](https://doi.org/10.1109/icra55743.2025.11128369)
- [CubeDN: Real-Time Drone Detection in 3D Space from Dual mmWave Radar Cubes](https://doi.org/10.1109/icra55743.2025.11127766)
- [Digital Beamforming Enhanced Radar Odometry](https://doi.org/10.1109/icra55743.2025.11127292)
- [Doppler Former: Velocity Supervision of Raw Radar Data](https://doi.org/10.1109/icra55743.2025.11127345)
- [GaRLIO: Gravity Enhanced Radar-LiDAR-Inertial Odometry](https://doi.org/10.1109/icra55743.2025.11128334)
- [Ground-Aware Automotive Radar Odometry](https://doi.org/10.1109/icra55743.2025.11128161)
- [Ground-Optimized 4D Radar-Inertial Odometry Via Continuous Velocity Integration Using Gaussian Process](https://doi.org/10.1109/icra55743.2025.11127572)
- [HeRCULES: Heterogeneous Radar Dataset in Complex Urban Environment for Multi-Session Radar SLAM](https://doi.org/10.1109/icra55743.2025.11128678)
- [Human Activity Recognition by Using Enhanced Radar Point Cloud 2D Histograms and Doppler Feature Fusion](https://doi.org/10.1109/icra55743.2025.11128165)
- [Introspective Loop Closure for SLAM with 4D Imaging Radar](https://doi.org/10.1109/icra55743.2025.11127330)
- [mmDEAR: mmWave Point Cloud Density Enhancement for Accurate Human Body Reconstruction](https://doi.org/10.1109/icra55743.2025.11127877)
- [Radar Teach and Repeat: Architecture and Initial Field Testing](https://doi.org/10.1109/icra55743.2025.11128412)
- [Radar4VoxMap: Accurate Odometry from Blurred Radar Observations](https://doi.org/10.1109/icra55743.2025.11128118)
- [RadarMask: A Novel End-to-End Sparse Millimeter-Wave Radar Sequence Panoptic Segmentation and Tracking Method](https://doi.org/10.1109/icra55743.2025.11128555)
- [RLCNet: A Novel Deep Feature-Matching-Based Method for Online Target-Free Radar-LiDAR Calibration](https://doi.org/10.1109/icra55743.2025.11127342)
- [Robust 4D Radar-Aided Inertial Navigation for Aerial Vehicles](https://doi.org/10.1109/icra55743.2025.11128496)
- [Structure-Aware Radar-Camera Depth Estimation](https://doi.org/10.1109/icra55743.2025.11128760)
- [Talk2Radar: Bridging Natural Language with 4D mmWave Radar for 3D Referring Expression Comprehension](https://doi.org/10.1109/icra55743.2025.11128399)
- [TDFANet: Encoding Sequential 4D Radar Point Clouds Using Trajectory-Guided Deformable Feature Aggregation for Place Recognition](https://doi.org/10.1109/icra55743.2025.11127648)
- [UniBEVFusion: Unified Radar-Vision Bevfusion for 3D Object Detection](https://doi.org/10.1109/icra55743.2025.11128067)
- [Unleashing HyDRa: Hybrid Fusion, Depth Consistency and Radar for Unified 3D Perception](https://doi.org/10.1109/icra55743.2025.11127412)


### 2026 (14)

- [4D Radar Diffusion with Adaptive Visual-Aided Condition for Point Cloud Enhancement](https://doi.org/10.1109/icra57385.2026.11696452)
- [4DRaL: Bridging 4D Radar with LiDAR for Place Recognition using Knowledge Distillation](https://doi.org/10.1109/icra57385.2026.11696222)
- [CFEAR-Teach-and-Repeat: Fast and Accurate Radar-only Localization](https://doi.org/10.1109/icra57385.2026.11697231)
- [Dr-PoGO: Direct Radar Pose-Graph Optimization](https://doi.org/10.1109/icra57385.2026.11696879)
- [Fully Polar Coordinate Object Detection: A Constraint-Based Polar Bounding Box Approach for LiDAR and Scanning Radar](https://doi.org/10.1109/icra57385.2026.11696654)
- [How IMU Drift Influences Multi-Radar Inertial Odometry for Ground Robots in Subterranean Terrains](https://doi.org/10.1109/icra57385.2026.11695852)
- [MotionNet-PGA: MotionNet with Polar-Guided Attention for Moving Object Segmentation in Scanning Radar](https://doi.org/10.1109/icra57385.2026.11696301)
- [MSDNet: Efficient 4D Radar Super-Resolution via Multi-Stage Distillation](https://doi.org/10.1109/icra57385.2026.11697541)
- [Omnidirectional Solid-State mmWave Radar Perception for UAV Power Line Collision Avoidance](https://doi.org/10.1109/icra57385.2026.11696714)
- [RaCo-SLAM: A Physics-Informed 4D Radar SLAM with Co-visibility Consistency Factor](https://doi.org/10.1109/icra57385.2026.11697519)
- [RadarSFD: Single-Frame Diffusion with Pretrained Priors for Radar Point Clouds](https://doi.org/10.1109/icra57385.2026.11695739)
- [SpaRC: Sparse Radar-Camera Fusion for 3D Object Detection](https://doi.org/10.1109/icra57385.2026.11696130)
- [SRCF-UAV: Sparse Radar-Camera Fusion for 3D UAV Detection](https://doi.org/10.1109/icra57385.2026.11696672)
- [View Synthesis and 6DoF Pose Estimation in mmWave Radar Neural Radiance Fields](https://doi.org/10.1109/icra57385.2026.11696279)


## IROS

_CCF-B robotics venue, added by request._


### 2024 (18)

- [Adaptive Visual-Aided 4D Radar Odometry Through Transformer-Based Feature Fusion](https://doi.org/10.1109/iros58592.2024.10802367)
- [Advancements in Radar Odometry](https://doi.org/10.1109/iros58592.2024.10802141)
- [AnytimeFusion: Parameter-free RGB Camera-Radar Sensor Fusion Algorithm in Complex Maritime Situations](https://doi.org/10.1109/iros58592.2024.10801864)
- [ASY-VRNet: Waterway Panoptic Driving Perception Model based on Asymmetric Fair Fusion of Vision and 4D mmWave Radar](https://doi.org/10.1109/iros58592.2024.10802447)
- [Augmenting Vision with Radar for All-weather Geo-localization without a Prior HD Map](https://doi.org/10.1109/iros58592.2024.10802744)
- [Automatic Spatial Calibration of Near-Field MIMO Radar With Respect to Optical Depth Sensors](https://doi.org/10.1109/iros58592.2024.10801705)
- [Autonomous Power Line Tracking with mmWave Radar](https://doi.org/10.1109/iros58592.2024.10802812)
- [BEVCar: Camera-Radar Fusion for BEV Map and Object Segmentation](https://doi.org/10.1109/iros58592.2024.10802147)
- [Co-RaL: Complementary Radar-Leg Odometry with 4-DoF Optimization and Rolling Contact](https://doi.org/10.1109/iros58592.2024.10801960)
- [CR3DT: Camera-RADAR Fusion for 3D Detection and Tracking](https://doi.org/10.1109/iros58592.2024.10801848)
- [CRPlace: Camera-Radar Fusion with BEV Representation for Place Recognition](https://doi.org/10.1109/iros58592.2024.10802267)
- [DeRO: Dead Reckoning Based on Radar Odometry With Accelerometers Aided for Robot Localization](https://doi.org/10.1109/iros58592.2024.10801645)
- ★ [NeRF-enabled Analysis-Through-Synthesis for ISAR Imaging of Small Everyday Objects with Sparse and Noisy UWB Radar Data](https://doi.org/10.1109/iros58592.2024.10801921)
- [RaNDT SLAM: Radar SLAM Based on Intensity-Augmented Normal Distributions Transform](https://doi.org/10.1109/iros58592.2024.10802458)
- [RMap: Millimeter-Wave Radar Mapping Through Volumetric Upsampling](https://doi.org/10.1109/iros58592.2024.10801827)
- [Road Boundary Estimation Using Sparse Automotive Radar Inputs](https://doi.org/10.1109/iros58592.2024.10802490)
- [Roofus: Learning-based Robotic Moisture Mapping on Flat Rooftops with Ground Penetrating Radar](https://doi.org/10.1109/iros58592.2024.10802148)
- [Tightly-Coupled Factor Graph Formulation For Radar-Inertial Odometry](https://doi.org/10.1109/iros58592.2024.10801945)


### 2025 (18)

- [Class-Aware PillarMix: Can Mixed Sample Data Augmentation Enhance 3D Object Detection with Radar Point Clouds?](https://doi.org/10.1109/iros60139.2025.11246852)
- [CORENet: Cross-Modal 4D Radar Denoising Network with LiDAR Supervision for Autonomous Driving](https://doi.org/10.1109/iros60139.2025.11246433)
- [Design and Development of a GPR-Equipped Robot for Full-space External Diseases Detection in Drainage Pipelines](https://doi.org/10.1109/iros60139.2025.11246503)
- [ELMAR: Enhancing LiDAR Detection with 4D Radar Motion Awareness and Cross-modal Uncertainty](https://doi.org/10.1109/iros60139.2025.11246399)
- [Impact of Temporal Delay on Radar-Inertial Odometry](https://doi.org/10.1109/iros60139.2025.11246946)
- [Indoor FireRescue Radar: 4D Indoor Millimeter Wave Dataset and Analysis for Hazardous Environment Perception](https://doi.org/10.1109/iros60139.2025.11246924)
- [Learning Point Correspondences In Radar 3D Point Clouds For Radar-Inertial Odometry](https://doi.org/10.1109/iros60139.2025.11246451)
- [LGDD: Local-Global Synergistic Dual-Branch 3D Object Detection Using 4D Radar](https://doi.org/10.1109/iros60139.2025.11246504)
- [mmWave Radar-Based Non-Line-of-Sight Pedestrian Localization at T-Junctions Utilizing Road Layout Extraction via Camera](https://doi.org/10.1109/iros60139.2025.11246461)
- [NanoMVG: USV-Centric Low-Power Multi-Task Visual Grounding based on Prompt-Guided Camera and 4D mmWave Radar](https://doi.org/10.1109/iros60139.2025.11246532)
- [R2LDM: An Efficient 4D Radar Super-Resolution Framework Leveraging Diffusion Model](https://doi.org/10.1109/iros60139.2025.11246739)
- [RaGNNarok: A Light-Weight Graph Neural Network for Enhancing Radar Point Clouds on Unmanned Ground Vehicles](https://doi.org/10.1109/iros60139.2025.11245944)
- [RDN: An Efficient Denoising Network for 4D Radar Point Clouds](https://doi.org/10.1109/iros60139.2025.11246274)
- [REOcc: Camera-Radar Fusion with Radar Feature Enrichment for 3D Occupancy Prediction](https://doi.org/10.1109/iros60139.2025.11246246)
- [RoCaRS: Robust Camera-Radar BEV Segmentation for Sensor Failure Scenarios](https://doi.org/10.1109/iros60139.2025.11246952)
- [Simulating Automotive Radar with Lidar and Camera Inputs](https://doi.org/10.1109/iros60139.2025.11247276)
- [VISC: mmWave Radar Scene Flow Estimation using Pervasive Visual-Inertial Supervision](https://doi.org/10.1109/iros60139.2025.11246830)
- [VoxEKF-RIO: A 4D Radar Inertial Odometry Based on Incremental Voxel Map and Iterated Kalman Filter](https://doi.org/10.1109/iros60139.2025.11247427)


---

## Notes

- Snapshot: 2026-11-06.
- CVPR / ICCV / ECCV / NeurIPS / ICML: full title scan (37,560 titles).
- AAAI: full Crossref harvest by ISSN (11,273 records). ACM MM: Crossref proceedings 2024–2026.
- ICRA 2024–2026 / IROS 2024–2025: full proceedings harvest via Crossref (7,939 papers).
- ECCV 2026 not yet indexed by ECVA; IJCAI excluded by scope; ICLR is not a CCF-A venue.
- "MIMO-SAR = 0" refers to these venues only. The topic lives in IEEE TGRS/TAES/TSP and at IGARSS/EUSAR.

## Contributing

Open a PR adding one line under the right venue and year: `- [Title](url)` with `★` if it is a SAR paper.

## License

[CC BY 4.0](LICENSE).
