---
permalink: /
title: "Homepage"
author_profile: false
header: false
redirect_from:
  - /about/
  - /about.html
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@500;600;700&family=Noto+Serif+SC:wght@400;500;600&display=swap');
  html, body { background-color: #f8fbfe !important; }
  .masthead { position: sticky; background: rgba(244, 249, 253, .94); backdrop-filter: blur(12px); }
  .masthead::after { background: #e2eaf0; }
  .masthead__inner-wrap { max-width: 1080px; }
  .masthead__menu .greedy-nav { background: transparent; }
  .masthead__menu .greedy-nav .visible-links { display: flex; width: 100%; align-items: center; gap: .35rem; }
  .masthead__menu .greedy-nav .visible-links > li { display: block; }
  .masthead__menu .greedy-nav .visible-links > li:first-child { margin-right: auto; }
  .masthead__menu-item--lg { padding-right: 2.1em; font-weight: 700; }
  .page { max-width: 1080px; }
  .page__content { padding-top: 2.5em; }
  .academic-home { color: #303941; font-family: 'DM Sans', Arial, sans-serif; font-size: 13px; }
  .academic-hero { display: grid; grid-template-columns: minmax(0, 1fr) 220px; gap: 44px; align-items: center; padding: 26px 28px; border-radius: 18px; background: linear-gradient(115deg, rgba(222, 237, 250, .48), rgba(237, 246, 253, .22)); }
  .academic-kicker, .academic-date, .academic-venue { color: #657782; font-family: 'DM Mono', Consolas, monospace; letter-spacing: .015em; }
  .academic-kicker { font-size: 10px; text-transform: uppercase; letter-spacing: .09em; }
  .academic-date, .academic-venue { font-size: 12px; }
  .academic-name { margin: .28em 0 .18em; color: #202a31; font-family: 'Playfair Display', Georgia, serif; font-size: 48px; font-weight: 600; letter-spacing: -.035em; line-height: 1.05; }
  .academic-name .cn-name { color: #74818a; font-family: 'Noto Serif SC', 'Songti SC', SimSun, serif; font-size: 1em; font-weight: 500; letter-spacing: 0; white-space: nowrap; }
  .academic-affiliation { margin: .5em 0 1em; color: #65727a; font-size: 15px; }
  .academic-links { display: flex; flex-wrap: wrap; gap: 9px; }
  .academic-links a { padding: 7px 11px; border: 1px solid #d5dde1; border-radius: 999px; color: #435d6b; font-size: 11px; text-decoration: none; }
  .academic-links a:hover { border-color: #647f8d; background: #f5f8f9; }
  .academic-portrait { display: block; width: 220px; height: 220px; border: 1px solid #dce4e5; border-radius: 50%; background: #edf1f2; box-shadow: 0 8px 24px #21364212; object-fit: cover; object-position: center 25%; }
  .academic-section { margin-top: 38px; scroll-margin-top: 78px; }
  .academic-section h2 { margin: 0 0 16px; padding-bottom: .5em; border-bottom: 1px solid #dce3e5; color: #27333a; font-family: 'Playfair Display', Georgia, serif; font-size: 18px; font-weight: 600; }
  .academic-bio { color: #52616a; font-size: 13px; line-height: 1.8; }
  .academic-row { display: grid; grid-template-columns: 145px minmax(0, 1fr); gap: 18px; align-items: start; margin: 15px 0; font-size: 12px; line-height: 1.65; }
  .academic-date { white-space: nowrap; font-weight: 700; }
  #publication { overflow-x: auto; }
  .academic-pub { width: max-content; min-width: 100%; grid-template-columns: 145px max-content; margin: 17px 0; }
  .academic-pub-title { font-size: 13px; font-weight: 700; white-space: nowrap; }
  .academic-meta { color: #59666e; font-size: 11px; line-height: 1.7; }
  .academic-status { color: #77858b; font-size: 10px; }
  .academic-award-badge { display: inline-block; margin-top: 5px; padding: 3px 8px; border-radius: 5px; background: #f6eddb; color: #946623; font-size: 10px; font-weight: 500; line-height: 1.5; }
  .page__content p.academic-notes { margin: 10px 0 0 163px; color: #77858b; font-size: 10px; line-height: 1.5; }
  .academic-award-emphasis { color: #202a31; font-weight: 700; }
  .academic-award-row { display: grid; grid-template-columns: 145px minmax(0, 1fr); gap: 18px; margin: 12px 0; font-size: 12px; line-height: 1.7; }
  .academic-teaching { white-space: nowrap; overflow-x: auto; }
  @media (max-width: 700px) {
    .page__content { padding-top: 1.4em; }
    .academic-hero { grid-template-columns: minmax(0, 1fr) 118px; gap: 14px; align-items: start; padding: 20px 16px; }
    .academic-portrait { width: 118px; height: 118px; margin-top: 10px; }
    .academic-name { font-size: clamp(25px, 6vw, 36px); }
    .academic-affiliation { font-size: 13px; }
    .academic-row, .academic-award-row { grid-template-columns: 112px minmax(0, 1fr); gap: 10px; font-size: .92em; }
    .page__content p.academic-notes { margin-left: 122px; }
  }
</style>

<div class="academic-home">
  <header class="academic-hero">
    <div>
      <div class="academic-kicker">PH.D. STUDENT · COMPUTER SCIENCE</div>
      <h1 class="academic-name">Dongchen Xie <span class="cn-name">(谢东辰)</span></h1>
      <p class="academic-affiliation">Software Security &amp; LLM</p>
      <div class="academic-links">
        <a href="https://scholar.google.com/citations?user=N6o4bLQAAAAJ&amp;hl=zh-CN">Google Scholar ↗</a>
        <a href="https://github.com/xxxxdc">GitHub ↗</a>
        <a href="mailto:dongchxie3-c@my.cityu.edu.hk">Email ↗</a>
      </div>
    </div>
    <img class="academic-portrait" src="/images/dongchen-xie-portrait.png" alt="Dongchen Xie">
  </header>

  <section class="academic-section" id="about">
    <h2>About</h2>
    <p class="academic-bio">Welcome to my homepage! I am a first-year Ph.D. student in Computer Science at <a href="https://www.cityu.edu.hk/">City University of Hong Kong</a>, supervised by Prof. <a href="https://5hadowblad3.github.io/">Heqing Huang</a>. I received my M.Eng. degree from <a href="https://www.whu.edu.cn/">Wuhan University</a> in 2026, under the supervision of Prof. <a href="https://xiaoyuanxie.github.io/">Xiaoyuan Xie</a>.</p>
    <p class="academic-bio">My research interests include, but are not limited to, software security and large language models, especially using AI to tackle some software issues.</p>
  </section>

  <section class="academic-section" id="education">
    <h2>Education</h2>
    <div class="academic-row"><div class="academic-date">2026.09 – Now</div><div><strong>Ph.D. in Computer Science</strong><br>Department of Computer Science, City University of Hong Kong</div></div>
    <div class="academic-row"><div class="academic-date">2024.09 – 2026.06</div><div><strong>M.Eng. in Electronic Information</strong><br>School of Cyber Science and Engineering, Wuhan University</div></div>
    <div class="academic-row"><div class="academic-date">2020.09 – 2024.06</div><div><strong>B.Eng. in Cyberspace Security</strong><br>School of Cyber Science and Technology, Shandong University</div></div>
  </section>

  <section class="academic-section" id="publication">
    <h2>Publication</h2>
    <article class="academic-row academic-pub"><div class="academic-date">FSE 2027<br><span class="academic-status">Under Review</span></div><div><div class="academic-pub-title">COMPASS: Predicting the Relationship of Multiple Patches for Vulnerabilities with LLMs</div><div class="academic-meta">Yi Song<sup>†</sup>, <strong>Dongchen Xie<sup>†</sup></strong>, Xiaoyuan Xie<sup>*</sup>, He Zhang, Lin Xu, Chunying Zhou</div></div></article>
    <article class="academic-row academic-pub"><div class="academic-date">ASE 2025</div><div><div class="academic-pub-title"><a href="https://ieeexplore.ieee.org/document/11334340">Not Every Patch is an Island: LLM-Enhanced Identification of Multiple Vulnerability Patches</a></div><div class="academic-meta">Yi Song<sup>†</sup>, <strong>Dongchen Xie<sup>†</sup></strong>, Lin Xu<sup>†</sup>, He Zhang, Chunying Zhou, Xiaoyuan Xie<sup>*</sup><br><span class="academic-award-badge">★ ACM SIGSOFT Distinguished Paper Award</span></div></div></article>
    <p class="academic-notes">† Co-first authors · * Corresponding author</p>
  </section>

  <section class="academic-section" id="teaching">
    <h2>Teaching</h2>
    <div class="academic-row"><div class="academic-date">Fall 2026</div><div class="academic-teaching">TA · CS2311 Computer Programming</div></div>
  </section>

  <section class="academic-section" id="award">
    <h2>Award</h2>
    <div class="academic-award-row"><div class="academic-date">Dec. 2025</div><div><strong>一等奖</strong>　“华为杯”第四届中国研究生网络安全创新大赛</div></div>
    <div class="academic-award-row"><div class="academic-date">Nov. 2025</div><div><strong>ACM SIGSOFT Distinguished Paper Award</strong>　40th IEEE/ACM International Conference on ASE</div></div>
    <div class="academic-award-row"><div class="academic-date">Nov. 2024</div><div><strong>一等奖</strong>　第七届CCF开源创新大赛</div></div>
    <div class="academic-award-row"><div class="academic-date">May. 2024</div><div><strong>三等奖</strong>　山东大学漏洞挖掘天梯赛</div></div>
  </section>
</div>
