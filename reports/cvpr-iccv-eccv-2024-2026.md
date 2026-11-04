# MIMO-SAR 与相机融合：CVPR / ICCV / ECCV 2024–2026 检索报告

**检索日期** 2026-11-04
**覆盖** CVPR 2024、CVPR 2025、CVPR 2026、ICCV 2025、ECCV 2024（主会）
**语料** 14,717 篇论文标题全量扫描；62 篇雷达/SAR 相关论文；79 篇摘要逐篇核验；21 篇取官方 BibTeX

---

## 一、结论先行

1. **MIMO-SAR：0 篇。** 五届主会、14,717 篇论文中，标题同时出现 MIMO 与 SAR 的论文为零。
2. **MIMO-SAR + 相机：0 篇。** 连 MIMO-SAR 本身都没有，融合更无从谈起。
3. **SAR 在三大会是"语义问题"，不是"成像问题"。** 9 篇 SAR 论文全部做检测、分割、ReID、配准、生成，**没有一篇**处理聚焦、自聚焦、阵列幅相误差、运动补偿。
4. **最接近的是三条线**：SAR–光学语义融合（4 篇）、雷达–相机几何/深度（多篇）、雷达神经重建（5 篇）。它们分别落在你五个方向里的 D5、D1、D2。
5. **这不是疏漏，是学科分工。** MIMO-SAR 的成像算法在 TGRS / TAES / TSP / IGARSS / EUSAR；CV 社区只"消费"SAR 图像，不"生产"SAR 图像。

---

## 二、检索口径（可复现）

| 会议 | 年份 | 标题数 | radar/SAR 命中 | SAR 专项 | MIMO-SAR |
|---|---|---:|---:|---:|---:|
| CVPR | 2024 | 2,716 | 9 | 1 | 0 |
| CVPR | 2025 | 2,871 | 8 | 2 | 0 |
| CVPR | 2026 | 4,042 | 23 | 4 | 0 |
| ICCV | 2025 | 2,701 | 11 | 2 | 0 |
| ECCV | 2024 | 2,387 | 11 | 0 | 0 |
| **合计** | | **14,717** | **62** | **9** | **0** |

**流程**

1. 抓取 CVF Open Access 与 ECVA 的全量论文列表（新年份走 `?day=all`，2018–2020 走 `{CONF}.py?day=`）；
2. 标题正则命中：`MIMO`、`SAR`、`synthetic aperture`、`radar`、`mmWave`、`FMCW`、`aperture`、`array imaging`、`beamforming`；
3. 对 79 篇逐篇抓取摘要核验，剔除误命中（如 `SAR-Net` 是 6D 位姿，不是合成孔径雷达）；
4. 对入选论文抓取 CVF 官方 BibTeX（含页码），ECCV 条目用 Crossref DOI 补齐。

**限制（写在明处）**

- ECCV 2026 尚未进入 ECVA 索引（截稿日 2026-11-04），未覆盖；
- 标题级召回可能漏掉"题名不含关键词"的论文（例如把 SAR 称作 "RF imaging"）；
- CVPRW / ICCVW 的 workshop 不计入主会——但 SAR↔光学翻译的主要 benchmark（PBVS MAVIC-T）恰在 workshop，见第六节；
- 本文所有"论文做了什么"均来自摘要原文；凡属我的推断，标注为"（推断）"。

---

## 三、9 篇 SAR 论文：全部是语义，没有一篇是成像

| 会议 | 标题 | 任务 | 涉及光学 | 涉及成像 |
|---|---|---|---|---|
| CVPR 2024 | [Unleashing Channel Potential: Space-Frequency Selection Convolution for SAR Object Detection](https://openaccess.thecvf.com/content/CVPR2024/html/Li_Unleashing_Channel_Potential_Space-Frequency_Selection_Convolution_for_SAR_Object_Detection_CVPR_2024_paper.html) | 检测骨干 | 否 | 否 |
| CVPR 2025 | [RSAR: Restricted State Angle Resolver and Rotated SAR Benchmark](https://openaccess.thecvf.com/content/CVPR2025/html/Zhang_RSAR_Restricted_State_Angle_Resolver_and_Rotated_SAR_Benchmark_CVPR_2025_paper.html) | 旋转框检测 + 数据集 | 是（对标光学 DOTA） | 否 |
| CVPR 2025 | [Cross-Rejective Open-Set SAR Image Registration](https://openaccess.thecvf.com/content/CVPR2025/html/Mao_Cross-Rejective_Open-Set_SAR_Image_Registration_CVPR_2025_paper.html) | 图像配准 | 否 | 否 |
| CVPR 2026 | [SARMAE: Masked Autoencoder for SAR Representation Learning](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_SARMAE_Masked_Autoencoder_for_SAR_Representation_Learning_CVPR_2026_paper.html) | 自监督预训练 | 是（光学先验对齐） | 否 |
| CVPR 2026 | [MM-OVSeg: Multimodal Optical-SAR Fusion for Open-Vocabulary Segmentation](https://openaccess.thecvf.com/content/CVPR2026/html/Wei_MM-OVSeg_Multimodal_Optical-SAR_Fusion_for_Open-Vocabulary_Segmentation_in_Remote_Sensing_CVPR_2026_paper.html) | 开放词表分割 | **是（融合）** | 否 |
| CVPR 2026 | [MOS: Mitigating Optical-SAR Modality Gap for Cross-Modal Ship Re-Identification](https://openaccess.thecvf.com/content/CVPR2026/html/Zhao_MOS_Mitigating_Optical-SAR_Modality_Gap_for_Cross-Modal_Ship_Re-Identification_CVPR_2026_paper.html) | 跨模态 ReID | **是（融合）** | 否 |
| CVPR 2026 | [FUSAR-GPT: A Spatiotemporal Feature-Embedded and Two-Stage Decoupled VLM for SAR Imagery](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_FUSAR-GPT_A_Spatiotemporal_Feature-Embedded_and_Two-Stage_Decoupled_Visual_Language_Model_CVPR_2026_paper.html) | 视觉语言模型 | 否 | 否 |
| ICCV 2025 | [Ph-GAN: Physics-Inspired GAN for Generating SAR Images Under Limited Data](https://openaccess.thecvf.com/content/ICCV2025/html/Zhang_Ph-GAN_Physics-Inspired_GAN_for_Generating_SAR_Images_Under_Limited_Data_ICCV_2025_paper.html) | 物理先验生成 | 否 | 否 |
| ICCV 2025 | [Cross-modal Ship Re-Identification via Optical and SAR Imagery](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_Cross-modal_Ship_Re-Identification_via_Optical_and_SAR_Imagery_A_Novel_ICCV_2025_paper.html) | 数据集 + ReID | **是（融合）** | 否 |

**读法**：唯一涉及"光学 + SAR"实质融合的是 MM-OVSeg、MOS、Ship ReID（以及 SARMAE 的光学先验对齐）。它们融合的是**语义特征**，不是**几何/相位**；融合发生在编码器里，不发生在成像算子里。

---

## 四、五个方向的最近邻

| 方向 | 2024+ 三大会有没有 | 最接近的工作 | 真正的缺口 |
|---|---|---|---|
| **D1 成像前误差处理** | **1 篇**（且是雷达-相机外参，不是 SAR 阵列校准） | RC-AutoCalib (CVPR 2025) | 通道幅相校准、阵列误差、运动误差补偿、自聚焦——**全空白** |
| **D2 成像中快速重建** | **5 篇**（神经场/渲染，非 SAR 聚焦） | DART (CVPR 2024)、RF4D、Rascene、X-band NLOS、GeRaF 2.0 (CVPR 2026) | 深度展开 / 物理约束网络做 MIMO-SAR 聚焦——**空白** |
| **D3 成像后质量改善** | **3 篇间接** | SARMAE、Ph-GAN、MOS 的去噪模块 | 专门去斑、旁瓣抑制、相位保真超分——**空白** |
| **D4 减少整体处理量** | **3 篇** | AdaRadar、RAVEN (CVPR 2026)、SparseRadNet (ECCV 2024) | MIMO-SAR 数据立方体的采样-重建联合优化——**空白** |
| **D5 相机辅助雷达** | **6 篇**（语义级 / 检测级） | MM-OVSeg、MOS、RC-AutoCalib、CARB-Net、Sparse Beats Dense | 用相机辅助 SAR **成像**（运动补偿、高程约束、自聚焦）——**空白** |

---

## 五、十二篇值得读的（按方向）

### D2 成像中快速重建

**1. DART: Implicit Doppler Tomography for Radar Novel View Synthesis** — CVPR 2024，Huang et al.
用 NeRF 式的可微渲染，把"反射率 + 透射率"映射到距离-多普勒图像，并用 LiDAR 定位构建了新数据集。**价值**：它给出了一个可微的雷达前向算子——这正是把 SAR 成像放进学习框架所需要的那块拼图。**局限**：场景级重建，不是条带/聚束 SAR 几何。

**2. RF4D: Neural Radar Fields for Novel View Synthesis in Outdoor Dynamic Scenes** — CVPR 2026，Zhang et al.
在神经场里加入时序与场景流，提出雷达功率渲染公式。**价值**：动态场景下的雷达时序建模，可类比到"运动目标 SAR"。**局限**：仍是前视雷达，不是合成孔径。

**3. Rascene: High-Fidelity 3D Scene Imaging with mmWave Communication Signals** — CVPR 2026，Song et al.
用 mmWave OFDM 通信信号做 ISAC 三维成像，多帧空间自适应融合 + 置信度加权前向投影。**价值**："稀疏、多径、少帧"条件下恢复几何一致性，和 MIMO-SAR 的稀疏采样问题同构。**局限**：通信波形，非调频连续波。

**4. X-band Radar Non-Line-of-Sight Imaging** — CVPR 2026，Du et al.
利用长波长把漫反射变成镜面反射，学习式稠密预测 + 几何感知 NLOS 重建，实测 40 m。**价值**：低频雷达 + 低分辨率 + 学习先验的组合，方法论可直接迁移。**局限**：NLOS 场景，不是对地观测。

**5. Seeing through boxes: Non-Line-of-Sight 3D Reconstruction from Radar Signals (GeRaF 2.0)** — CVPR 2026，Lu et al.
把 LoS 几何作为先验，约束 RF 从可见区到遮挡区的传播，稳定 SDF 重建。**价值**：这是全场**唯一**"用视觉/几何先验去约束雷达成像"的工作，最接近你说的"相机辅助雷达"。

### D5 相机辅助雷达

**6. MM-OVSeg: Multimodal Optical-SAR Fusion for Open-Vocabulary Segmentation** — CVPR 2026，Wei et al.
跨模态统一 + 双编码器融合，光学给光谱语义、SAR 给穿云结构，做恶劣天气下的开放词表分割。**价值**：目前最完整的 optical-SAR 融合框架。**局限**：语义分割，不涉及成像几何，也不涉及相位。

**7. RC-AutoCalib: An End-to-End Radar-Camera Automatic Calibration Network** — CVPR 2025，Luu et al.
首个在线雷达-相机几何自动标定：双视角（前视 + BEV）表示、选择性融合、跨模态注意力匹配、抗噪匹配器。**价值**：与 MVC 的"链 B"（CCS↔ACS 标定）是同一个数学问题，只是它在线、可学习、面向车载。**局限**：nuScenes 车载场景，未涉及距离-角度热图的 bin 量化。

**8. CARB-Net: Camera-Assisted Radar-Based Network for Vulnerable Road User Detection** — ECCV 2024，Lee et al.
用地平面前馈阵列把相机检测结果注入雷达网络的早期层，并设计退化机制应对雷达多普勒缺失/相机遮挡。**价值**："相机补雷达角分辨率"的教科书式做法，和你的动机（1.33° → 相机 0.03°）完全一致。**局限**：检测级，不是成像级。

### D4 减少整体处理量

**9. SparseRadNet: Sparse Perception Neural Network on Subsampled Radar Data** — ECCV 2024，Wu et al.
自适应地从距离-多普勒谱中挑选"对下游任务贡献最大"的像素，再用双分支 GNN 提取全局/局部特征。**价值**：这就是"监测点筛选 / 按需更新"的同类思想——把"选哪些点"变成可学习模块。**局限**：面向检测，不是成像。

**10. AdaRadar / RAVEN** — CVPR 2026
AdaRadar 用 DCT + 剪枝 + 量化做率自适应压缩，解决原始雷达数据堵塞带宽的问题；RAVEN 用天线混合器压缩虚拟 MIMO 阵列，并做 chirp 级早退，计算量降 170×。**价值**：MIMO-SAR 的数据立方体比车载雷达大一到两个数量级，这两个思路（压缩 + 早退）几乎是必需的前置设计。

### D3 成像后质量改善

**11. SARMAE: Masked Autoencoder for SAR Representation Learning** — CVPR 2026，Liu et al.
构建百万级 SAR-光学配对数据集 SAR-1M，把散斑噪声注入 MAE 做噪声感知预训练，再用光学语义锚点对齐特征。**价值**：目前唯一把"散斑物理"写进预训练目标的工作。**局限**：表征学习，不是图像复原。

**12. Ph-GAN: Physics-Inspired GAN for Generating SAR Images Under Limited Data** — ICCV 2025，Zhang et al.
把理想点散射中心（PSC）模型嵌入 GAN，用两个物理一致性损失约束生成器与判别器。**价值**：小样本下保持电磁散射特性——数据增广的可用手段。

---

## 六、为什么是 0：一个结构性解释

- **CV 社区把 SAR 当"图像"**：输入是已经聚焦好的幅度图，任务是检测/分割/配准。成像链路（脉冲压缩、聚焦、自聚焦、运动补偿）被整体当成黑盒。
- **SAR 社区把 CV 当"下游工具"**：MIMO-SAR 的论文发在 TGRS/TAES/TSP/IGARSS/EUSAR，评价指标是分辨率、PSLR、相位误差，不是 mAP。
- **两边的评价体系不重叠**：CV 论文不报相位保真度，SAR 论文不报语义指标。这就是为什么"相机辅助 SAR 成像"这个交叉点至今空着——**不是没人有能力，是没人有动机**。

> 一个旁证：SAR↔光学的**翻译** benchmark（MAVIC-T）办在 CVPRW 的 PBVS workshop，连主会都没进。说明这个方向在 CV 社区仍被视为"应用/竞赛"，而非"方法"。

---

## 七、四个可以做的切口（按可行性排序）

1. **视觉先验约束的 MIMO-SAR 自聚焦**（D1 × D5）
   用相机给出的场景深度/光流约束平台运动误差，把自聚焦从"盲估计"变成"半监督"。目前无人做；难点是相机与 SAR 的时间同步与尺度对齐。

2. **MIMO-SAR 与相机的手眼标定**（D5）
   把 RC-AutoCalib 的在线标定思路搬到"距离-角度热图 ↔ 像素"的映射上，解决 MVC 这类系统"标一次、碰一下就废"的问题。

3. **相位保真的可微 SAR 重建**（D2 × D3）
   现有 CV 雷达重建（DART/RF4D/Rascene）全是幅度/功率域，没有人把相位写进损失。而 SAR 的干涉/形变应用恰恰只吃相位。这是最容易做出差异化的点。

4. **稀疏 MIMO 阵列的采样-重建联合优化**（D4 × D2）
   把 SparseRadNet 的"选点"与展开网络的重建联合训练，目标函数直接写成"给定采样预算下的相位误差"。

---

## 八、去哪儿补 MIMO-SAR 的真文献

三大会没有，不等于文献没有。建议换库：

- **期刊**：IEEE TGRS、IEEE TAES、IEEE TSP、IEEE TIM、IEEE JSTARS
- **会议**：IGARSS、EUSAR、IET Radar Conference、IEEE Radar Conference
- **检索词**：`MIMO-SAR`、`sparse MIMO array`、`SAR autofocus`、`motion compensation`、`phase error`、`back-projection`、`omega-k`、`deep unfolding SAR`

（本节只给检索路径，不列具体文献，避免未核实的引用。）

---

## 九、附件

- `MIMO-SAR_CVPR2024-2026.bib`：21 条，含 CVF 官方 BibTeX 与 ECCV 的 Crossref DOI/页码
- `MIMO-SAR_2024-2026_matrix.xlsx`：五方向 × 21 篇的覆盖矩阵（● 直接 / ◐ 可借鉴）

**引用前请复核页码**：CVPR 2026 的页码来自官方 BibTeX，正式投稿前建议再对一遍 IEEE Xplore。
