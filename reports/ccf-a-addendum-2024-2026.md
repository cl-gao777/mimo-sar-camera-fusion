# 扩展检索：CCF-A AI 会议 2024–2026（MIMO-SAR / 雷达–相机）

**检索日期** 2026-11-04 ｜ **承接**《MIMO-SAR 与相机融合：CVPR/ICCV/ECCV 2024–2026 检索报告》
**本轮新增** AAAI 2024–2026、NeurIPS 2024/2025、ICML 2024/2025、ACM MM 2024/2025、ACL 2024/2025
**按要求剔除** IJCAI

---

## 〇、先修正一个口径问题

严格按 CCF-A（2022 目录）的 AI 会议是：**AAAI、NeurIPS、ICML、CVPR、ICCV、ACM MM、ACL**（IJCAI 已剔除）。

两个需要说明的边界：

- **ECCV 是 CCF-B，不是 CCF-A。** 上一轮按你“CV 三大会”的说法保留了它；本轮统计里单独标注，不计入 CCF-A 合计。
- **ICLR 不在 CCF 目录里**（既不是 A 也不是 B），属于“事实顶会、非 CCF-A”。本轮未纳入；如需纳入，我可以单独补一轮 OpenReview 检索。

---

## 一、总表

| 会议 | 年份 | 扫描量 | radar/SAR 命中 | SAR 专项 | MIMO-SAR |
|---|---|---:|---:|---:|---:|
| CVPR | 2024 | 2,716 | 9 | 1 | 0 |
| CVPR | 2025 | 2,871 | 8 | 2 | 0 |
| CVPR | 2026 | 4,042 | 23 | 4 | 0 |
| ICCV | 2025 | 2,701 | 11 | 2 | 0 |
| ECCV（B 类） | 2024 | 2,387 | 11 | 0 | 0 |
| **NeurIPS** | 2024 | 4,493 | 7 | 2 | 0 |
| **NeurIPS** | 2025 | 5,858 | 5 | 0 | 0 |
| **ICML** | 2024 | 2,610 | 0 | 0 | 0 |
| **ICML** | 2025 | 3,330 | 1 | 1 | 0 |
| **AAAI** | 2024–26 | 检索式 | 26 | 6 | 0 |
| **ACM MM** | 2024–25 | 检索式 | 6 | 1 | 0 |
| **ACL** | 2024–25 | 检索式 | 0 | 0 | 0 |
| **合计** | | **31,008（全量）+ 3 个检索式会场** | **107** | **19** | **0** |

**一句话：把范围从 5 个会场扩到 12 个会场、扫描量翻倍到 3 万篇，MIMO-SAR 仍然是 0。**

---

## 二、逐会场的新发现

### AAAI：SAR 最密集的 CCF-A 会场（6 篇）

AAAI 是这轮最大的意外——SAR 论文数量（6 篇）仅次于 CVPR（7 篇），而且**第一次出现了“SAR–光学几何”工作**。

| 论文 | 年份 | 做了什么 | 与你的关系 |
|---|---|---|---|
| **SOMA: Feature Gradient Enhanced Affine-Flow Matching for SAR-Optical Registration** | 2026 | 把多尺度多方向**梯度先验**嵌进深度特征，用混合匹配做 SAR–光学**稠密配准** | **最接近“相机辅助 SAR”的几何工作**：它解决的是“两张不同模态的图怎么逐像素对上”，和你的 CCS↔ACS 是同一类问题 |
| **HiFC-GAN: Hierarchical Feature-Constrained GAN for Optical-to-SAR Transfer** | 2026 | 光学→SAR 风格迁移，分层约束高层语义与低层散射纹理 | 数据增广；说明“跨模态生成”在 AAAI 有位置 |
| **DenoDet V2: Phase-Amplitude Cross Denoising for SAR Object Detection** | 2026 | 在变换域做**幅度–相位联合调制**，用相位谱反哺幅度谱 | **目前 CCF-A 里唯一“相位感知”的 SAR 去噪**，直接支撑你的切口 3 |
| **SAR-DisentDM** | 2026 | 语义解耦扩散，小样本 SAR 生成 | 数据侧 |
| **Dual Information Purification for Lightweight SAR Object Detection** | 2025 | 轻量 SAR 检测的双重信息净化 | 下游 |
| **Statistically Principled Deep Learning for SAR Image Segmentation** | 2024 | 统计先验的 SAR 分割（学生摘要，2 页） | 下游，权重低 |

雷达–相机方向，AAAI 也有两篇强工作：**RCTrans**（雷达稠密化 + 序列解码，2025）与 **HGSFusion**（混合生成 + 同步，2025）。

### NeurIPS：数据与“雷达–相机时序融合”

| 论文 | 年份 | 做了什么 | 与你的关系 |
|---|---|---|---|
| **SARDet-100K** | 2024 | 整合 10 个 SAR 检测数据集，10 万级图像 + 开源工具链 | SAR 视觉任务的**数据底座**；不含成像 |
| **M3LEO** | 2024 | 干涉 SAR（InSAR）+ 多光谱的对齐数据集 | **SAR–光学配准**的数据基础，和 SOMA 互补 |
| **CRT-Fusion** | 2024 | 把**运动信息**引入相机–雷达时序融合 | D5 的时序版本；对你的“静态图像 + 连续雷达帧”是个提醒：时序能补几何 |
| **RadarOcc** | 2024 | 4D 成像雷达做 3D 占据预测 | 成像雷达的上游用法 |
| TARSS-Net / RETR / AdaPKC | 2024 | 雷达语义分割 / 多视角检测 / 自适应峰值感受野 | 雷达感知，非成像 |

NeurIPS 2025（用 virtual site 的 5,858 条全量列表）：5 条命中（含 1 条缩写误伤），实质相关的是 RAPTR（雷达 3D 姿态）、**Non-Line-of-Sight 3D Reconstruction with Radar**、V2X-Radar（4D 雷达协同数据集），仍无 SAR。

### ICML：只有 1 篇

**Gamma Distribution PCA-Enhanced Feature Learning for Angle-Robust SAR Target Recognition**（2025）——SAR 目标识别，特征学习侧，与成像无关。

ICML 2024 为 0。这符合预期：ICML 几乎不碰雷达硬件与成像。

### ACM MM：1 篇 SAR–光学匹配 + 5 篇雷达

| 论文 | 年份 | 做了什么 |
|---|---|---|
| **Interpretable Matching of Optical-SAR Image via Dynamically Conditioned Diffusion Models** | 2024 | 用动态条件扩散做**可解释的 SAR–光学匹配** |
| SparseInteraction | 2024 | 稀疏语义引导的雷达–相机 3D 检测 |
| FARFusion V2 | 2024 | 几何约束的路侧远距离雷达–相机融合 |
| FGRFlow / Radar-Mamba / Venus | 2025 | 4D 雷达场景流 / 点云增强 / 用视频生成 mmWave 数据 |

### ACL：0

检索式命中全部是缩写误伤（RADAR 指“放射报告生成”“风险感知路由”，SAR 指“synthetic aperture”但正文是合成数据）。**ACL 与 SAR/雷达感知无交集**，这符合学科分布。

---

## 三、SAR–光学这条线，现在有 8 篇了

上一轮只有 4 篇，这轮扩到 8 篇，而且**第一次出现“几何级”而非“语义级”的工作**：

| 层级 | 论文 | 会场 |
|---|---|---|
| **语义融合**（分割/ReID） | MM-OVSeg、MOS、Ship ReID | CVPR 2026 / ICCV 2025 |
| **表征对齐** | SARMAE（光学语义锚点） | CVPR 2026 |
| **跨模态生成/翻译** | HiFC-GAN、SAR-DisentDM | AAAI 2026 |
| **几何配准/匹配** | **SOMA**、**Interpretable Matching** | AAAI 2026 / ACM MM 2024 |
| **数据底座** | M3LEO（InSAR+多光谱） | NeurIPS 2024 |

**判断**：这 8 篇里，只有 SOMA 和 Interpretable Matching 真正处理“两种模态的几何对应”。它们做的事（把 SAR 和光学的像素对上）和你要做的（把雷达的距离–角度单元和相机的像素对上）在数学上是同构的——**这是你切口 2（MIMO-SAR–相机标定）最直接的可行性证据**。

---

## 四、五个方向的更新

| 方向 | 上一轮 | 本轮新增 | 结论 |
|---|---|---|---|
| **D1 成像前误差** | 1（RC-AutoCalib） | SOMA（跨模态配准，非标定） | 仍无 SAR 阵列校准/自聚焦 |
| **D2 快速重建** | 5（神经场） | NeurIPS 2025 NLOS 重建、RadarOcc | 仍无“深度展开做 SAR 聚焦” |
| **D3 质量改善** | 3 | **DenoDet V2（相位感知）**、SAR-DisentDM、HiFC-GAN | 首次出现“相位保真”类工作，但服务于检测 |
| **D4 计算量** | 3 | 无 | 仍是空白最多的方向 |
| **D5 相机辅助雷达** | 6 | CRT-Fusion、RCTrans、HGSFusion、SparseInteraction、FARFusion V2、SOMA | 扩到 12 篇，但**没有一篇辅助“成像”** |

---

## 五、对四个切口的影响

1. **相机先验约束的 MIMO-SAR 自聚焦**（D1×D5）：仍然无人做。全库没有一篇把相机运动/深度喂给 SAR 相位误差估计。
2. **MIMO-SAR–相机标定**（D5）：**可行性上升**。SOMA（AAAI 2026）证明“SAR–光学几何配准”能进 CCF-A；你的问题只是把“两图配准”换成“热图↔像素的刚体变换”，方法论同源。
3. **相位保真的可微重建**（D2×D3）：**风险下降**。DenoDet V2 在 AAAI 2026 用相位谱做检测，说明“相位”不再是 CV 审稿人的盲区；你把它用到重建，属于同一叙事。
4. **稀疏阵列采样–重建联合优化**（D4×D2）：仍空。D4 在所有会场只有 3 篇，是最“无人区”的方向。

---

## 六、限制（必须写清）

- **AAAI / ACM MM / ACL 是检索式，不是全量标题扫描**。AAAI 用 OJS 关键词检索（radar / SAR / synthetic aperture / mmWave / MIMO / FMCW，2024 年起），可能漏掉题名不含这些词的工作；ACM MM 用 Crossref 容器检索（ACM DL 被 Cloudflare 拦截，无法全量抓取）。
- **NeurIPS 2025 用会议 virtual site 的 5,858 条列表**，因为官方 proceedings 页面当时只发布了 64 条（Creative AI Track）。
- **ECCV 2026 未进 ECVA 索引**，未覆盖。
- **IJCAI 按你要求剔除**；**ICLR 非 CCF-A，未纳入**。
- 所有“论文做了什么”来自摘要原文；凡属判断，标注为“判断”。

---

## 七、附件

- `MIMO-SAR_2024-2026_matrix_v2.xlsx`：在原 21 行基础上新增“扩展 CCF-A”工作表（25 篇），五方向打标
- `MIMO-SAR_CVPR2024-2026.bib`：仍只覆盖 CV 三大会 21 条；扩展会场的条目可按需补 DOI（AAAI 的 DOI 形如 `10.1609/aaai.v40iXX.XXXXX`，需要逐篇核）
