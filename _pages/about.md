---
permalink: /
title: "Dongchen Xie"
author_profile: true
header: false  # 新增：关闭主题自带的头部标题栏
redirect_from: 
  - /about/
  - /about.html
---

<!-- 修复后的CSS：只隐藏主题自动生成的标题，保留手动的About Me -->
<style>
  /* 1. 只隐藏主题自动生成的标题容器（不影响正文里的h1） */
  .page-header, .masthead, .site-header, .header-title-container {
    display: none !important;
  }
  /* 2. 隐藏主题自动生成的独立标题元素（排除带aboutme锚点的） */
  h1:not([id="aboutme"]):not(.manual-title) {
    display: none !important;
  }
  /* 3. 确保手动写的标题正常显示（兜底） */
  #aboutme, #Publications, #Honors and Awards {
    display: block !important;
    visibility: visible !important;
  }
</style>

<!-- 给手动标题加类名，确保不被隐藏 -->
<h1 id="aboutme" class="manual-title">About Me (<a href=".../assets/CV-Dongchen_Xie.pdf">CV</a>)</h1>
<hr style="border: 0; border-top: 1px solid #ddd; margin: 10px 0;">
Hi! I am Dongchen, coming from Hubei, China.

Fortunately, I will be a Ph.D. student supervised by [Prof. Heqing Huang](https://5hadowblad3.github.io/) in the Department of Computer Science (CS), [City University of Hong Kong (CityU)](https://www.cityu.edu.hk/) from Fall 2026.

I'm currently a second-year postgraduate student at the School of Cyber Science and Engineering (CSE), [Wuhan University (WHU)](https://www.whu.edu.cn/).  I received my Bachelor's degree from the School of Cyber Science and Technology (CST), [Shandong University (SDU)](https://cst.qd.sdu.edu.cn/) in 2024.

It is my honor to be advised by [Prof. Xiaoyuan Xie](https://xiaoyuanxie.github.io/) from the School of Computer Science, WHU. My research interests include, but are not limited to, software security and large language models, especially using AI to tackle some software issues (e.g., patch localization, bug-inducing commit identification).

<h1 id="Publications" class="manual-title">Publications</h1>
<hr style="border: 0; border-top: 1px solid #ddd; margin: 10px 0;">

<span style="white-space: nowrap; display: inline-block;">
  <span style="background-color: #0052cc; color: white; padding: 2px 6px; border-radius: 2px;">ASE 2025</span> [**Not Every Patch is an Island: LLM-Enhanced Identification of Multiple Vulnerability Patches**](https://ieeexplore.ieee.org/document/11334340)
</span>
<br> <span style="font-size: 0.8em;"><u>Yi Song</u>, <u><strong>Dongchen Xie</strong></u>, <u>Lin Xu</u>, He Zhang, Chunying Zhou, Xiaoyuan Xie*</span> 
<br> <span style="font-size: 0.8em;"><span style="color: red;">🏆 ACM SIGSOFT Distinguished Paper Award </span></span>

<span style="font-size: 0.8em;">( __ co-first author，&ensp;</span> <span style="font-size: 0.8em;">* corresponding author )</span>

<h1 id="Honors and Awards" class="manual-title">Honors and Awards</h1>
<hr style="border: 0; border-top: 1px solid #ddd; margin: 10px 0;">

  🥇<span style="font-size: 0.8em;color: red;">一等奖</span>&ensp;**“华为杯”第四届中国研究生网络安全创新大赛**&ensp;<span style="font-size: 0.8em;">Dec. 2025</span>

  🏆<span style="font-size: 0.8em;color: red;">ACM SIGSOFT Distinguished Paper Award</span>&ensp;**40th IEEE/ACM International Conference on ASE**&ensp;<span style="font-size: 0.8em;">Nov. 2025</span>

  🥇<span style="font-size: 0.8em;color: red;">一等奖</span>&ensp;**第七届CCF开源创新大赛**&ensp;<span style="font-size: 0.8em;">Nov. 2024</span>
  
  🥉<span style="font-size: 0.8em;color: red;">三等奖</span>&ensp;**山东大学漏洞挖掘天梯赛**&ensp;<span style="font-size: 0.8em;">May. 2024</span>
