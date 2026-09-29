---
title: ""
layout: single
permalink: /
author_profile: false
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
#   overlay_image: /images/particles.jpg
excerpt: #"Soft Disentanglement in Frequency Bands for Neural Audio Codecs"
---

Welcome to this demo website, in which we display examples of reconstructions / inpaintings we obtained thanks to the model introduced in the paper "Soft Disentanglement in Frequency Bands for Neural Audio Codecs", that has been submitted to EUSIPCO 2025. These excerpts are displayed in [Audio Examples](./audio.md). The code used to train and evaluate the model is available on [GitHub](https://github.com/Soft-Disentangled-Codec/Soft-Disentangled-Codec).

# Abstract

<html>
<div style="text-align: justify">
<p>
In neural-based audio feature extraction, ensuring that representations capture disentangled information is crucial for model interpretability. However, existing disentanglement methods often rely on assumptions that are highly dependent on data characteristics or specific tasks. In this work, we introduce a generalizable approach for learning disentangled features within a neural architecture. Our method applies spectral decomposition to time-domain signals, followed by a multi-branch audio codec that operates on the decomposed components. Empirical evaluations demonstrate that our approach achieves better reconstruction and perceptual performance compared to a state-of-the-art baseline while also offering potential advantages for inpainting tasks.
</p>

</div>
</html>

*Index Terms - Neural Audio Codec, Disentanglement, Frequency Decomposition, Inpainting*

# Code

The implementation of the codec, together with the training and evaluation scripts and the configurations used in the paper, is available at [https://github.com/Soft-Disentangled-Codec/Soft-Disentangled-Codec](https://github.com/Soft-Disentangled-Codec/Soft-Disentangled-Codec). It is built on the [Descript Audio Codec](https://github.com/descriptinc/descript-audio-codec) implementation.

[View the code on GitHub](https://github.com/Soft-Disentangled-Codec/Soft-Disentangled-Codec){: .btn .btn--primary}
