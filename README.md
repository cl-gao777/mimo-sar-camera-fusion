# MIMO-SAR × Camera Fusion — A 2024–2026 Landscape

![papers](https://img.shields.io/badge/papers-101-blue) ![venues](https://img.shields.io/badge/venues-7-green) ![SAR](https://img.shields.io/badge/SAR_papers-19-orange) ![MIMO--SAR](https://img.shields.io/badge/MIMO--SAR-0-red) ![license](https://img.shields.io/badge/license-CC_BY_4.0-lightgrey)

A verified map of radar / SAR × camera fusion at the top computer-vision and AI venues, 2024–2026.

**101 papers · 7 venues · 19 SAR papers · 0 MIMO-SAR papers.**

---

## TL;DR

Across **31,008** fully scanned titles from CVPR, ICCV, ECCV, NeurIPS and ICML — plus keyword sweeps of AAAI, ACM MM and ACL — there is **not a single paper on MIMO-SAR imaging**, and therefore none on camera-assisted MIMO-SAR.

SAR appears at these venues almost exclusively as an **image modality** (detection, segmentation, re-identification, registration, generation), never as an **imaging problem** (focusing, autofocus, array calibration, motion compensation). The few optical–SAR papers fuse *semantics*, not *geometry*.

That gap is the point of this repository.

---

## Scope

| Venue | Years | Retrieval | Titles |
|---|---|---|---|
| CVPR | 2024, 2025, 2026 | full title scan | 9,629 |
| ICCV | 2025 | full title scan | 2,701 |
| ECCV (CCF-B) | 2024 | full title scan | 2,387 |
| NeurIPS | 2024, 2025 | full title scan | 10,351 |
| ICML | 2024, 2025 | full title scan | 5,940 |
| AAAI | 2024–2026 | OJS keyword search | — |
| ACM MM | 2024, 2025 | Crossref keyword search | — |
| ACL | 2024, 2025 | Crossref keyword search | — |

**Excluded on purpose:** IJCAI (out of scope for this survey), ICLR (not a CCF-A venue), ECCV 2026 (not yet indexed by ECVA at retrieval time).

Retrieval date: **2026-11-04**.

---

## Counts

| Venue | 2024 | 2025 | 2026 | Total |
|---|---:|---:|---:|---:|
| CVPR | 9 | 8 | 22 | **39** |
| ICCV | — | 11 | — | **11** |
| ECCV | 8 | — | — | **8** |
| NeurIPS | 7 | 4 | — | **11** |
| ICML | 0 | 1 | — | **1** |
| AAAI | 2 | 5 | 18 | **25** |
| ACM MM | 3 | 3 | — | **6** |
| **Total** | | | | **101** |

By type: radar perception 48 · radar–camera 17 · radar imaging/reconstruction 11 · SAR downstream 8 · **SAR–optical 6** · radar data/benchmark 5 · SAR data/benchmark 3 · SAR generation 2 · GPR 1.

---

## Five research directions

The directions follow the usual pipeline of a radar imaging system: before imaging, during imaging, after imaging, the compute budget, and camera assistance.

| # | Direction | What exists in 2024–2026 | Closest work | Gap |
|---|---|---|---|---|
| D1 | Pre-imaging error handling (array calibration, motion compensation) | 1 paper, and it is radar–camera extrinsics, not SAR | [RC-AutoCalib](https://openaccess.thecvf.com/content/CVPR2025/html/Luu_RC-AutoCalib_An_End-to-End_Radar-Camera_Automatic_Calibration_Network_CVPR_2025_paper.html) (CVPR 2025) | SAR autofocus / array calibration: **empty** |
| D2 | Fast reconstruction (physics-constrained learning, deep unfolding) | 11 papers, all neural fields / rendering | [DART](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_DART_Implicit_Doppler_Tomography_for_Radar_Novel_View_Synthesis_CVPR_2024_paper.html) (CVPR 2024), RF4D, Rascene (CVPR 2026) | Deep unfolding for MIMO-SAR focusing: **empty** |
| D3 | Post-imaging quality (denoising, sidelobes, super-resolution, phase) | 3–4 papers, mostly for detection | [DenoDet V2](https://ojs.aaai.org/index.php/AAAI/article/view/37761) (AAAI 2026) | Phase-preserving restoration: **empty** |
| D4 | Compute reduction (sampling, early exit, compression) | 3 papers | AdaRadar, RAVEN (CVPR 2026), SparseRadNet (ECCV 2024) | Sampling–reconstruction co-design for MIMO-SAR: **empty** |
| D5 | Camera-assisted radar (calibration, association, geometric priors) | 17 radar–camera papers + 6 optical–SAR papers | [SOMA](https://ojs.aaai.org/index.php/AAAI/article/view/37939) (AAAI 2026), MM-OVSeg (CVPR 2026) | Camera-assisted SAR **imaging**: **empty** |

---

## Start here

Six papers that define the current frontier, one per direction:

1. **SOMA: Feature Gradient Enhanced Affine-Flow Matching for SAR-Optical Registration** — AAAI 2026. Dense pixel-level SAR↔optical registration with structural gradient priors. The closest existing work to "camera-assisted radar geometry".
2. **DenoDet V2: Phase-Amplitude Cross Denoising for SAR Object Detection** — AAAI 2026. The only CCF-A paper that treats phase as a first-class citizen in SAR feature modulation.
3. **MM-OVSeg: Multimodal Optical-SAR Fusion for Open-Vocabulary Segmentation** — CVPR 2026. The most complete optical–SAR fusion framework so far, at the semantic level.
4. **RC-AutoCalib: An End-to-End Radar-Camera Automatic Calibration Network** — CVPR 2025. Online geometric calibration; mathematically the same problem as CCS↔ACS alignment.
5. **DART: Implicit Doppler Tomography for Radar Novel View Synthesis** — CVPR 2024. A differentiable radar forward operator, the piece needed to put SAR imaging inside a learning loop.
6. **SARDet-100K: Towards Open-Source Benchmark and ToolKit for Large-Scale SAR Object Detection** — NeurIPS 2024. The data foundation for anything SAR-related.

---

## Open problems

1. **Vision-prior-constrained MIMO-SAR autofocus.** No paper feeds camera depth or optical flow into SAR phase-error estimation.
2. **MIMO-SAR ↔ camera hand-eye calibration.** SOMA shows that cross-modal geometric registration is publishable at CCF-A; nobody has moved it from "two images" to "range–angle heatmap ↔ pixels".
3. **Phase-preserving differentiable SAR reconstruction.** Every CV radar reconstruction (DART, RF4D, Rascene) is amplitude/power-only. Interferometry and deformation monitoring consume phase alone.
4. **Sampling–reconstruction co-design for sparse MIMO arrays.** D4 has the fewest papers of all five directions.

---

## Repository layout

```
.
├── README.md
├── papers/
│   ├── by-venue.md                 # every paper, grouped by venue and year
│   ├── by-venue.xlsx               # same, filterable
│   ├── papers.csv                  # flat table: conference, year, type, title, url
│   ├── five-directions-matrix.xlsx # venue × direction coverage matrix
│   └── reading-list.md             # recommended reading, 16 papers with notes (Chinese)
├── bib/
│   └── mimo-sar-2024-2026.bib      # 21 BibTeX entries, official CVF metadata
├── reports/
│   ├── cvpr-iccv-eccv-2024-2026.md # first pass over the CV venues (Chinese)
│   └── ccf-a-addendum-2024-2026.md # AAAI / NeurIPS / ICML / ACM MM / ACL (Chinese)
└── LICENSE
```

---

## Caveats

- Counts are a **snapshot** at 2026-11-04, not a living census.
- CVPR / ICCV / ECCV / NeurIPS / ICML were scanned at **title level**, so a paper whose title omits `radar`, `SAR`, `mmWave` etc. can be missed.
- AAAI, ACM MM and ACL were retrieved through **keyword search** (AAAI OJS, Crossref), which is less complete than a full listing. ACM DL blocks automated crawling.
- NeurIPS 2025 was taken from the conference virtual site (5,858 accepted papers) because the official proceedings page had not been fully published.
- "MIMO-SAR = 0" is a statement about **these venues**, not about the literature. MIMO-SAR imaging lives in IEEE TGRS / TAES / TSP and at IGARSS / EUSAR.

---

## Contributing

Corrections and additions are welcome. Please open a PR that adds one line to `papers/papers.csv`:

```csv
conference,year,type,title,url
CVPR,2026,SAR downstream,Your Paper Title,https://...
```

and, if possible, the corresponding entry in `papers/by-venue.md`. Papers must be from a CCF-A venue and published in 2024 or later.

---

## Citation

```bibtex
@misc{mimosar2026,
  author       = {cl-gao777},
  title        = {MIMO-SAR x Camera Fusion: A 2024-2026 Landscape},
  year         = {2026},
  howpublished = {\url{https://github.com/cl-gao777/mimo-sar-camera-fusion}}
}
```

## License

[CC BY 4.0](LICENSE) — reuse with attribution.
