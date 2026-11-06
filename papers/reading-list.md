# 推荐阅读清单（2024–2026）

按五个研究方向组织。每篇给一句“读它解决什么问题”，以及“读的时候看什么”。

> 只读五篇的话：**SOMA → DenoDet V2 → DART → RC-AutoCalib → MM-OVSeg**。

---

## 总表

| 方向 | 2024+ 现状 | 推荐阅读（按顺序） | 读它解决什么问题 |
|---|---|---|---|
| **D1 成像前误差** | 1 篇（且是雷达-相机外参） | RC-AutoCalib (CVPR25) → SOMA (AAAI26) | 标定/配准：两套坐标怎么对齐 |
| **D2 快速重建** | 5 篇（神经场/渲染） | DART (CVPR24) → Rascene (CVPR26) → GeRaF 2.0 (CVPR26) → RF4D (CVPR26) | 可微前向算子与稀疏重建 |
| **D3 质量改善** | 3 篇间接 | DenoDet V2 (AAAI26) → SARMAE (CVPR26) → Ph-GAN (ICCV25) | 去噪、相位保真、物理约束 |
| **D4 减少计算量** | 3 篇 | SparseRadNet (ECCV24) → AdaRadar (CVPR26) → RAVEN (CVPR26) | 采样、压缩、早退 |
| **D5 相机辅助雷达** | 6 篇（语义/检测级） | MM-OVSeg (CVPR26) → CARB-Net (ECCV24) → Sparse Beats Dense (ECCV24) → CRT-Fusion (NeurIPS24) | 跨模态融合的四种层级 |

---

## D1 成像前误差

**1. RC-AutoCalib: An End-to-End Radar-Camera Automatic Calibration Network** — CVPR 2025
[链接](https://openaccess.thecvf.com/content/CVPR2025/html/Luu_RC-AutoCalib_An_End-to-End_Radar-Camera_Automatic_Calibration_Network_CVPR_2025_paper.html)
读它：在线外参标定怎么做成网络，而不依赖标定物。
看什么：双视角（前视 + BEV）表示如何消解雷达高度不确定性；跨模态注意力如何找对应点。这两点和你的 CCS↔ACS 是同一结构。

**2. SOMA: Feature Gradient Enhanced Affine-Flow Matching for SAR-Optical Registration** — AAAI 2026
[链接](https://ojs.aaai.org/index.php/AAAI/article/view/37939)
读它：两种成像机理完全不同的传感器，如何做**稠密**逐像素配准。
看什么：梯度先验怎么嵌进深度特征；混合匹配策略怎么在弱纹理区保稳。可迁移点：把“图像梯度”换成“距离–角度热图的相位梯度”。

---

## D2 快速重建

**3. DART: Implicit Doppler Tomography for Radar Novel View Synthesis** — CVPR 2024
[链接](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_DART_Implicit_Doppler_Tomography_for_Radar_Novel_View_Synthesis_CVPR_2024_paper.html)
读它：把雷达成像写成**可微渲染**的模板。
看什么：反射率/透射率如何映射到 range-Doppler；这是把 BP/ωk 写成网络层的参照物。

**4. Rascene: High-Fidelity 3D Scene Imaging with mmWave Communication Signals** — CVPR 2026
[链接](https://openaccess.thecvf.com/content/CVPR2026/html/Song_Rascene_High-Fidelity_3D_Scene_Imaging_with_mmWave_Communication_Signals_CVPR_2026_paper.html)
读它：稀疏、多径、少帧条件下如何恢复几何一致性。
看什么：多帧空间自适应融合 + 置信度加权前向投影。和 MIMO-SAR 的稀疏采样同构。

**5. Seeing through boxes: Non-Line-of-Sight 3D Reconstruction from Radar Signals (GeRaF 2.0)** — CVPR 2026
[链接](https://openaccess.thecvf.com/content/CVPR2026/html/Lu_Seeing_through_boxes_Non-Line-of-Sight_3D_Reconstruction_from_Radar_Signals_CVPR_2026_paper.html)
读它：全场唯一“用视觉/几何先验约束雷达成像”的工作。
看什么：LoS 几何如何作为先验进入神经场；这是你切口 1（相机辅助成像）最近的邻居。

**6. RF4D: Neural Radar Fields for Novel View Synthesis in Outdoor Dynamic Scenes** — CVPR 2026
[链接](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_RF4DNeural_Radar_Fields_for_Novel_View_Synthesis_in_Outdoor_Dynamic_CVPR_2026_paper.html)
读它：动态场景下的雷达时序建模。
看什么：场景流模块与雷达功率渲染公式；对应“运动目标 SAR”。

---

## D3 质量改善

**7. DenoDet V2: Phase-Amplitude Cross Denoising for SAR Object Detection** — AAAI 2026
[链接](https://ojs.aaai.org/index.php/AAAI/article/view/37761)
读它：目前 CCF-A 里唯一把**相位**当一等公民的 SAR 去噪。
看什么：幅度谱与相位谱如何互相调制；这套“幅相联合”能不能搬到重建损失里。

**8. SARMAE: Masked Autoencoder for SAR Representation Learning** — CVPR 2026
[链接](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_SARMAE_Masked_Autoencoder_for_SAR_Representation_Learning_CVPR_2026_paper.html)
读它：散斑物理如何写进预训练目标。
看什么：噪声注入方式 + 光学语义锚点对齐。

**9. Ph-GAN: Physics-Inspired GAN for Generating SAR Images Under Limited Data** — ICCV 2025
[链接](https://openaccess.thecvf.com/content/ICCV2025/html/Zhang_Ph-GAN_Physics-Inspired_GAN_for_Generating_SAR_Images_Under_Limited_Data_ICCV_2025_paper.html)
读它：电磁散射模型（PSC）如何变成可微损失。
看什么：两个物理一致性损失分别约束生成器与判别器的哪一部分。

---

## D4 减少计算量

**10. SparseRadNet: Sparse Perception Neural Network on Subsampled Radar Data** — ECCV 2024
[链接](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/11537_ECCV_2024_paper.php)
读它：把“选哪些点”变成可学习模块。
看什么：RD 谱上的自适应子采样 + 双分支 GNN。对应你的“监测点筛选”。

**11. AdaRadar: Rate Adaptive Spectral Compression for Radar-based Perception** — CVPR 2026
[链接](https://openaccess.thecvf.com/content/CVPR2026/html/Park_AdaRadar_Rate_Adaptive_Spectral_Compression_for_Radar-based_Perception_CVPR_2026_paper.html)
读它：原始雷达数据堵塞带宽时怎么办。
看什么：DCT + 剪枝 + 量化，以及用检测置信度反推压缩率的反馈环。

**12. RAVEN: Radar Adaptive Vision Encoders for Efficient Chirp-wise Object Detection** — CVPR 2026
[链接](https://openaccess.thecvf.com/content/CVPR2026/html/Sen_RAVEN_Radar_Adaptive_Vision_Encoders_for_Efficient_Chirp-wise_Object_Detection_CVPR_2026_paper.html)
读它：chirp 级早退能省多少算力（论文报 170×）。
看什么：早退的置信度规则怎么定，才不会漏检。

---

## D5 相机辅助雷达

**13. MM-OVSeg: Multimodal Optical-SAR Fusion for Open-Vocabulary Segmentation** — CVPR 2026
[链接](https://openaccess.thecvf.com/content/CVPR2026/html/Wei_MM-OVSeg_Multimodal_Optical-SAR_Fusion_for_Open-Vocabulary_Segmentation_in_Remote_Sensing_CVPR_2026_paper.html)
读它：目前最完整的 optical–SAR 融合框架。
看什么：双编码器如何对齐两种模态特征；但注意它停在语义层，不碰几何。

**14. CARB-Net: Camera-Assisted Radar-Based Network for Vulnerable Road User Detection** — ECCV 2024
[链接](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/8101_ECCV_2024_paper.html)
读它：“相机补雷达角分辨率”的教科书式做法。
看什么：地平面前馈阵列如何把相机检测注入雷达早期层；雷达多普勒缺失时的退化机制。

**15. Sparse Beats Dense: Rethinking Supervision in Radar-Camera Depth Completion** — ECCV 2024
[链接](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/6528_ECCV_2024_paper.html)
读它：稀疏监督为什么反而更好。
看什么：LiDAR 分布泄漏（LDL）现象与 Disruption-Compensation 框架。

**16. CRT-Fusion: Camera, Radar, Temporal Fusion Using Motion Information for 3D Object Detection** — NeurIPS 2024
[链接](https://proceedings.neurips.cc/paper_files/paper/2024/hash/c49a28241640407b23bba8f2495f4bc9-Abstract-Conference.html)
读它：时序与运动信息如何补几何。
看什么：运动信息进入 BEV 融合的位置；对你的“静态图像 + 连续雷达帧”是个提醒。

---

## 建议的阅读顺序

1. **先建立问题感**：RC-AutoCalib（标定）→ SOMA（跨模态几何）——这两篇定义了你切口 2 的可行性边界。
2. **再看重建**：DART（可微前向）→ Rascene（稀疏融合）→ GeRaF 2.0（视觉先验）。
3. **然后看质量**：DenoDet V2（相位）→ SARMAE（散斑）。
4. **最后看效率与融合**：SparseRadNet → MM-OVSeg / CARB-Net。

按这个顺序，每篇都能挂在前一篇的钩子上；跳过第 1 步直接读 DART，会觉得“渲染很酷但和我无关”。
