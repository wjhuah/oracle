<div align="center">
<div>
<a href="https://github.com/OBI-Future/PictOBI-20k"><img src="https://visitor-badge.laobi.icu/badge?page_id=zijianchen98/OBI-Bench"/></a>
    <a href="https://github.com/zijianchen98/OBI-Bench"><img src="https://img.shields.io/github/stars/zijianchen98/OBI-Bench"/></a>
    <a href="https://arxiv.org/abs/2509.05773"><img src="https://img.shields.io/badge/Arxiv-2509.05773-red"/></a>
    <a href="https://github.com/OBI-Future/PictOBI-20k"><img src="https://img.shields.io/badge/Awesome-PictOBI--20k-orange"/></a>
</div>

<h1>PictOBI-20k: Unveiling Large Multimodal Models in Visual Decipherment for Pictographic Oracle Bone Characters 🔍</h1>

_The first attempt to apply large multimodal models in paleography and archaeology_

<div>
    Wenjie Hua<sup>1</sup>,
    Zijian Chen<sup>2*</sup>,
    Jinhao Li<sup>1</sup>,
    Lirong Deng<sup>1</sup>,
    Fan Du<sup>1</sup>,
    Tingzhu Chen<sup>2*</sup>,
    Guangtao Zhai<sup>2</sup>
</div>

<div>
  <sup>1</sup>School of Chinese Language and Literature, Wuhan University
  
  <sup>2</sup>Shanghai Jiao Tong University

  <sup>*</sup>Corresponding authors 
</div>   

中文版速递（TBA）

<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/vision_backbone.jpg">
  </div>

</div>

> Overview of **PictOBI-20k**: We present a pictographic Oracle Bone Character (OBC) dataset and evaluation protocols centered on visual decipherment. Tasks include **_1) classification:_** categorizing pictographic OBCs into semantic classes; **_2) retrieval:_** returning visually/semantically aligned OBCs; **_3) consistency:_** testing label stability across variant groups.

## Release
- [2025/09/09] 🔥🔥🔥 Initial repository skeleton with figures & docs (this README, images, PDFs).
- [TBA] Public test splits and evaluation toolkits.
- [TBA] Leaderboard and model submission guideline.

## General Principles
##### Focusing on OBC Visual-Decipherment Abilities of LMMs & Variant-Aware Evaluation

<div style="width: 80%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/accuracy-class.jpg">
  </div>

## Image / Doc Sources
Dataset figures and outlines are curated from our study materials; we additionally provide short docs for quick orientation.

<div style="width: 80%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/consistency.jpg">
  </div>

- Docs: [Intro (PDF)](assets/intro.pdf) · [Overview (PDF)](assets/overview.pdf) · [Reference Map (PDF)](assets/reference_map.pdf)

## Benchmark Candidates
We evaluate representative multimodal models (details in the paper) under unified protocols for classification, retrieval, and variant-group consistency.

<div style="width: 80%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/accuracy-class.jpg">
  </div>

## Performance Benchmark on Pictographic OBC Tasks 

<details close>
<summary>Results on the classification tasks (click to expand)</summary>

<div style="width: 70%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/accuracy-class.jpg">
  </div>
</details>

<details close>
<summary>Results on the retrieval tasks (click to expand)</summary>

<div style="width: 70%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/vision_backbone.jpg">
  </div>
</details>

<details close>
<summary>Results on the consistency (variant-stability) tasks (click to expand)</summary>

<div style="width: 70%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/consistency.jpg">
  </div>
</details>

## Dataset Splits 📦
- [x] To be released with `dataset/` metadata and variant maps.

## Contact 📧
Please contact the authors for queries.

- Wenjie Hua, `huawenchieh@gmail.com`

## Citation📎
If you find our work interesting, please cite:

