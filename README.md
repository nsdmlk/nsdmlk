<div align="center">
  <img src="img/kg.jpeg" width="100%" style="border-radius: 5px; filter: grayscale(100%) contrast(120%);" alt="Kanterville Ghost">
</div>

<br>

<div align="center">

  <sub>☾ &nbsp; MACHINE LEARNING &nbsp; · &nbsp; RESEARCH &nbsp; · &nbsp; PYTHON &nbsp; ☾</sub>
  
  <br>
  
  <a href="https://github.com/nsdmlk"><img src="https://img.shields.io/badge/GITHUB-000000?style=flat-square&logo=github&logoColor=white"></a>
  <a href="https://t.me/KantervilleGhost"><img src="https://img.shields.io/badge/TELEGRAM-000000?style=flat-square&logo=telegram&logoColor=white"></a>
  <a href="mailto:nsdmlk@yandex.ru"><img src="https://img.shields.io/badge/EMAIL-000000?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://pypi.org/user/KantervilleGhost/"><img src="https://img.shields.io/badge/PYPI-000000?style=flat-square&logo=pypi&logoColor=white"></a>
  <a href="https://orcid.org/0009-0002-6802-7544"><img src="https://img.shields.io/badge/ORCID-000000?style=flat-square&logo=orcid&logoColor=white"></a>

<br>

---

<br>

<!-- ═══════════════ ABOUT ═══════════════ -->
<div align="center">
  <h3><i>between mathematics & machines</i></h3>
</div>

<div align="justify">
  <p>CS student at <b>Beijing Institute of Technology</b>. I research how models learn when data is scarce, focusing on <b>small-sample learning</b>, <b>conformal prediction</b>, and <b>reinforcement learning</b>.</p>
  
  <p>I build open-source libraries that bridge the gap between theoretical guarantees and practical implementations — from robust gradient boosting to calibrated neural networks.</p>
</div>

<br>

---

<br>

<!-- ═══════════════ PROJECTS ═══════════════ -->
<div align="center">
  <h3><i>Selected Works</i></h3>
</div>

<br>

> **Ⅰ. Small Data Machine Learning (Paper)**
> *The Trilemma of Low-Sample Tabular Regimes*
> 
> The theoretical foundation of Small Data. Formalizes the "Trilemma of Small Data" (variance, bias, and uncertainty under validation depletion) and evaluates the exact scaling boundaries where standard models fail.
> 
> <a href="https://arxiv.org/abs/2611.30118"><img src="https://img.shields.io/badge/ARXIV-2611.30118-000000?style=flat-square&logo=arxiv&logoColor=white"></a>
> <a href="https://doi.org/10.48550/arXiv.2611.30118"><img src="https://img.shields.io/badge/DOI-10.48550/arXiv.2611.30118-000000?style=flat-square&logo=doi&logoColor=white"></a>
> <a href="https://github.com/nsdmlk/SmallData-Trilemma"><img src="https://img.shields.io/badge/PAPER_REPO-000000?style=flat-square&logo=github&logoColor=white"></a>

<br>

> **Ⅱ. SmallGBM**
> *Robust gradient boosting for tabular data (n < 1000)*
> 
> Replaces fragile mean-based second-order Taylor approximations with robust median leaf estimation. Built with a native C core (256-bin histograms) for 2-3x faster training.
> 
> `Outperforms XGBoost and LightGBM on 22 small datasets`
> `Limits AUC degradation to 3.7x less than XGBoost under 20% label corruption`
> 
> <a href="https://github.com/nsdmlk/SmallGBM"><img src="https://img.shields.io/badge/SOURCE-000000?style=flat-square&logo=github&logoColor=white"></a>
> <a href="https://pypi.org/project/smallgbm/"><img src="https://img.shields.io/badge/PYPI-000000?style=flat-square&logo=pypi&logoColor=white"></a>
> <a href="https://pepy.tech/projects/smallgbm"><img src="https://static.pepy.tech/personalized-badge/smallgbm?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREY&left_text=downloads" alt="Downloads"></a>
> <a href="https://github.com/YDX-2147483647/best-of-bits"><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/YDX-2147483647/best-of-bits/main/config/badge/v1.json" alt="Best of BITs"></a>

<br>

> **Ⅲ. SmallMLP**
> *Adaptive neural networks with calibrated conformal intervals (n < 500)*
> 
> Eliminates manual architecture search by deriving layer width and dropout directly from dataset geometry. Produces prediction intervals with finite-sample coverage guarantees.
> 
> `Best mean rank among 10 models on 18 datasets (zero-tuning)`
> `Produces 19% narrower intervals than split conformal at equal coverage`
> 
> <a href="https://github.com/nsdmlk/SmallMLP"><img src="https://img.shields.io/badge/SOURCE-000000?style=flat-square&logo=github&logoColor=white"></a>
> <a href="https://pypi.org/project/smallmlp/"><img src="https://img.shields.io/badge/PYPI-000000?style=flat-square&logo=pypi&logoColor=white"></a>
> <a href="https://pepy.tech/projects/smallmlp"><img src="https://static.pepy.tech/personalized-badge/smallmlp?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREY&left_text=downloads" alt="Downloads"></a>
> <a href="https://github.com/YDX-2147483647/best-of-bits"><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/YDX-2147483647/best-of-bits/main/config/badge/v1.json" alt="Best of BITs"></a>

<br>

> **Ⅳ. RL-from-scratch**
> *Value-based reinforcement learning*
> 
> Implementing algorithms from first principles to understand the mechanics behind agents, rather than treating them as black boxes.
> 
> `DQN` | `Double DQN` | `Dueling DQN`
> 
> <a href="https://github.com/nsdmlk/RL-from-scratch"><img src="https://img.shields.io/badge/SOURCE-000000?style=flat-square&logo=github&logoColor=white"></a>

<br>

---

<br>

<!-- ═══════════════ TECH STACK ═══════════════ -->
<div align="center">
  <h3><i>Arsenal</i></h3>
  <br>
  <img src="https://skillicons.dev/icons?i=python,pytorch,c,docker,fastapi,git,linux,bash,latex&perline=15" alt="Tech Stack" />
</div>

<br>

---

<br>

<!-- ═══════════════ STATS ═══════════════ -->
<!-- <div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nsdmlk&show_icons=true&theme=dark&bg_color=000000&border_color=222222&icon_color=ffffff&title_color=ffffff&text_color=aaaaaa&hide_rank=true&hide_title=true" width="400" />
</div> -->

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=UnifrakturMaguntia&size=20&duration=5000&pause=2500&color=FFFFFF&center=true&vCenter=true&lines=there+is+always+another+experiment." alt="Footer">
  <br>
  <sub>☾ &nbsp; BEIJING · CHINA · 2026 &nbsp; ☾</sub>
</div>
