 <div align="center">


<svg width="1200" height="320" viewBox="0 0 1200 320" fill="none" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1200" y2="320">
      <stop stop-color="#101512"/>
      <stop offset="1" stop-color="#080B09"/>
    </linearGradient>

    <linearGradient id="green" x1="0" y1="0" x2="1" y2="1">
      <stop stop-color="#A3FFB0"/>
      <stop offset="1" stop-color="#36C66B"/>
    </linearGradient>

    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0H0V40" stroke="#8BA997" stroke-opacity="0.09"/>
    </pattern>

    <filter id="glow">
      <feGaussianBlur stdDeviation="5"/>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="320" fill="url(#bg)"/>
  <rect width="1200" height="320" fill="url(#grid)"/>

  <!-- Decorative glow -->
  <circle cx="1010" cy="145" r="130" fill="#36C66B" opacity="0.07" filter="url(#glow)"/>

  <!-- Top label -->
  <text x="76" y="64" fill="#6D9B7B"
        font-family="monospace" font-size="13" letter-spacing="4">
    MIHIR SHARMA / DEVELOPER PROFILE
  </text>

  <!-- Main name -->
  <text x="72" y="155" fill="#E7F0E9"
        font-family="Arial, Helvetica, sans-serif"
        font-size="68" font-weight="bold" letter-spacing="-2">
    MIHIR SHARMA
  </text>

  <!-- Green underline -->
  <rect x="77" y="178" width="90" height="4" rx="2" fill="url(#green)"/>

  <!-- Description -->
  <text x="77" y="222" fill="#A9B7AC"
        font-family="monospace" font-size="17">
    DATA SCIENCE  /  AI SYSTEMS  /  ENGINEERING
  </text>

  <text x="77" y="258" fill="#668271"
        font-family="monospace" font-size="13">
    Building, researching and experimenting with intelligent systems.
  </text>

  <!-- Right terminal panel -->
  <rect x="850" y="70" width="275" height="175" rx="10"
        fill="#111A14" stroke="#355440" stroke-opacity="0.7"/>

  <rect x="850" y="70" width="275" height="32" rx="10" fill="#1B2920"/>
  <circle cx="870" cy="86" r="4" fill="#6BCB85"/>
  <circle cx="885" cy="86" r="4" fill="#77847A"/>
  <circle cx="900" cy="86" r="4" fill="#77847A"/>

  <text x="870" y="130" fill="#78C98B"
        font-family="monospace" font-size="13">
    $ whoami
  </text>

  <text x="870" y="153" fill="#E0EAE2"
        font-family="monospace" font-size="13">
    mihir_sharma
  </text>

  <text x="870" y="185" fill="#78C98B"
        font-family="monospace" font-size="13">
    $ interests
  </text>

  <text x="870" y="207" fill="#A9B7AC"
        font-family="monospace" font-size="11">
    AI / ML / LLM / FINANCE
  </text>

  <!-- Bottom line -->
  <path d="M0 292H1200" stroke="#365442" stroke-opacity="0.5"/>

  <text x="77" y="312" fill="#587461"
        font-family="monospace" font-size="10" letter-spacing="2">
    THINK  ·  BUILD  ·  ITERATE
  </text>

  <text x="1120" y="312" fill="#587461"
        font-family="monospace" font-size="10" text-anchor="end">
    EST. 2026
  </text>

</svg>

</div>

---

## About Me

I'm a Data Science undergraduate interested in understanding how intelligent systems work beyond the application layer.

My interests lie at the intersection of **machine learning, LLM infrastructure, data engineering, and systems optimization**. I enjoy exploring technical problems, experimenting with different approaches, and building projects that connect theoretical concepts with practical applications.

Currently, I'm focusing on:

- Understanding LLM inference and prefix caching.
- Exploring cache-aware routing and retrieval systems.
- Building practical machine learning applications.
- Strengthening my foundations in programming, algorithms, and data systems.

---

## Current Research & Engineering

### CacheRag

**Cache-Aware Routing and Prefix Caching for Efficient LLM Inference**

[![Repository](https://img.shields.io/badge/Explore_Repository-238636?style=flat&logo=github&logoColor=white)](https://github.com/mihirsharma1824/CacheRag)

LLM inference can involve repeatedly processing shared prompt prefixes across requests. CacheRag explores how prefix caching and cache-aware request routing can reduce redundant computation and improve inference-serving efficiency.

**Areas of exploration**

- **Prefix Caching:** Reusing previously computed prompt-prefix states where compatible.
- **Cache-Aware Routing:** Investigating request placement based on cache locality and availability.
- **Performance Evaluation:** Studying cache hit rate, time-to-first-token, throughput, and response latency.

*Status: Research and prototyping.*

---

## Featured Projects

### Samudra Setu

**Satellite-Based Oil Spill Detection & Vessel Attribution**

[![Project](https://img.shields.io/badge/Explore_Project-238636?style=flat&logo=github&logoColor=white)](https://github.com/Samudra-Setu)

An AI-powered system designed to identify potential marine oil spills using Sentinel-1 SAR satellite imagery and correlate detected incidents with AIS vessel movement data.

**Key components**

- SAR imagery preprocessing and oil-spill classification.
- Machine learning-based detection of potential oil-spill regions.
- AIS trajectory analysis and spatial-temporal correlation.
- Candidate vessel ranking using proximity and movement patterns.
- Dashboard for visualizing detections and vessel information.

*The system generates candidate vessel associations for investigation, not legally conclusive attribution.*

---

## Technologies & Tools

**Programming Languages**

![C](https://img.shields.io/badge/C-555555?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-555555?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-555555?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-555555?style=flat&logo=mysql&logoColor=white)

**Machine Learning & Backend**

![PyTorch](https://img.shields.io/badge/PyTorch-555555?style=flat&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-555555?style=flat&logo=fastapi&logoColor=white)

**Databases & Development Tools**

![MySQL](https://img.shields.io/badge/MySQL-555555?style=flat&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-555555?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-555555?style=flat&logo=docker&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-555555?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-555555?style=flat&logo=css3&logoColor=white)

---

## Currently Exploring

- LLM serving and inference optimization
- Prefix caching and cache-aware scheduling
- Retrieval-Augmented Generation (RAG)
- Machine learning research and experimentation
- Data structures and algorithms

---

## Contribution Arcade

<div align="center">

**A little Pac-Man to keep the contributions moving.**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mihirsharma1824/mihirsharma1824/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mihirsharma1824/mihirsharma1824/output/pacman-contribution-graph.svg">
  <img alt="Pac-Man contribution graph" src="https://raw.githubusercontent.com/mihirsharma1824/mihirsharma1824/output/pacman-contribution-graph.svg" width="100%">
</picture>

</div>

---

<div align="center">

### Let's build something meaningful.

Interested in connecting with engineers, researchers, and people building interesting things in AI, machine learning, and systems engineering.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mihirsharma1824)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mihirsharma24)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:238636&height=100&section=footer" width="100%" />

</div>
