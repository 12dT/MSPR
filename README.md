# MSPR: Multi-stage Semantic-Guided Prompt Reasoning for Multimodal Sentiment Analysis

Official implementation of **MSPR**, a multi-stage framework for multimodal sentiment analysis that models affect understanding progressively through **Tone**, **Content**, and **Emotion**.



## Introduction

Multimodal sentiment analysis requires joint reasoning over textual and visual cues. 
However, sentiment is often implicit and progressively constructed, rather than directly observable from one-step multimodal fusion.

MSPR addresses this problem with a three-stage framework:

- **Tone**: captures perceptual cues such as color, illumination, and overall atmosphere
- **Content**: models semantic entities, scenes, and interactions
- **Emotion**: performs higher-level affective interpretation

To support this progressive reasoning process, MSPR introduces:

1. **Hierarchical caption supervision** for stage-wise semantic guidance
2. **Prototype-centered prompt interaction** for cross-modal affect transfer
3. **Dual-path contrastive alignment** for structured affective representation learning

## Framework Overview

<p align="center">
  <img src="figures/framework.pdf" width="85%">
</p>

The source code will be released publicly upon acceptance of the corresponding paper. This repository currently serves as a placeholder for reference and linkage purposes.

Thank you for your interest.
