---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
  - /cv.html
---

{% include base_path %}

<p class="cv-updated">Last updated: Oct 2026</p>

## 🎓 Education

<div class="timeline">
  <div class="tl-item">
    <div class="tl-date">Aug 2023 – Dec 2024</div>
    <div class="tl-body">
      <div class="tl-title">University of Illinois Urbana-Champaign <span class="tag-uiuc">UIUC</span></div>
      <div class="tl-sub">M.Eng. in Electrical and Computer Engineering · Grainger College of Engineering</div>
      <div class="tl-loc">Urbana, Illinois, USA</div>
    </div>
  </div>
  <div class="tl-item">
    <div class="tl-date">Sep 2019 – Jul 2023</div>
    <div class="tl-body">
      <div class="tl-title">Peking University <span class="tag-pku">PKU</span></div>
      <div class="tl-sub">B.S. in Data Science · Yuanpei College</div>
      <div class="tl-loc">Beijing, China</div>
    </div>
  </div>
  <div class="tl-item">
    <div class="tl-date">Sep 2016 – Jul 2019</div>
    <div class="tl-body">
      <div class="tl-title">Affiliated Middle School of Henan Normal University</div>
      <div class="tl-loc">Xinxiang, Henan, China</div>
    </div>
  </div>
</div>

## 💼 Work Experience

<div class="timeline">
  <div class="tl-item">
    <div class="tl-date">Feb 2025 – Present</div>
    <div class="tl-body">
      <div class="tl-title">TikTok Inc. <a class="tag-tiktok" href="https://www.tiktok.com/about?lang=en">TikTok</a></div>
      <div class="tl-sub">Machine Learning Engineer · Data E-commerce Recommendation</div>
      <div class="tl-loc">San Jose, California, USA</div>
    </div>
  </div>
  <div class="tl-item">
    <div class="tl-date">May 2024 – Aug 2024</div>
    <div class="tl-body">
      <div class="tl-title">WeRide Corp <a class="tag-weride" href="https://www.weride.ai/">WeRide.ai</a></div>
      <div class="tl-sub">Software Engineer Intern · Perception Team (Camera / Object Detection)</div>
      <div class="tl-loc">San Jose, California, USA</div>
    </div>
  </div>
  <div class="tl-item">
    <div class="tl-date">Jun 2022 – Feb 2023</div>
    <div class="tl-body">
      <div class="tl-title">Alibaba (Beijing) Software Services Co., Ltd. <a class="tag-alibaba" href="https://www.alibabagroup.com/en-US/">Alibaba</a></div>
      <div class="tl-sub">Algorithm Engineer Intern · Alimama Advertising Technology Department</div>
      <div class="tl-loc">Beijing, China</div>
    </div>
  </div>
  <div class="tl-item">
    <div class="tl-date">Sep 2020 – Jan 2023</div>
    <div class="tl-body">
      <div class="tl-title">Machine Intelligence and Perception Laboratory <span class="tag-pku">PKU</span></div>
      <div class="tl-sub">Undergraduate Research Assistant · School of Intelligence Science and Technology</div>
      <div class="tl-loc">Beijing, China · Mentor: <a href="https://scholar.google.com.hk/citations?user=a832IIMAAAAJ&hl=en">Guojie Song</a></div>
    </div>
  </div>
</div>

## 📝 Publications

{% assign pubs = site.publications | sort: "date" | reverse %}
{% for post in pubs %}{% include pub-card.html %}{% endfor %}

## 🛠 Skills

<div class="chips">
  <span class="chip">Python</span>
  <span class="chip">C++</span>
  <span class="chip">PyTorch</span>
  <span class="chip">TensorFlow</span>
  <span class="chip">Graph Neural Networks</span>
  <span class="chip">Recommender Systems</span>
  <span class="chip">Object Detection</span>
</div>
