<div align="center">
<div>
<a href="https://github.com/OBI-Future/PictOBI-20k"><img src="https://visitor-badge.laobi.icu/badge?page_id=OBI-Future/PictOBI-20k"/></a>
    <a href="https://github.com/OBI-Future/PictOBI-20k"><img src="https://img.shields.io/github/stars/OBI-Future/PictOBI-20k"/></a>
    <a href="https://arxiv.org/abs/2509.05773"><img src="https://img.shields.io/badge/Arxiv-2509.05773-red"/></a>
    <a href="https://github.com/OBI-Future/PictOBI-20k"><img src="https://img.shields.io/badge/Awesome-PictOBI--20k-orange"/></a>
</div>

<h1>PictOBI-20k: Unveiling Large Multimodal Models in Visual Decipherment for Pictographic Oracle Bone Characters 🔍</h1>

_A pioneering benchmark bridging large multimodal models with the visual decipherment of ancient Chinese oracle bone scripts_


<div>
    Zijian Chen<sup>1,2,†</sup>,
    Wenjie Hua<sup>3,†</sup>,
    Jinhao Li<sup>4</sup>,
    Lirong Deng<sup>5</sup>,
    Fan Du<sup>6</sup>,
    Tingzhu Chen<sup>1,★</sup>,
    Guangtao Zhai<sup>1,2,★</sup>
</div>

<div>
  <sup>1</sup>Shanghai Jiao Tong University  
  <sup>2</sup>Shanghai AI Lab  
  <sup>3</sup>Wuhan University  
  <sup>4</sup>East China Normal University  
  <sup>5</sup>Macao Polytechnic University  
  <sup>6</sup>Southern University of Science and Technology  

  <sup>†</sup>Equal contribution &nbsp;&nbsp; <sup>★</sup>Corresponding authors

</div>

<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/intro.jpg">
  </div>
  
> Overview of **PictOBI-20k**:  
> We present **PictOBI-20k**, a large-scale dataset for evaluating LMMs on the visual decipherment of pictographic Oracle Bone Characters (OBCs). The dataset comprises **20k carefully curated OBC–object image pairs** and over **15k multi-choice questions**. To further assess visual reasoning, we provide **subjective annotations** examining the consistency of reference points between humans and LMMs. Experimental results suggest that while general LMMs exhibit preliminary visual decipherment ability, they often fail to effectively leverage visual information and remain constrained by language priors. We hope PictOBI-20k can serve as a foundation for advancing evaluation and optimization of **visual attention in OBC-oriented LMMs**.

## Release
- [TBA] Public datasets release.  
- [2025/09/09] 🔥 Github repository for **PictOBI-20k** is online.


## General Principles
##### Centering on the Visual-Decipherment Abilities of LMMs for OBCs

PictOBI-20k is specifically designed to probe how well large multimodal models (LMMs) can visually decipher pictographic Oracle Bone Characters (OBCs).  
Unlike purely textual decipherment, our benchmark emphasizes **visual alignment between OBCs and their real-world referents**, aligning with the original pictographic nature of the script.

<div style="width: 80%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/overview.jpg">
</div>

## OBC and Real-Object Image Sources

We curate OBC images from **eight major resources**, including classic OBC websites (e.g., YinQiWenYuan, XiaoXueTang, GuoXueDaShi) and open datasets such as **Oracle-241, Oracle-50k, HUST-OBS, OBI125, and OBIdatasetIJDH**.  
Corresponding **real-object images** (≈4.8k) are carefully collected from Freepik, Pexels, Pinterest, and the Academia Sinica Bronze Ware Database, ensuring coverage across 80 representative pictographic categories:contentReference[oaicite:1]{index=1}.

<div style="width: 80%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/source.png">
</div>

## Benchmark Candidates

We benchmark **11 prominent LMMs**—including GPT-4o, Gemini 2.5 Pro, Claude 4 Sonnet, GLM-4.5V, Qwen2.5-VL series, and InternVL3 series—under a unified protocol covering:  
- **Classification** (multi-choice mapping of OBCs to objects)  
- **Retrieval** (searching semantically/visually aligned items)  
- **Variant-group consistency** (alignment stability across glyph variants)

In addition, we disentangle performance by testing **standalone vision encoders** (CLIP-L/14, DINOv2-L/14, InternViT-300M) to reveal gaps between vision backbones and multimodal reasoning:contentReference[oaicite:2]{index=2}.

<div style="width: 80%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/candidate.jpg">
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

