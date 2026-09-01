---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<!-- Language switcher -->
<div style="text-align: right; margin-bottom: 1.2em;">
  <span style="display: inline-block; padding: 0.35em 1.1em; margin: 0 0.25em; border-radius: 20px; font-size: 0.92em; background: #2d6cdf; color: #fff;">English</span>
  <a href="{{ site.baseurl }}/about-zh/" style="display: inline-block; padding: 0.35em 1.1em; margin: 0 0.25em; border-radius: 20px; font-size: 0.92em; text-decoration: none; border: 1px solid #2d6cdf; color: #2d6cdf;">中文</a>
</div>

# 📝 Publications

<style>
.pub-card{background:#f7f9fc;border:1px solid #e3e8ef;border-radius:10px;padding:16px 18px;margin:0 0 16px 0;}
.pub-title{font-weight:700;font-size:1.05em;color:#1a1a1a;margin:0 0 4px 0;line-height:1.4;}
.pub-authors{font-size:0.9em;color:#444;margin:0 0 8px 0;}
.pub-meta{margin:0 0 8px 0;}
.pub-tag{display:inline-block;font-size:0.78em;font-weight:600;border-radius:12px;padding:2px 10px;margin:0 6px 0 0;}
.pub-tag.ccf-a{background:#c0392b;color:#fff;}
.pub-tag.ccf-b{background:#2980b9;color:#fff;}
.pub-tag.neutral{background:#566573;color:#fff;}
.pub-links{margin:0 0 10px 0;}
.pub-link{display:inline-block;padding:2px 12px;border:1px solid #2d6cdf;border-radius:14px;color:#2d6cdf;text-decoration:none;font-size:0.85em;margin-right:6px;}
.pub-link:hover{background:#2d6cdf;color:#fff;}
.pub-abstract{font-size:0.88em;color:#555;line-height:1.65;margin:8px 0 0 0;}
.pub-abs,.proj-abs{margin-top:10px;padding-top:8px;border-top:1px dashed #d5dbe4;}
.pub-abs summary,.proj-abs summary{cursor:pointer;font-size:0.85em;font-weight:600;color:#2d6cdf;list-style:none;user-select:none;outline:none;}
.pub-abs summary::-webkit-details-marker,.proj-abs summary::-webkit-details-marker{display:none;}
.pub-abs summary::before,.proj-abs summary::before{content:"▸ ";}
.pub-abs[open] summary::before,.proj-abs[open] summary::before{content:"▾ ";}
.proj-card{background:#f7f9fc;border:1px solid #e3e8ef;border-radius:10px;padding:16px 18px;margin:0 0 16px 0;}
.proj-title{font-weight:700;font-size:1.05em;color:#1a1a1a;margin:0 0 4px 0;line-height:1.4;}
.proj-meta{font-size:0.82em;color:#666;margin:0 0 8px 0;}
.proj-list{margin:0;padding-left:20px;}
.proj-list li{font-size:0.92em;color:#444;line-height:1.6;margin:4px 0;}
</style>

<div class="pub-card">
  <div class="pub-title">Learned Lossless Image Compression with Interleaved Parallel Inference and Irregular Causal Reasoning</div>
  <div class="pub-authors"><b>Lingdu Kong</b>, Xiaochun Yang, Shuo Li, Tieying Li, Bin Wang, Chunhui Shen, Xiang Wang, Feibo Li</div>
  <div class="pub-meta"><span class="pub-tag ccf-a">KDD-26 · CCF-A</span><span class="pub-tag neutral">2026</span></div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.1145/3770855.3817757">link</a>
    <a class="pub-link" href="https://github.com/NoobKLD/ICRM">code</a>
  </div>
  <details class="pub-abs" open><summary>Abstract</summary><p class="pub-abstract">To balance the high overhead of pixel-by-pixel decoding and the loss of spatial priors in block-based decoding, this paper proposes Interleaved Parallel Inference (IPI) and an Irregular Causal Reasoning Module (ICRM), which interleave decoding across block groups to reduce prior-less pixels while keeping overhead low. It achieves state-of-the-art results on 9 benchmark datasets and 3 scenarios, saving up to 20.61% bpp over representative baselines.</p></details>
</div>

<div class="pub-card">
  <div class="pub-title">Kangaroo: Efficient Lossless Floating-Point Compression via Dynamic Reference Selection</div>
  <div class="pub-authors">Shuo Li, Xiaochun Yang, Chunhui Shen, Yutong Han, Xiang Wang, <b>Lingdu Kong</b>, Bin Wang, Feibo Li</div>
  <div class="pub-meta"><span class="pub-tag ccf-a">SIGMOD-26 · CCF-A</span><span class="pub-tag neutral">2026</span></div>
  <div class="pub-links">
    <a class="pub-link" href="https://dl.acm.org/doi/10.1145/3802076">link</a>
  </div>
  <details class="pub-abs"><summary>Abstract</summary><p class="pub-abstract">For streaming lossless compression of floating-point time series in IoT systems, existing XOR-based algorithms that always use the immediate predecessor as the reference are often suboptimal. Kangaroo dynamically selects the best reference via an optimality criterion, a pruning-based encoding strategy, and an efficient search over an extended history window, plus a bit-flip-based erasure strategy. It outperforms all baselines on 26 datasets (average 23.2%, up to 98.0% compression-ratio gain) and has been deployed in Alibaba Cloud's Lindorm database since 2024.</p></details>
</div>

<div class="pub-card">
  <div class="pub-title">Fine-Grained Disentanglement for Alleviating Inconsistencies in Cross-Modal Hashing Retrieval</div>
  <div class="pub-authors">Tieying Li, Xiaochun Yang, Bin Wang, <b>Lingdu Kong</b>, Qingtian Bian, Jiaxing Xu, Boce Chu</div>
  <div class="pub-meta"><span class="pub-tag neutral">DSE · SCI Q1</span><span class="pub-tag neutral">2026</span></div>
  <div class="pub-links">
    <a class="pub-link" href="https://link.springer.com/article/10.1007/s41019-025-00330-w">link</a>
  </div>
  <details class="pub-abs"><summary>Abstract</summary><p class="pub-abstract">To tackle modality-modality and modality-label inconsistencies in cross-modal hashing retrieval, this work shows that coarse-grained disentanglement mis-separates semantics and loses modality-common information, and that fine-grained features yield up to 6% accuracy gains. It proposes IAFG, whose Semantic Component Disentanglement and Fine-grained Semantic Alignment achieve component-level separation and alignment without extensive pre-training, reaching state-of-the-art accuracy on benchmark datasets.</p></details>
</div>

<div class="pub-card">
  <div class="pub-title">Reverse Distribution based Video Moment Retrieval for Effective Bias Elimination</div>
  <div class="pub-authors"><b>Lingdu Kong</b>, Xiaochun Yang, Tieying Li, Bin Wang, Xiangmin Zhou</div>
  <div class="pub-meta"><span class="pub-tag ccf-a">AAAI-25 · CCF-A</span><span class="pub-tag neutral">2025</span></div>
  <div class="pub-links">
    <a class="pub-link" href="https://ojs.aaai.org/index.php/AAAI/article/view/33302">link</a>
    <a class="pub-link" href="https://github.com/NoobKLD/ReDis-VMR">code</a>
  </div>
  <details class="pub-abs" open><summary>Abstract</summary><p class="pub-abstract">This paper provides a complete definition and quantitative metrics for both data bias and model bias in video moment retrieval (VMR), going beyond existing resplitting-based methods. It introduces ReDis-VMR, which dynamically generates inverse-distribution datasets via Gaussian kernel estimation for fairer evaluation, and the DEA pipeline, which incrementally expands the model and uses a fair loss to suppress concentrated distributions, achieving state-of-the-art bias elimination.</p></details>
</div>

<div class="pub-card">
  <div class="pub-title">Bridging Modalities: A Survey of Cross-Modal Image-Text Retrieval</div>
  <div class="pub-authors">Tieying Li, <b>Lingdu Kong</b>, Xiaochun Yang, Bin Wang, Jiaxing Xu</div>
  <div class="pub-meta"><span class="pub-tag neutral">CJIF · Survey</span><span class="pub-tag neutral">2024</span></div>
  <div class="pub-links">
    <a class="pub-link" href="https://www.icck.org/article/abs/cjif.2024.361895">link</a>
  </div>
  <details class="pub-abs"><summary>Abstract</summary><p class="pub-abstract">A comprehensive survey of cross-modal image-text retrieval that addresses the limitations of prior single-perspective reviews. It categorizes existing models into single-tower, dual-tower, real-value, and binary representation models, highlights the role of modality fusion, discusses the impact of multimodal large language models, and reviews datasets, metrics, and performance comparisons before outlining open challenges and future directions.</p></details>
</div>

<div class="pub-card">
  <div class="pub-title">An Adaptive Video Clip Sampling Approach for Enhancing Query-Based Moment Retrieval in Videos</div>
  <div class="pub-authors"><b>Lingdu Kong</b>, Tieying Li, Xiaochun Yang, Shengzhi Han, Bin Wang</div>
  <div class="pub-meta"><span class="pub-tag ccf-b">DASFAA-23 · CCF-B</span><span class="pub-tag neutral">2023</span></div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.1007/978-3-031-30675-4_28">link</a>
  </div>
  <details class="pub-abs" open><summary>Abstract</summary><p class="pub-abstract">To mitigate accuracy loss in query-based moment retrieval caused by fixed sampling—which drops clips in long videos and leaves sampled clips sparse—this work proposes adaptive video clip sampling that resamples missing annotated clips and enhances sparsely sampled ones, then uses a consistency loss to learn the semantics of adaptively sampled features. Experiments on three real datasets show its effectiveness, especially for long videos.</p></details>
</div>

# 📖 Education

- *2022.09 - 2027.06*, Northeastern University, Ph.D.
    - Research Interests: Multimodal Retrieval, Video Moment Retrieval, Learned Image Compression, Learned Video Compression, Text-Image Retrieval.
    - Supervisor: [Xiaochun Yang](http://faculty.neu.edu.cn/yangxiaochun/zh_CN/zdylm/263676/list/).
- *2018.09 - 2022.06*, Northeastern University, Bachelor.
    - GPA: 4.0246/5.0000 (Top 8.06%).

# 💻 Internships

- *2025.02 - 2025.05*, [Alibaba Cloud Computing Co., Ltd.](https://www.aliyun.com/)
    - Image and video compression algorithms for the Internet of Vehicles.
- *2022.03 - 2022.10*, [Shanghai Baosight Software Co., Ltd.](https://www.baosight.com/)
    - Monitoring and alarm system for annealing process parameters.
    - Performance prediction of CM steel.
    - Development of the MSA (Measurement System Analysis) system.
    - Development of a one-click analysis system for hot rolling defects.

# 🚀 Projects

<div class="proj-card">
  <div class="proj-title">Massive Multi-modal Data Compression for the Internet of Vehicles</div>
  <div class="proj-meta">CCF-Alibaba “Yao Chi” Research Fund · Northeastern University · 2025</div>
  <details class="proj-abs" open><summary>Details</summary><ul class="proj-list">
    <li>Studies efficient lossless compression for the massive multi-modal data (text, structured, floating-point, model/point-cloud, and image) generated in connected-vehicle scenarios, aiming to reduce storage and transmission costs.</li>
    <li>Covers pattern-based vehicle signal extraction, local adaptive image compression, and floating-point compression with dynamic historical reference; developed a learned lossless image compression framework based on Grouped Block Spatial Priors (GBSP) and Meta-Adaptive Spatial Priors (MASP).</li>
    <li>Designed model variants for bitstream-first, encoder-constrained, and decoder-constrained scenarios, achieving state-of-the-art compression performance on 9 benchmark datasets with strong zero-shot generalization.</li>
  </ul></details>
</div>

<div class="proj-card">
  <div class="proj-title">Lossless Compression on Photon-Counting CT Medical Images</div>
  <div class="proj-meta">Photon-counting CT medical imaging · 2026 · in collaboration with Neusoft Group</div>
  <details class="proj-abs" open><summary>Details</summary><ul class="proj-list">
    <li>Applies learned lossless image compression to photon-counting CT (PCCT) medical datasets covering multiple anatomical regions, resolutions (512/1024/2048), and reconstruction kernels.</li>
    <li>At the most common 1024×1024 resolution, achieves an 18.17% compression ratio with ~4.4 ms encoding and ~3.2 ms decoding per image, balancing high-throughput storage and real-time transmission needs.</li>
    <li>Keeps encoding time around 20 ms even on 2048×2048 ultra-high-resolution images, demonstrating good scalability across resolutions.</li>
  </ul></details>
</div>

# 🎖 Honors and Awards

- *2018*, National Scholarship.
- *2022*, Presidential Scholarship.
- *2022, 2023, 2024, 2025, 2026*, Academic Scholarship (Full Tuition Coverage).
- *2022, 2023, 2025*, First-Class Scholarship.
- *2018, 2019, 2024*, Second-Class Scholarship.
- *2020*, Third-Class Scholarship.
- *2019*, Outstanding Student.
- *2020*, Outstanding Student Leader.
- *2021*, Excellent Communist Youth League Member.
- *2023*, Second Prize, 20th “Huawei Cup” China Postgraduate Mathematical Contest in Modeling.
