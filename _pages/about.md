---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
  dl {
    margin-bottom: 60px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }
    /* 会议标签样式 */
  .conference-label {
    position: absolute;
    top: 10px;
    left: -5px;
    background-color: #2c3e50;  /* 深蓝色背景 */
    color: white;  /* 白色文字 */
    padding: 6px 12px;
    border-radius: 6px;
    font-size: 0.95em;
    font-weight: 600;
    letter-spacing: 0.5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    z-index: 1;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    font-style: italic;  /* 添加斜体 */
  }
   /* 鼠标悬停效果 */
  .conference-label:hover {
    background-color: #34495e;  /* 悬停时稍微变亮 */
    transition: background-color 0.2s ease;
  }

  dl dt img {
    width: 100%; /* 在移动端默认占满宽度 */
    aspect-ratio: 2/1; /* 设置宽高比为2:1，即高度为宽度的一半 */
    object-fit: cover; /* 确保图片不会被裁剪 */
    display: block;
    margin: 10px 10px 10px 0px; /* 适当的间距 */
    
    /* 添加美化效果 */
    border-radius: 8px; /* 让图片有轻微的圆角 */
    border: 2px solid #ddd; /* 添加淡灰色的边框 */
    box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2); /* 添加轻微阴影 */
    padding: 5px; /* 给图片一些内边距，让它不贴着边框 */
    background-color: #fff; /* 设置背景色，让图片更加干净 */
  }
  /* 教育和工作经历卡片样式 */
  .experience-card, .education-card {
    display: flex;
    align-items: center;
    gap: 25px;
    margin-bottom: 30px;
    padding: 20px;
    background: #f8f9fa;
    border-radius: 12px;
    transition: all 0.3s ease;
    border: 1px solid #e9ecef;
  }

  .experience-card:hover, .education-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    border-color: #dee2e6;
  }

  .experience-info, .education-info {
    flex: 1;
  }

  .experience-logo, .education-logo {
    flex-shrink: 0;
    width: 100px;
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: white;
    border-radius: 10px;
    padding: 10px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
  }

  .experience-logo img, .education-logo img {
    width: 100%;
    height: 100%;
    object-fit: contain;
  }

  .experience-title, .education-title {
    font-size: 1.2em;
    margin-bottom: 8px;
    color: #2c3e50;
  }

  .experience-title a, .education-title a {
    color: #2c3e50;
    text-decoration: none;
    transition: color 0.3s ease;
  }

  .experience-title a:hover, .education-title a:hover {
    color: #3498db;
  }

  .experience-role, .education-role {
    color: #666;
    font-style: italic;
    margin-bottom: 5px;
  }

  .experience-topics, .education-topics {
    color: #666;
    font-style: italic;
  }

  .section-title {
    font-size: 1.8em;
    color: #2c3e50;
    margin: 40px 0 20px;
    padding-bottom: 10px;
    border-bottom: 2px solid #ecf0f1;
  }
  
  .globe-container {
    /* 1. 实现水平居中 */
    max-width: 300px; /* 缩小：设置您想要的宽度，例如300px */
    margin-left: auto; /* 自动左边距 */
    margin-right: auto; /* 自动右边距 */
    /* 或者使用更现代的 Flex 布局实现居中（如果容器本身是块级元素，上面三行即可）*/
    /* display: flex; */
    /* justify-content: center; */
}
</style>
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is En Ci, a CS M.S. student at Nanjing University, supervised by [Ying Tai](https://tyshiwo.github.io/). I obtained my B.S. degree at Wuhan University, advised by [Zuchao Li](https://zcli-charlie.github.io/). My current research interest centers on AIGC(AI-Generated-Content) and MLLM(Multimodal Lagre Lanuage Model), including image generation/editing, unified understanding and generation. 

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
<li><em>2025.09:</em> 🎉 One paper was accepted by <strong>NeurIPS 2025</strong>.</li>
<li><em>2025.09:</em> 🎉 Commenced my M.S. journey at <strong>Nanjing University</strong>, expecting three years of fruitful research.</li>
<li><em>2025.06:</em> 🎉 One paper was accepted by <strong>ICCV 2025</strong>. See you in Hawaii!</li>
<li><em>2025.06:</em> 🎈 Recognized as an <strong>Outstanding Graduate</strong> of Wuhan University. I am deeply grateful for the four enriching years spent here!</li>
<li><em>2025.01:</em> 🎉 One paper was accepted by <strong>NAACL 2025</strong>.</li>
<li><em>2024.11:</em> 🎈 I was honored with <strong>Lei Jun Scholarship(Undergraduate)</strong>.</li>
<li><em>2023.10:</em> 🎈 I was honored with <strong>the National Scholarship</strong>(0.2% nation-wide). </li>

# 📝 Publications 
**\* Equal Contribution**   


<dl>
  <dt><img align="left" width="100"
hspace="10" wspace="20" src="../images/Ultra100K.png">
<span class="conference-label">NeurIPS 2025</span>
</dt>
  <dd><a href="https://arxiv.org/abs/"><strong>UltraHR-100K: Enhancing UHR Image Synthesis with A Large-Scale High-Quality Dataset</strong></a></dd>
  <dd>Chen Zhao<sup>*</sup>, <strong>En Ci<sup>*</sup></strong>, Yunzhe Xu<sup>*</sup>, Tiehan Fan, Shanyan Guan, Yanhao Ge, Jian Yang, Ying Tai</dd>
</dl>

<hr>

<dl>
  <dt><img align="left" width="100"
hspace="10" wspace="20" src="../images/DescribeEdit.png">
<span class="conference-label">ICCV 2025</span>
</dt>
  <dd><a href="https://arxiv.org/abs/2508.20505"><strong>Describe, Don't Dictate: Semantic Image Editing with Natural Language Intent</strong></a></dd>
  <dd><strong>En Ci<sup>*</sup></strong>, Shanyan Guan<sup>*</sup>, Yanhao Ge, Yilin Zhang, Wei Li, Zhenyu Zhang, Jian Yang, Ying Tai</dd>
</dl>

<hr>

<dl>
  <dt><img align="left" width="100"
hspace="10" wspace="20" src="../images/LDNet.png">
<span class="conference-label">NAACL 2025</span>
</dt>
  <dd><a href="https://arxiv.org/pdf/2502.12614"><strong>Label Drop for Multi-Aspect Relation Modeling in Universal Information
Extraction</strong></a></dd>
  <dd>Lu Yang, Jiajia Li, <strong>En Ci</strong>, Lefei Zhang, Zuchao Li, Ping Wang</dd>
</dl>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
<div class="education-card">
  <div class="education-info">
    <div class="education-title">
      <strong>2025.09 - Now</strong><br/>
      Master, Artificial Intelligence, Nanjing University 
    </div>
  </div>
  <div class="education-logo">
    <img src="../images/NJU.png" alt="Nanjing University Logo" />
  </div>
</div>

<div class="education-card">
  <div class="education-info">
    <div class="education-title">
      <strong>2021.09 - 2025.06</strong><br/>
      Bachelor, School of Computer Science, Wuhan University
    </div>
  </div>
  <div class="education-logo">
    <img src="../images/WHU.png" alt="Wuhan University Logo" />
  </div>
</div>


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
<div class="experience-card">
  <div class="experience-info">
    <div class="experience-title">
      <a href="https://vivo.com/">vivo, Shanghai</a>
    </div>
    <div class="experience-role">Internship, Assistant Algorithm Engineer, 2024.10 ~ </div>
    <!-- <div class="experience-topics">Topics: (M)LLM, GUI Agent</div> -->
  </div>
  <div class="experience-logo">
    <img src="../images/vivo.png" alt="vivo Logo" />
  </div>
</div>

<div class="globe-container">
    <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=0Rpqiq9n6R9WC3DYQXr0-QOKrEZyMTOAF6jyn-qaZ9E"></script>
</div>
