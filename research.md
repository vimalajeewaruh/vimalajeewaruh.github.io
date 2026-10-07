---
title: Research
page_key: research
description: "Research directions in multiscale statistical inference, wavelet learning, self-similarity, and interdisciplinary data science."
permalink: /research/
---

<section class="page-hero">
  <p class="kicker">01 / Research</p>
  <h1>Statistical methods for<br><em>structure across scales.</em></h1>
  <p>My research develops theory and computational tools for signals whose information is distributed across time, frequency, resolution, and context.</p>
</section>

<section class="content-section research-detail" id="multiscale-inference">
  <div class="detail-number">01</div>
  <div markdown="1">
    <p class="kicker">Inference</p>
    <h2>Multiscale statistical inference</h2>
    <p>Wavelet representations separate a complex signal into interpretable resolution levels. I use those levels as building blocks for likelihood-based, Bayesian, robust, and composite-likelihood inference. This work is motivated by a practical need: quantify dependence and uncertainty without requiring an unrealistic full covariance model for every observation.</p>

    **Current methodological interests**

    - Bayesian inference for wavelet-domain summary statistics
    - Composite likelihood and Laplace approximations
    - Robust multiscale estimation under contamination
    - Finite-sample uncertainty and diagnostic measures
  </div>
</section>

<section class="content-section research-detail" id="wavelet-learning">
  <div class="detail-number">02</div>
  <div markdown="1">
    <p class="kicker">Learning</p>
    <h2>Wavelet learning and signal recovery</h2>
    <p>Classical wavelet shrinkage often treats each coefficient as an isolated number. My work studies methods that also use scale, location, neighboring coefficients, and tree structure. The goal is to preserve interpretable wavelet representations while allowing modern learning systems to recognize contextual patterns.</p>

    **Current methodological interests**

    - Machine-learning-integrated shrinkage
    - SCOPE families of smooth shrinkage rules
    - Wavelet-aware attention and transformer models
    - Generalization across signal and noise families
  </div>
</section>

<section class="content-section research-detail" id="self-similarity">
  <div class="detail-number">03</div>
  <div markdown="1">
    <p class="kicker">Scaling</p>
    <h2>Fractality, self-similarity, and the Hurst exponent</h2>
    <p>The Hurst exponent summarizes long-range dependence and self-similar behavior. I develop wavelet-based estimators that remain informative in short, noisy, and non-ideal data settings. These methods include level-pair energy ratios, noise corrections, robust aggregation, and probabilistic inference.</p>

    **Current methodological interests**

    - ALPHEE and noise-corrected ALPHEE
    - Local and time-varying Hurst estimation
    - Fractal and multifractal signal descriptors
    - Scaling-based features for statistical learning
  </div>
</section>

<section class="content-section research-detail" id="interdisciplinary">
  <div class="detail-number">04</div>
  <div markdown="1">
    <p class="kicker">Collaboration</p>
    <h2>Interdisciplinary data science</h2>
    <p>Methodological questions become most meaningful when they are tested against real scientific constraints. I collaborate across biomedical science, agriculture, food systems, neuroscience, environmental science, and engineering, adapting multiscale tools to the data-generating mechanism rather than treating every dataset alike.</p>

    [Explore application areas →]({{ '/applications/' | relative_url }}){: .text-link }
  </div>
</section>
