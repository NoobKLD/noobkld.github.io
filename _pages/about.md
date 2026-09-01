---
permalink: /
title: ""
excerpt: ""
author_profile: true
lang: en
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

# 📖 Education

<div class="edu-card">
  <div class="edu-head">
    <span class="edu-title">Ph.D. · Northeastern University</span>
    <span class="edu-date">2022.09 – 2027.06</span>
  </div>
  <ul class="edu-detail">
    <li><b>Research Interests:</b> Multimodal Retrieval, Video Moment Retrieval, Learned Image Compression, Learned Video Compression, Text-Image Retrieval.</li>
    <li><b>Supervisor:</b> <a href="http://faculty.neu.edu.cn/yangxiaochun/zh_CN/zdylm/263676/list/">Xiaochun Yang</a></li>
  </ul>
</div>

<div class="edu-card">
  <div class="edu-head">
    <span class="edu-title">Bachelor · Northeastern University</span>
    <span class="edu-date">2018.09 – 2022.06</span>
  </div>
  <ul class="edu-detail">
    <li><b>GPA:</b> 4.0246/5.0000 (Top 8.06%)</li>
  </ul>
</div>

# 📝 Publications

<style>
.pub-card{background:#f7f9fc;border:1px solid #e3e8ef;border-radius:10px;padding:16px 18px;margin:0 0 16px 0;}
.pub-title{font-weight:700;font-size:1.05em;color:#1a1a1a;margin:0 0 4px 0;line-height:1.4;}
.pub-authors{font-size:0.9em;color:#444;margin:0 0 8px 0;}
.pub-meta{margin:0 0 8px 0;display:flex;flex-wrap:wrap;align-items:center;row-gap:6px;}
.pub-tag{display:inline-block;font-size:0.78em;font-weight:600;border-radius:12px;padding:2px 10px;margin:0 6px 0 0;}
.pub-tag.ccf-a{background:#c0392b;color:#fff;}
.pub-tag.ccf-b{background:#2980b9;color:#fff;}
.pub-tag.neutral{background:#566573;color:#fff;}
.pub-link{display:inline-block;padding:2px 12px;border:1px solid #2d6cdf;border-radius:14px;color:#2d6cdf;text-decoration:none;font-size:0.85em;margin-right:6px;}
.pub-link:hover{background:#2d6cdf;color:#fff;}
.pub-abstract{flex-basis:100%;display:none;font-size:0.88em;color:#555;line-height:1.65;margin:10px 0 0 0;padding-top:8px;border-top:1px dashed #d5dbe4;}
.pub-abs[open] ~ .pub-abstract{display:block;}
.pub-abs{margin:0;padding:0;border:0;}
.pub-abs summary{cursor:pointer;list-style:none;user-select:none;outline:none;display:inline-block;padding:2px 12px;border:1px dashed #2d6cdf;border-radius:14px;color:#2d6cdf;font-size:0.85em;font-weight:600;}
.pub-abs summary:hover{background:#eef3fb;}
.pub-abs summary::-webkit-details-marker{display:none;}
.pub-abs summary::before{content:"▸ ";}
.pub-abs[open] summary::before{content:"▾ ";}
.proj-abs{margin-top:10px;padding-top:8px;border-top:1px dashed #d5dbe4;}
.proj-abs summary{cursor:pointer;font-size:0.85em;font-weight:600;color:#2d6cdf;list-style:none;user-select:none;outline:none;}
.proj-abs summary::-webkit-details-marker{display:none;}
.proj-abs summary::before{content:"▸ ";}
.proj-abs[open] summary::before{content:"▾ ";}
.proj-card{background:#f7f9fc;border:1px solid #e3e8ef;border-radius:10px;padding:16px 18px;margin:0 0 16px 0;}
.proj-title{font-weight:700;font-size:1.05em;color:#1a1a1a;margin:0 0 4px 0;line-height:1.4;}
.proj-meta{font-size:0.82em;color:#666;margin:0 0 8px 0;}
.proj-list{margin:0;padding-left:20px;}
.proj-list li{font-size:0.92em;color:#444;line-height:1.6;margin:4px 0;}

.edu-card,.int-card{background:#f7f9fc;border:1px solid #e3e8ef;border-radius:10px;padding:12px 16px;margin:0 0 10px 0;}
.edu-head,.int-head{display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;gap:8px;}
.edu-title,.int-title{font-weight:700;font-size:0.98em;color:#1a1a1a;}
.edu-title a,.int-title a{color:#2d6cdf;text-decoration:none;}
.edu-title a:hover,.int-title a:hover{text-decoration:underline;}
.edu-date,.int-date{font-size:0.78em;font-weight:600;color:#fff;background:#566573;border-radius:12px;padding:2px 10px;white-space:nowrap;}
.edu-detail,.int-detail{margin:6px 0 0 0;padding-left:18px;}
.edu-detail li,.int-detail li{font-size:0.88em;color:#444;line-height:1.55;margin:2px 0;}
.honor-card{display:flex;justify-content:space-between;align-items:center;gap:10px;background:#f7f9fc;border:1px solid #e3e8ef;border-radius:8px;padding:7px 14px;margin:0 0 8px 0;}
.honor-name{font-size:0.9em;color:#333;}
.honor-year{font-size:0.75em;font-weight:600;color:#fff;background:#2d6cdf;border-radius:10px;padding:2px 9px;white-space:nowrap;}
.pub-tag.first-author{background:#27ae60;color:#fff;}

</style>

<div class="pub-card">
  <div class="pub-title">Learned Lossless Image Compression with Interleaved Parallel Inference and Irregular Causal Reasoning</div>
  <div class="pub-authors"><b>Lingdu Kong</b>, Xiaochun Yang, Shuo Li, Tieying Li, Bin Wang, Chunhui Shen, Xiang Wang, Feibo Li</div>
  <div class="pub-meta"><span class="pub-tag ccf-a">KDD-26 · CCF-A</span><span class="pub-tag neutral">2026</span><span class="pub-tag first-author">First Author</span> <a class="pub-link" href="https://doi.org/10.1145/3770855.3817757">link</a> <a class="pub-link" href="https://github.com/NoobKLD/ICRM">code</a> <details class="pub-abs" open><summary>Abstract</summary></details><p class="pub-abstract">To balance the high overhead of pixel-by-pixel decoding and the loss of spatial priors in block-based decoding, this paper proposes Interleaved Parallel Inference (IPI) and an Irregular Causal Reasoning Module (ICRM), which interleave decoding across block groups to reduce prior-less pixels while keeping overhead low. It achieves state-of-the-art results on 9 benchmark datasets and 3 scenarios, saving up to 20.61% bpp over representative baselines.</p></div>
</div>

<div class="pub-card">
  <div class="pub-title">Kangaroo: Efficient Lossless Floating-Point Compression via Dynamic Reference Selection</div>
  <div class="pub-authors">Shuo Li, Xiaochun Yang, Chunhui Shen, Yutong Han, Xiang Wang, <b>Lingdu Kong</b>, Bin Wang, Feibo Li</div>
  <div class="pub-meta"><span class="pub-tag ccf-a">SIGMOD-26 · CCF-A</span><span class="pub-tag neutral">2026</span> <a class="pub-link" href="https://dl.acm.org/doi/10.1145/3802076">link</a> <details class="pub-abs"><summary>Abstract</summary></details><p class="pub-abstract">For streaming lossless compression of floating-point time series in IoT systems, existing XOR-based algorithms that always use the immediate predecessor as the reference are often suboptimal. Kangaroo dynamically selects the best reference via an optimality criterion, a pruning-based encoding strategy, and an efficient search over an extended history window, plus a bit-flip-based erasure strategy. It outperforms all baselines on 26 datasets (average 23.2%, up to 98.0% compression-ratio gain) and has been deployed in Alibaba Cloud's Lindorm database since 2024.</p></div>
</div>

<div class="pub-card">
  <div class="pub-title">Fine-Grained Disentanglement for Alleviating Inconsistencies in Cross-Modal Hashing Retrieval</div>
  <div class="pub-authors">Tieying Li, Xiaochun Yang, Bin Wang, <b>Lingdu Kong</b>, Qingtian Bian, Jiaxing Xu, Boce Chu</div>
  <div class="pub-meta"><span class="pub-tag neutral">DSE · SCI Q1</span><span class="pub-tag neutral">2026</span> <a class="pub-link" href="https://link.springer.com/article/10.1007/s41019-025-00330-w">link</a> <details class="pub-abs"><summary>Abstract</summary></details><p class="pub-abstract">To tackle modality-modality and modality-label inconsistencies in cross-modal hashing retrieval, this work shows that coarse-grained disentanglement mis-separates semantics and loses modality-common information, and that fine-grained features yield up to 6% accuracy gains. It proposes IAFG, whose Semantic Component Disentanglement and Fine-grained Semantic Alignment achieve component-level separation and alignment without extensive pre-training, reaching state-of-the-art accuracy on benchmark datasets.</p></div>
</div>

<div class="pub-card">
  <div class="pub-title">Reverse Distribution based Video Moment Retrieval for Effective Bias Elimination</div>
  <div class="pub-authors"><b>Lingdu Kong</b>, Xiaochun Yang, Tieying Li, Bin Wang, Xiangmin Zhou</div>
  <div class="pub-meta"><span class="pub-tag ccf-a">AAAI-25 · CCF-A</span><span class="pub-tag neutral">2025</span><span class="pub-tag first-author">First Author</span> <a class="pub-link" href="https://ojs.aaai.org/index.php/AAAI/article/view/33302">link</a> <a class="pub-link" href="https://github.com/NoobKLD/ReDis-VMR">code</a> <details class="pub-abs" open><summary>Abstract</summary></details><p class="pub-abstract">This paper provides a complete definition and quantitative metrics for both data bias and model bias in video moment retrieval (VMR), going beyond existing resplitting-based methods. It introduces ReDis-VMR, which dynamically generates inverse-distribution datasets via Gaussian kernel estimation for fairer evaluation, and the DEA pipeline, which incrementally expands the model and uses a fair loss to suppress concentrated distributions, achieving state-of-the-art bias elimination.</p></div>
</div>

<div class="pub-card">
  <div class="pub-title">Bridging Modalities: A Survey of Cross-Modal Image-Text Retrieval</div>
  <div class="pub-authors">Tieying Li, <b>Lingdu Kong</b>, Xiaochun Yang, Bin Wang, Jiaxing Xu</div>
  <div class="pub-meta"><span class="pub-tag neutral">CJIF · Survey</span><span class="pub-tag neutral">2024</span> <a class="pub-link" href="https://www.icck.org/article/abs/cjif.2024.361895">link</a> <details class="pub-abs"><summary>Abstract</summary></details><p class="pub-abstract">A comprehensive survey of cross-modal image-text retrieval that addresses the limitations of prior single-perspective reviews. It categorizes existing models into single-tower, dual-tower, real-value, and binary representation models, highlights the role of modality fusion, discusses the impact of multimodal large language models, and reviews datasets, metrics, and performance comparisons before outlining open challenges and future directions.</p></div>
</div>

<div class="pub-card">
  <div class="pub-title">An Adaptive Video Clip Sampling Approach for Enhancing Query-Based Moment Retrieval in Videos</div>
  <div class="pub-authors"><b>Lingdu Kong</b>, Tieying Li, Xiaochun Yang, Shengzhi Han, Bin Wang</div>
  <div class="pub-meta"><span class="pub-tag ccf-b">DASFAA-23 · CCF-B</span><span class="pub-tag neutral">2023</span><span class="pub-tag first-author">First Author</span> <a class="pub-link" href="https://doi.org/10.1007/978-3-031-30675-4_28">link</a> <details class="pub-abs" open><summary>Abstract</summary></details><p class="pub-abstract">To mitigate accuracy loss in query-based moment retrieval caused by fixed sampling—which drops clips in long videos and leaves sampled clips sparse—this work proposes adaptive video clip sampling that resamples missing annotated clips and enhances sparsely sampled ones, then uses a consistency loss to learn the semantics of adaptively sampled features. Experiments on three real datasets show its effectiveness, especially for long videos.</p></div>
</div>

# 💻 Internships

<div class="int-card">
  <div class="int-head">
    <span class="int-title"><a href="https://www.aliyun.com/">Alibaba Cloud Computing Co., Ltd.</a></span>
    <span class="int-date">2025.02 – 2025.05</span>
  </div>
  <ul class="int-detail">
    <li>Image and video compression algorithms for the Internet of Vehicles.</li>
    <li>Re-compression based on JPEG and PNG images.</li>
  </ul>
</div>

<div class="int-card">
  <div class="int-head">
    <span class="int-title"><a href="https://www.baosight.com/">Shanghai Baosight Software Co., Ltd.</a></span>
    <span class="int-date">2022.03 – 2022.10</span>
  </div>
  <ul class="int-detail">
    <li>Monitoring and alarm system for annealing process parameters.</li>
    <li>Performance prediction of CM steel.</li>
    <li>Development of the MSA (Measurement System Analysis) system.</li>
    <li>Development of a one-click analysis system for hot rolling defects.</li>
  </ul>
</div>

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

<div class="honor-card"><span class="honor-name">National Scholarship</span><span class="honor-year">2018</span></div>
<div class="honor-card"><span class="honor-name">Presidential Scholarship</span><span class="honor-year">2022</span></div>
<div class="honor-card"><span class="honor-name">Academic Scholarship (Full Tuition Coverage)</span><span class="honor-year">2022–2026</span></div>
<div class="honor-card"><span class="honor-name">First-Class Scholarship</span><span class="honor-year">2022, 2023, 2025</span></div>
<div class="honor-card"><span class="honor-name">Second-Class Scholarship</span><span class="honor-year">2018, 2019, 2024</span></div>
<div class="honor-card"><span class="honor-name">Third-Class Scholarship</span><span class="honor-year">2020</span></div>
<div class="honor-card"><span class="honor-name">Outstanding Student</span><span class="honor-year">2019</span></div>
<div class="honor-card"><span class="honor-name">Outstanding Student Leader</span><span class="honor-year">2020</span></div>
<div class="honor-card"><span class="honor-name">Excellent Communist Youth League Member</span><span class="honor-year">2021</span></div>
<div class="honor-card"><span class="honor-name">Second Prize, 20th “Huawei Cup” China Postgraduate Mathematical Contest in Modeling</span><span class="honor-year">2023</span></div>
