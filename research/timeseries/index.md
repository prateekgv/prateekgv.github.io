---
layout: single
author_profile: true
comments: false
title: false
---

#### Sparsity-assisted signal denoising and pattern recognition in time-series data
##### Background
Signal denoising and pattern recognition of time-series data are widely used in many scientific fields, including physics, engineering, medicine, economics, acoustics, biology, and psychology. For example, specific signal patterns in the electroencephalogram (EEG) data, which are useful in clinical diagnosis and cognitive neuroscience, are challenging to detect and distinguish from artifacts. In this work, we address the problem of signal denoising and pattern recognition in processing batch-mode time-series data by combining linear time-invariant filters, orthogonal multiresolution representations, and sparsity-based methods. For example, in the figure below, we decompose the original signal as the sum of a low-frequency signal, an oscillatory signal, and a discontinuous signal using our novel filter designs and proposed signal model.

<figure>
  <img src="figures/sasdpr.png"/>
  <figcaption>Decomposition of a noisy input signal into sum of a low-frequency signal, an oscillatory signal, and discontinuous signal using sparsity-assisted signal denoising and pattern recognition (SASDPR) approach.</figcaption>
</figure>

##### Our Research
In this work, we
* develop stable and non-sparse zero-phase IIR filters as matrices
* the order of the filter depends on the positive definiteness condition of the reachability and observability Gramians.
* filter response types include stable low-pass, high-pass, and band-pass filters.

To demonstrate various applications of our proposed filter designs, we
* develop a new signal model called sparsity-assisted signal denoising (SASD) by combining our proposed filter designs with the existing signal model. Because the zero-phase filters in the SASD signal model are stable, they demonstrate consistent results on changing the orders of the filter.
* propose and derive a new signal model called sparsity-assisted pattern recognition (SAPR). In SAPR, we combine LTI band-pass filters and sparsity-based methods with orthogonalmultiresolution representations, such as wavelets, to detect specific patterns in the input signal.
* combine the signal denoising and pattern recognition tasks, and derive a new signal model called the sparsity-assisted signal denoising and pattern recognition (SASDPR).

##### Publications
1. **G. V. Prateek**, Y-E. Ju, and A. Nehorai, "Sparsity-assited signal denoising and pattern recognition in time-series data," in _Circuits, Systems, and Signal Processing_, vol. 41, pp. 249–298, Jan. 2022. [\[<span style="color:blue">**link**</span>\]](https://rdcu.be/cnHD9) [\[<span style="color:blue">**code**</span>\]](https://github.com/prateekgv/sasdpr)