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

<br>
😎😎 **Welcome to my personal website!** 😎😎

I am Wenyu Li, you can also call me Wind. I am now a final year undergraduate of South China University of Technology at Guangzhou, China, and you can find my CV [here](/WenyuLi_CV.pdf).

My research has primarily centered on information retrieval and text comprehension, leveraging advanced NLP techniques to bridge interdisciplinary domains. As I deepen my exploration of Large Language Models (LLMs), my goal is to expand my research to encompass a broader spectrum of LLM applications, moving beyond the realms of information understanding and retrieval. 

<strong><span style="color:red; font-size:larger;">I will join Westlake NLP group as a Phd student supervised by [Prof. Yue Zhang](https://frcchang.github.io/) in 2025 fall!</span></strong>
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🔥 News
- *2024.12*: &nbsp;🎉🎉 I will start my research internship at Tencent!
- *2024.10*: &nbsp;🎉🎉 Our paper *Generating Diverse Criteria On-the-Fly to Improve Pointwise LLM Rankers* has been <span style="color:red;">accepted by The 18th ACM International Conference on Web Search and Data Mining (WSDM) 2025</span> as Main Conference Paper!
- *2024.09*: &nbsp;🎉🎉 <span style="color:red;">I have been admitted as a PhD student at Westlake University (with the highest score in the interview)!</span>
- *2024.05*: &nbsp;🎉🎉 I go to Singapore and attend The Web Conference 2024 on site!
- *2024.06*: &nbsp;🎉🎉 I will start a new journey visiting [Prof. Zhiyuan Liu](https://nlp.csai.tsinghua.edu.cn/~lzy/) at Tsinghua University!
- *2024.03*: &nbsp;🎉🎉 My first paper *Zero-shot Explainable Mental Health Analysis on Social Media by Incorporating Mental Scales* has been <span style="color:red;">accepted by The Web Conference (WWW) 2024</span>!
- *2023.07*: &nbsp;🎉🎉 I will start visiting [Prof. Yue Zhang](https://frcchang.github.io/) at Westlake University!
- *2023.06*: &nbsp;🎉🎉 I have been granted my first [China patent](https://patents.google.com/patent/CN110413126B/en?oq=CN110%2c413%2c126+B)!
- *2023.05*: &nbsp;🎉🎉 Our project *"Design of a Depression Risk Assessment System Based on Psychological Scales and AIGC Large Models"* secured a National Project Approval under the China College Students' Innovation and Entrepreneurship Training Program!
- *2023.03*: &nbsp;🎉🎉 Get the Future Innovation Award of Future Technology Taihu Innovation Award <span style="color:red;">(Top 3%)</span>!
- *2023.03*: &nbsp;🎉🎉 Get the First class Science and Technology Innovation Award of Future Technology Taihu Innovation Award <span style="color:red;">(Top 3%)</span>!
- *2023.01*: &nbsp;🎉🎉 Get the First Prize of Asia and Pacific Mathematical Contest in Modeling (APMCM) <span style="color:red;">(Top 5%)</span>!
- *2022.01*: &nbsp;🎉🎉 Our project *"Depression Tendency Analysis Chatbot Based on WeChat Official Accounts"* secured a Guangdong Province Science and Technology Innovation Strategic Special Fund Project!

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WSDM 2025</div><img src='images/COLM24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generating Diverse Criteria On-the-Fly to Improve Pointwise LLM Rankers](https://arxiv.org/abs/2404.11960)

Fang Guo\*, **Wenyu Li\***, Honglei Zhuang, Yun Luo, Yafu Li, Qi Zhu, Le Yan, Yue Zhang (\* equal contribution)
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->
- We propose to build a ranker that generates ranking scores based on a set of criteria from various perspectives. These criteria are intended to direct each perspective in providing a distinct yet synergistic evaluation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2024 Short</div><img src='images/WWW24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Zero-shot Explainable Mental Health Analysis on Social Media by Incorporating Mental Scales](https://arxiv.org/abs/2402.10948)

**Wenyu Li**, Yinuo Zhu, Xin Lin, Ming Li, Ziyue Jiang, Ziqian Zeng

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->
- Inspired by the psychological assessment practice of using scales to evaluate mental states, we propose MAIMS (Mental Analysis by Incorporating Mental Scales), incorporates two procedures via LLMs. First, the patient completes mental scales, and then the psychologist interprets the collected information from the mental scales and makes informed decisions.
</div>
</div>

- LisaQA: An Attributed QA Benchmark for Literature Search, ACL 2025 (Under Review)<br>F. Guo\*, **Wenyu Li\***, Y. Zhang

- Depression Risk Assessment Method and System Based on Psychological Scales and AIGC Large Models, China patent, Application Number: 2024103834530 (Under review)<br>**Wenyu Li**, Ming Li, Yinuo Zhu, Xin Lin, Jinghao You, Ziyue Jiang


- [Wearable device based on arm somatosensory interaction technology](https://patents.google.com/patent/CN110413126B/en?oq=CN110%2c413%2c126+B), China Patent, CN110413126B<br>**Wenyu Li**


# 🎖 Honors and Awards
- *2024.10*:&nbsp;  Third-Class South China University of Technology Scholarship. 
- *2023.11*:&nbsp;  Third-Class South China University of Technology Scholarship. 
- *2023.03*:&nbsp;  Future Innovation Award, Future Technology Taihu Innovation Award by Wuxi government.
- *2023.03*:&nbsp;  First-class Science and Technology Innovation Award, Future Technology Taihu Innovation Award by Wuxi government, .
- *2023.03*:&nbsp;  Third-class Academic Innovation Award, Future Technology Taihu Innovation Award by Wuxi government.
- *2023.01*:&nbsp;  First Prize, Asia and Pacific Mathematical Contest in Modeling.
- *2022.11*:&nbsp;  Third-Class South China University of Technology Scholarship.
- *2022.11*:&nbsp;  Third-class TCL Enterprise Donated Scholarship.

# 📖 Educations
- *2021.06 - present*, South China University of Technology, Bachelor's degree.

# 🎓 Social Service
- Reviewer: WWW 2024, IJCAI 2024, JSCT
- Volunteer: NLPCC 2024 (Hangzhou, China)

<!--
# 💬 Social Service
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Researches
- *2024.12 - 2025.03*, Internship, working on role-playing ability of MLLM (especially audio LLM), supervised by [Dr. Xiaoqi Jiao]([https://nlp.csai.tsinghua.edu.cn/~lzy/](https://scholar.google.com/citations?user=VryvpBgAAAAJ&hl)), **Tencent**, Shenzhen, China.
- *2024.06 - 2024.09*, Visitor, working on personalised human-bot dialogue system, supervised by [Prof. Zhiyuan Liu](https://nlp.csai.tsinghua.edu.cn/~lzy/), **Tsinghua University**, Beijing, China.
- *2023.07 - present*, Visiting Student, working on using LLMs to give a new solution to information retrieval, supervised by [Prof. Yue Zhang](https://frcchang.github.io/), **Westlake University**, Hangzhou, China.
- *2022.09 - 2023.06*, Working on the design of a depression risk assessment system based on psychological scales and AIGC large models, surpervised by Principal Researcher Mo Yu, **WeChat AI, Tecent**, China.
- *2019.10 - 2020.11*, Working on a wearable device based on somatic interaction technology, supervised by Dr. Yadong Li, **University of Science and Technology of China**, Hefei, China.

# 🩴 My Interesting Life
- *2023.02*, **I cycled around Hainan Island in nine days, about 850 KM**, there is also a [video](https://www.bilibili.com/video/BV14e4y1P7o7/?vd_source=87867a0ba7d93f723755287cbc2e89fd) to record this.<br>
<div style="display:flex; justify-content:center; align-items:flex-start; flex-wrap:wrap;">
  <img src="images/cycle1.png" alt="Cycling around Hainan" title="Cycling around Hainan" width="330"/>&nbsp;&nbsp;&nbsp;
  <img src="images/cycle2.png" alt="Cycling around Hainan" title="Cycling around Hainan" width="330"/>
</div>

<br>

- *2022.10*, **I starred in a drama, which received an overwhelming response and received reports from Guangdong Province**<br>
<div style="display:flex; justify-content:center; align-items:flex-start; flex-wrap:wrap;">
  <img src="images/drama1.png" alt="Starring in a drama" title="Starring in a drama" width="445"/>&nbsp;&nbsp;&nbsp;
  <img src="images/drama2.png" alt="Starring in a drama" title="Starring in a drama" width="200"/>
</div>
<br>

- **I like football and travelling, especially with my friends and girlfriend.**<br>
<div id="slider" style="width: 900px; overflow: hidden; margin-left: 56px;">
    <div id="slider-inner">
        <img src="images/1.png" alt="Image 1">
        <img src="images/2.png" alt="Image 2">
        <img src="images/3.png" alt="Image 3">
        <img src="images/4.png" alt="Image 4">
        <img src="images/5.png" alt="Image 5">
        <img src="images/6.png" alt="Image 6">
        <img src="images/7.png" alt="Image 7">
        <img src="images/8.png" alt="Image 8">
        <img src="images/9.png" alt="Image 9">
        <img src="images/10.png" alt="Image 10">
        <img src="images/11.png" alt="Image 11">
        <img src="images/12.png" alt="Image 12">
        <img src="images/14.png" alt="Image 14">
    </div>
</div>

<script>
var slider = document.getElementById('slider');
var sliderInner = document.getElementById('slider-inner');
var images = sliderInner.getElementsByTagName('img');
var totalWidth = 0;
var currentOffset = 0;
var animationSpeed = 1;

// 计算所有图片的总宽度
function calculateTotalWidth() {
    totalWidth = Array.from(images).reduce((acc, img) => acc + img.offsetWidth + 10, 0); // 加上margin的宽度
}

// 动态移动图片以实现无限滚动
function cycleImages() {
    var firstImageWidth = images[0].offsetWidth + 10; // 加上margin的宽度

    if (currentOffset >= firstImageWidth) {
        sliderInner.appendChild(images[0]); // 将第一张图片移动到最后
        currentOffset -= firstImageWidth; // 调整当前偏移量
        sliderInner.style.transform = 'translateX(-' + currentOffset + 'px)';
    }
}

// 更新滚动动画
function updateAnimation() {
    currentOffset += animationSpeed;
    sliderInner.style.transform = 'translateX(-' + currentOffset + 'px)';
    cycleImages(); // 检查是否需要循环图片
    requestAnimationFrame(updateAnimation);
}

// 初始化
calculateTotalWidth();
requestAnimationFrame(updateAnimation);

// 当窗口大小变化时重新计算宽度
window.addEventListener('resize', calculateTotalWidth);
</script>

<style>
#slider img {
    max-height: 280px;
    height: auto;
    min-width: 100px; /* 根据实际情况调整 */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border: 1px solid #ddd;
    margin-right: 10px; /* 增加间距 */
    border-radius: 10px; /* 圆角边框 */
    flex-shrink: 0;
}

#slider-inner {
    display: flex;
    align-items: center;
    transition: none; /* 移除过渡效果以避免移动时的跳动 */
}

@keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(calc(-1 * var(--totalWidth))); }
}

#slider img:hover {
    transform: scale(1.50); /* 鼠标悬停时放大 */
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2); /* 鼠标悬停时增加阴影 */
}

/* 如果图片未加载，显示一个简单的加载动画 */
#slider img:not([src]), 
#slider img:empty {
    min-width: 100px;
    background: linear-gradient(130deg, #e6e9f0 0%, #eef1f5 50%, #e6e9f0 100%);
    background-size: 200% 100%;
    animation: loadingAnimation 1s infinite;
}

@keyframes loadingAnimation {
    0% { background-position: 100% 0; }
    100% { background-position: 0 0; }
}
</style>

<br>
<div style="width: 500px; height: 500px; margin: auto;"> <!-- 设置您想要的宽度和高度 -->
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=UC6ibAca1Av5EPZP3WPd9Xzwv1J1pzlCFAfXYn0DNqI"></script>
</div>
<br>
