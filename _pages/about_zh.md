---
permalink: /about-zh/
title: ""
excerpt: ""
author_profile: true
lang: zh-CN
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 📖 教育背景

<div class="edu-card">
  <div class="edu-head">
    <span class="edu-title">博士 · 东北大学</span>
    <span class="edu-date">2022.09 – 2027.06</span>
  </div>
  <ul class="edu-detail">
    <li><b>研究方向：</b>多模态检索、视频片段检索、学习型图片压缩、学习型视频压缩、图文检索。</li>
    <li><b>导师：</b><a href="http://faculty.neu.edu.cn/yangxiaochun/zh_CN/zdylm/263676/list/">杨晓春</a></li>
  </ul>
</div>

<div class="edu-card">
  <div class="edu-head">
    <span class="edu-title">本科 · 东北大学</span>
    <span class="edu-date">2018.09 – 2022.06</span>
  </div>
  <ul class="edu-detail">
    <li><b>绩点：</b>4.0246/5.0000（前 8.06%）</li>
  </ul>
</div>

# 📝 发表论文

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
  <div class="pub-meta"><span class="pub-tag ccf-a">KDD-26 · CCF-A</span><span class="pub-tag neutral">2026</span><span class="pub-tag first-author">第一作者</span> <a class="pub-link" href="https://doi.org/10.1145/3770855.3817757">链接</a> <a class="pub-link" href="https://github.com/NoobKLD/ICRM">代码</a> <details class="pub-abs" open><summary>摘要</summary></details><p class="pub-abstract">针对学习型无损图像压缩中逐像素解码开销高、分块解码丢失空间先验的问题，提出交错并行推理（IPI）与不规则因果推理模块（ICRM）：通过块组间交错解码在保持低开销的同时减少“无先验”像素数量，并用 ICRM 对齐交错解码产生的不规则空间先验。在 9 个基准数据集、3 种场景下达到最优，较代表性基线最高节省 20.61% 的 bpp。</p></div>
</div>

<div class="pub-card">
  <div class="pub-title">Kangaroo: Efficient Lossless Floating-Point Compression via Dynamic Reference Selection</div>
  <div class="pub-authors">Shuo Li, Xiaochun Yang, Chunhui Shen, Yutong Han, Xiang Wang, <b>Lingdu Kong</b>, Bin Wang, Feibo Li</div>
  <div class="pub-meta"><span class="pub-tag ccf-a">SIGMOD-26 · CCF-A</span><span class="pub-tag neutral">2026</span> <a class="pub-link" href="https://dl.acm.org/doi/10.1145/3802076">链接</a> <details class="pub-abs"><summary>摘要</summary></details><p class="pub-abstract">面向物联网中浮点数时间序列的流式无损压缩，发现现有 XOR 类算法固定以紧邻前值作参考并非最优。提出 Kangaroo：以“最小化编码比特数”为最优参考准则，用剪枝编码与扩展历史窗口的动态搜索高效定位最优参考，并结合位翻转擦除策略最大化尾随零。在 26 个数据集上全面超越基线，压缩率平均提升 23.2%（最高 98.0%），已部署于阿里云 Lindorm 数据库。</p></div>
</div>

<div class="pub-card">
  <div class="pub-title">Fine-Grained Disentanglement for Alleviating Inconsistencies in Cross-Modal Hashing Retrieval</div>
  <div class="pub-authors">Tieying Li, Xiaochun Yang, Bin Wang, <b>Lingdu Kong</b>, Qingtian Bian, Jiaxing Xu, Boce Chu</div>
  <div class="pub-meta"><span class="pub-tag neutral">DSE · SCI 1区</span><span class="pub-tag neutral">2026</span> <a class="pub-link" href="https://link.springer.com/article/10.1007/s41019-025-00330-w">链接</a> <details class="pub-abs"><summary>摘要</summary></details><p class="pub-abstract">针对跨模态哈希检索中模态-模态、模态-标签的不一致问题，指出现有粗粒度解耦存在语义分离不准、丢失模态共有信息的缺陷，并验证细粒度特征可带来最高 6% 的精度提升。提出 IAFG 框架：语义组件解耦（SCD）用可学习查询向量与竞争式特征路由实现细粒度分离，细粒度语义对齐（FSA）在组件级完成跨模态对齐，无需大规模预训练即在多个基准上取得最优。</p></div>
</div>

<div class="pub-card">
  <div class="pub-title">Reverse Distribution based Video Moment Retrieval for Effective Bias Elimination</div>
  <div class="pub-authors"><b>Lingdu Kong</b>, Xiaochun Yang, Tieying Li, Bin Wang, Xiangmin Zhou</div>
  <div class="pub-meta"><span class="pub-tag ccf-a">AAAI-25 · CCF-A</span><span class="pub-tag neutral">2025</span><span class="pub-tag first-author">第一作者</span> <a class="pub-link" href="https://ojs.aaai.org/index.php/AAAI/article/view/33302">链接</a> <a class="pub-link" href="https://github.com/NoobKLD/ReDis-VMR">代码</a> <details class="pub-abs" open><summary>摘要</summary></details><p class="pub-abstract">针对视频时刻检索（VMR）中的数据偏差与模型偏差，现有 Resplitting 等方法对偏差定义不完整且无法量化。本文给出涵盖数据偏差与模型偏差的完整定义及量化指标，并提出 ReDis-VMR：基于高斯核估计按模型动态生成逆分布数据集以更准确地评估性能；进一步提出 DEA 管道，通过增量扩展模型结构与公平损失抑制集中分布的影响。实验在偏差率上达到最优，并在多种评估方式下验证了有效性。</p></div>
</div>

<div class="pub-card">
  <div class="pub-title">Bridging Modalities: A Survey of Cross-Modal Image-Text Retrieval</div>
  <div class="pub-authors">Tieying Li, <b>Lingdu Kong</b>, Xiaochun Yang, Bin Wang, Jiaxing Xu</div>
  <div class="pub-meta"><span class="pub-tag neutral">CJIF · 综述</span><span class="pub-tag neutral">2024</span> <a class="pub-link" href="https://www.icck.org/article/abs/cjif.2024.361895">链接</a> <details class="pub-abs"><summary>摘要</summary></details><p class="pub-abstract">系统综述跨模态图文检索：针对以往综述仅关注子空间学习或深度模型等单一视角的不足，按模型结构与特征表示将现有方法分为单塔、双塔、实值表示与二值表示四类，重点分析模态融合的作用，并探讨多模态大语言模型（MLLM）对跨模态融合与检索的影响，同时梳理常用数据集、评测指标与代表性方法对比，最后指出开放挑战与未来方向。</p></div>
</div>

<div class="pub-card">
  <div class="pub-title">An Adaptive Video Clip Sampling Approach for Enhancing Query-Based Moment Retrieval in Videos</div>
  <div class="pub-authors"><b>Lingdu Kong</b>, Tieying Li, Xiaochun Yang, Shengzhi Han, Bin Wang</div>
  <div class="pub-meta"><span class="pub-tag ccf-b">DASFAA-23 · CCF-B</span><span class="pub-tag neutral">2023</span><span class="pub-tag first-author">第一作者</span> <a class="pub-link" href="https://doi.org/10.1007/978-3-031-30675-4_28">链接</a> <details class="pub-abs" open><summary>摘要</summary></details><p class="pub-abstract">针对查询式视频时刻检索中固定采样导致长视频丢失片段、采样片段稀疏而影响精度的问题，提出自适应视频片段采样方法：通过重采样找回丢失的标注片段，并对稀疏片段进行增强；基于多个骨干网络获得视频特征后，用一致性损失约束自适应采样特征的语义。在三个真实数据集上的实验证明了方法的有效性，尤其对长视频提升明显。</p></div>
</div>

# 💻 实习经历

<div class="int-card">
  <div class="int-head">
    <span class="int-title"><a href="https://www.aliyun.com/">阿里云计算有限公司</a></span>
    <span class="int-date">2025.02 – 2025.05</span>
  </div>
  <ul class="int-detail">
    <li>车联网图像和视频压缩算法。</li>
    <li>基于JPEG和PNG图像的再压缩。</li>
  </ul>
</div>

<div class="int-card">
  <div class="int-head">
    <span class="int-title"><a href="https://www.baosight.com/">上海宝信软件股份有限公司</a></span>
    <span class="int-date">2022.03 – 2022.10</span>
  </div>
  <ul class="int-detail">
    <li>退火工艺过程参数监控报警。</li>
    <li>CM钢性能预测。</li>
    <li>MSA（测量系统分析）系统开发。</li>
    <li>热轧缺陷一键分析系统开发。</li>
  </ul>
</div>

# 🚀 参与项目

<div class="proj-card">
  <div class="proj-title">面向车联网的海量多模数据压缩技术</div>
  <div class="proj-meta">CCF-阿里云瑶池科研基金 · 东北大学 · 2025</div>
  <details class="proj-abs" open><summary>详情</summary><ul class="proj-list">
    <li>针对车联网中海量多模数据（文本、结构化、浮点数、模型/点云、图像）的存储与传输成本问题，开展高效无损压缩研究。</li>
    <li>围绕车机信号模式提取、图像局部自适应压缩、基于历史动态参照的浮点压缩三个方向展开研究，构建了基于分组块空间先验（GBSP）与元自适应空间先验（MASP）的学习式无损图像压缩框架。</li>
    <li>针对比特流优先、编码端资源受限、解码端资源受限三种实际场景设计模型变体，在 9 个基准数据集上取得最优压缩性能，并展现出较强的零样本泛化能力。</li>
  </ul></details>
</div>

<div class="proj-card">
  <div class="proj-title">光子CT医学影像无损压缩</div>
  <div class="proj-meta">光子计数CT医学影像 · 2026 · 与东软集团合作</div>
  <details class="proj-abs" open><summary>详情</summary><ul class="proj-list">
    <li>面向光子计数CT（Photon-Counting CT）医学影像场景，将学习式无损压缩方法应用于跨解剖部位、多分辨率（512/1024/2048）与多种重建核的医学图像数据集。</li>
    <li>在医学场景中最常见的 1024×1024 分辨率下实现 18.17% 的压缩率，单张图像编码延迟约 4.4ms、解压约 3.2ms，兼顾高吞吐存储与实时传输需求。</li>
    <li>在 2048×2048 超高分辨率图像上仍保持约 20ms 的编码耗时，验证了算法良好的分辨率扩展能力。</li>
  </ul></details>
</div>

# 🎖 荣誉奖项

<div class="honor-card"><span class="honor-name">国家奖学金</span><span class="honor-year">2018</span></div>
<div class="honor-card"><span class="honor-name">校长奖学金</span><span class="honor-year">2022</span></div>
<div class="honor-card"><span class="honor-name">学业奖学金（覆盖全部学费）</span><span class="honor-year">2022–2026</span></div>
<div class="honor-card"><span class="honor-name">院一等奖学金</span><span class="honor-year">2022、2023、2025</span></div>
<div class="honor-card"><span class="honor-name">院二等奖学金</span><span class="honor-year">2018、2019、2024</span></div>
<div class="honor-card"><span class="honor-name">院三等奖学金</span><span class="honor-year">2020</span></div>
<div class="honor-card"><span class="honor-name">优秀学生</span><span class="honor-year">2019</span></div>
<div class="honor-card"><span class="honor-name">优秀学生干部</span><span class="honor-year">2020</span></div>
<div class="honor-card"><span class="honor-name">优秀团员</span><span class="honor-year">2021</span></div>
<div class="honor-card"><span class="honor-name">“华为杯”第二十届中国研究生数学建模竞赛二等奖</span><span class="honor-year">2023</span></div>
