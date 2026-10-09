---
permalink: /
browser_title: "Dongchen Xie"
author_profile: false
header: false
redirect_from:
  - /about/
  - /about.html
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@500;600;700&family=Noto+Serif+SC:wght@400;500;600&display=swap');
  html, body { background-color: #fff !important; }
  .masthead { position: sticky; background: rgba(255, 255, 255, .96); backdrop-filter: blur(12px); }
  .masthead::after { background: #e2eaf0; }
  .masthead__inner-wrap { max-width: 1080px; }
  .masthead__menu { width: 100%; }
  .masthead__menu .academic-nav { display: flex; width: 100%; align-items: center; justify-content: space-between; }
  .academic-nav-home { color: #4b5257; font-size: 18px; font-weight: 700; text-decoration: none; }
  .academic-nav-links { display: flex; align-items: center; gap: 24px; }
  .academic-nav-links a { color: #505b63; font-size: 12px; text-decoration: none; }
  .academic-nav-links a:hover { color: #28728a; }
  .masthead__menu-item--lg { padding-right: 2.1em; font-weight: 700; }
  .page { max-width: 1080px; }
  .page__content { padding-top: 2.5em; }
  .academic-home { color: #303941; font-family: 'DM Sans', Arial, sans-serif; font-size: 13px; }
  .academic-hero { display: grid; grid-template-columns: minmax(0, 1fr) 190px; gap: 44px; align-items: center; padding: 26px 28px; border-radius: 18px; background: #fff; }
  .academic-kicker, .academic-date, .academic-venue { color: #657782; font-family: 'DM Mono', Consolas, monospace; letter-spacing: .015em; }
  .academic-kicker { font-size: 10px; text-transform: uppercase; letter-spacing: .09em; }
  .academic-date, .academic-venue { font-size: 12px; }
  .academic-name { margin: .28em 0 .18em; color: #202a31; font-family: 'Playfair Display', Georgia, serif; font-size: 48px; font-weight: 600; letter-spacing: -.035em; line-height: 1.05; }
  .academic-name { white-space: nowrap; }
  .academic-name .cn-name { color: #74818a; font-family: 'Noto Serif SC', 'Songti SC', SimSun, serif; font-size: .58em; font-weight: 500; letter-spacing: 0; white-space: nowrap; vertical-align: .08em; }
  .academic-affiliation { margin: .5em 0 1em; color: #65727a; font-size: 15px; }
  .academic-links { display: flex; flex-wrap: wrap; gap: 9px; }
  .academic-links a { padding: 7px 11px; border: 1px solid #d5dde1; border-radius: 999px; color: #435d6b; font-size: 11px; text-decoration: none; }
  .academic-links a:hover { border-color: #647f8d; background: #f5f8f9; }
  .academic-links .academic-like { display: inline-flex; align-items: center; gap: 5px; padding: 7px 11px; border: 1px solid #d5dde1; border-radius: 999px; background: #fff; color: #435d6b; font: inherit; font-size: 11px; line-height: 1.4; cursor: pointer; }
  .academic-links .academic-like:hover { border-color: #d69aa2; background: #fffafa; }
  .academic-like .like-heart { width: 15px; height: 15px; flex: 0 0 15px; fill: transparent; stroke: #6f7d84; stroke-width: 2.2; stroke-linecap: round; stroke-linejoin: round; transition: fill .18s ease, stroke .18s ease, transform .18s ease; }
  .academic-like[aria-pressed="true"] { border-color: #edc8cd; }
  .academic-like[aria-pressed="true"] .like-heart { fill: #e58e9b; stroke: #e58e9b; transform: scale(1.08); }
  .academic-like:disabled { cursor: default; opacity: .7; }
  .academic-portrait { display: block; width: 190px; height: 190px; border: 1px solid #dce4e5; border-radius: 50%; background: #edf1f2; box-shadow: 0 8px 24px #21364212; object-fit: contain; object-position: center; }
  .academic-section { margin-top: 38px; scroll-margin-top: 78px; }
  .academic-section h2 { margin: 0 0 16px; padding-bottom: .5em; border-bottom: 1px solid #dce3e5; color: #27333a; font-family: 'DM Sans', Arial, sans-serif; font-size: 17px; font-weight: 600; }
  .academic-bio { color: #52616a; font-size: 13px; line-height: 1.8; }
  .academic-row { display: grid; grid-template-columns: 145px minmax(0, 1fr); gap: 18px; align-items: start; margin: 15px 0; font-size: 12px; line-height: 1.65; }
  .academic-date { white-space: nowrap; color: #597380; font-family: 'DM Mono', Consolas, monospace; font-size: 12px; font-weight: 500; letter-spacing: 0; }
  #publication { overflow-x: auto; }
  .academic-pub { width: max-content; min-width: 100%; grid-template-columns: 145px max-content; margin: 17px 0; }
  .academic-pub-title { font-size: 13px; font-weight: 700; white-space: nowrap; }
  .academic-meta { color: #59666e; font-size: 11px; line-height: 1.7; }
  .academic-status { color: #77858b; font-size: 10px; font-weight: 400; }
  .academic-award-badge { display: inline-block; margin-top: 5px; padding: 3px 8px; border-radius: 5px; background: #f6eddb; color: #946623; font-size: 10px; font-weight: 500; line-height: 1.5; }
  .page__content p.academic-notes { margin: 10px 0 0 163px; color: #77858b; font-size: 10px; line-height: 1.5; }
  .academic-award-emphasis { color: #202a31; font-weight: 700; }
  .academic-award-row { display: grid; grid-template-columns: 145px minmax(0, 1fr); gap: 18px; margin: 12px 0; font-size: 12px; line-height: 1.7; }
  .academic-teaching { white-space: nowrap; overflow-x: auto; }
  @media (max-width: 700px) {
    .page__content { padding-top: 1.4em; }
    .academic-hero { grid-template-columns: minmax(0, 1fr) 108px; gap: 14px; align-items: start; padding: 20px 16px; }
    .academic-portrait { width: 108px; height: 108px; margin-top: 10px; }
    .academic-name { font-size: clamp(19px, 5.5vw, 32px); }
    .academic-name .cn-name { font-size: .55em; }
    .academic-affiliation { font-size: 13px; }
    .academic-row, .academic-award-row { grid-template-columns: 112px minmax(0, 1fr); gap: 10px; font-size: .92em; }
    .page__content p.academic-notes { margin-left: 122px; }
    .academic-nav-home { font-size: 15px; }
    .academic-nav-links { gap: 8px; }
    .academic-nav-links a { font-size: 10px; }
  }
  @media (max-width: 430px) {
    .academic-hero { grid-template-columns: minmax(0, 1fr) 76px; gap: 10px; padding: 18px 12px; }
    .academic-portrait { width: 76px; height: 76px; }
    .academic-name { font-size: clamp(17px, 5vw, 21px); letter-spacing: -.04em; }
    .academic-name .cn-name { font-size: .52em; }
  }
</style>

<div class="academic-home">
  <header class="academic-hero">
    <div>
      <div class="academic-kicker">PH.D. STUDENT · COMPUTER SCIENCE</div>
      <h1 class="academic-name">Dongchen Xie <span class="cn-name">(谢东辰)</span></h1>
      <p class="academic-affiliation">CityU · Software Security &amp; LLM</p>
      <div class="academic-links">
        <a href="https://scholar.google.com/citations?user=N6o4bLQAAAAJ&amp;hl=zh-CN">Google Scholar ↗</a>
        <a href="https://github.com/xxxxdc">GitHub ↗</a>
        <a href="mailto:dongchxie3-c@my.cityu.edu.hk">Email ↗</a>
        <button class="academic-like" id="homepage-like" type="button" aria-pressed="false" aria-label="Like this homepage">
          <svg class="like-heart" aria-hidden="true" viewBox="0 0 24 24"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78Z"/></svg><span>Likes</span><span id="homepage-like-count" aria-live="polite">…</span>
        </button>
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
    <div class="academic-award-row"><div class="academic-date">2025.12</div><div><strong>一等奖</strong>　“华为杯”第四届中国研究生网络安全创新大赛</div></div>
    <div class="academic-award-row"><div class="academic-date">2025.11</div><div><strong>ACM SIGSOFT Distinguished Paper Award</strong>　40th IEEE/ACM International Conference on ASE</div></div>
    <div class="academic-award-row"><div class="academic-date">2024.11</div><div><strong>一等奖</strong>　第七届CCF开源创新大赛</div></div>
    <div class="academic-award-row"><div class="academic-date">2024.05</div><div><strong>三等奖</strong>　山东大学漏洞挖掘天梯赛</div></div>
  </section>
</div>

<script>
  (() => {
    const button = document.getElementById('homepage-like');
    const count = document.getElementById('homepage-like-count');
    if (!button || !count) return;

    const counterGetUrl = 'https://countapi.mileshilliard.com/api/v1/get/xxxxdc-homepage-likes-39988de32a5a4b55bc7edcf04e05204d';
    const counterHitUrl = 'https://countapi.mileshilliard.com/api/v1/hit/xxxxdc-homepage-likes-39988de32a5a4b55bc7edcf04e05204d';
    const storageKey = 'xxxxdc-homepage-liked-v3';
    const liked = () => {
      try { return localStorage.getItem(storageKey) === '1'; }
      catch (_) { return false; }
    };
    const setLiked = value => {
      button.setAttribute('aria-pressed', value ? 'true' : 'false');
    };
    const showCount = value => {
      const safeValue = Number.isFinite(Number(value)) ? Number(value) : 0;
      count.textContent = safeValue.toLocaleString();
      button.setAttribute('aria-label', `Like this homepage, ${count.textContent} likes`);
    };

    setLiked(liked());
    fetch(counterGetUrl, { cache: 'no-store' })
      .then(response => response.ok ? response.json() : Promise.reject())
      .then(data => showCount(data.value));

    button.addEventListener('click', async () => {
      if (liked() || button.disabled) return;
      button.disabled = true;
      try {
        const response = await fetch(counterHitUrl, { cache: 'no-store' });
        if (!response.ok) throw new Error('Could not record this like');
        const data = await response.json();
        showCount(data.value);
        try { localStorage.setItem(storageKey, '1'); } catch (_) {}
        setLiked(true);
      } catch (_) {
        button.setAttribute('aria-label', 'Like counter is temporarily unavailable');
      } finally {
        button.disabled = false;
      }
    });
  })();
</script>
