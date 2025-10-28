---
title: "TIFIN at CheckThat! 2025: Reasoning-Guided Claim Normalization for Noisy Multilingual Social Media Posts"
date: 2025-09-12
tags: ["claim normalization", "misinformation detection", "multilingual NLP", "social media analysis", "fact-checking"]
author: ["Manan Sharma", "Arya Suneesh", "Manish Jain", "Pawan Kumar Rajpoot", "Prasanna Devadiga", "Bharatdeep Hazarika", "Ashish Shrivastava", "Kishan Gurumurthy", "Anshuman B Suresh", "Aditya U Baliga"]
description: "A reasoning-guided approach to claim normalization using 5W1H decomposition and Qwen3-14B fine-tuning, achieving 41.3% relative improvement in METEOR scores over baseline configurations across 20 languages."
summary: "This paper presents TIFIN's solution for CheckThat! Lab CLEF 2025 Task 2, demonstrating how systematic decomposition using Who, What, Where, When, Why and How questions enables robust cross-lingual transfer for transforming noisy social media posts into clear, verifiable statements."
---

##### Authors
Manan Sharma, Arya Suneesh, Manish Jain, Pawan Kumar Rajpoot, Prasanna Devadiga, Bharatdeep Hazarika, Ashish Shrivastava, Kishan Gurumurthy, Anshuman B Suresh, Aditya U Baliga

##### Abstract
We address claim normalization for multilingual misinformation detection - transforming noisy social media posts into clear, verifiable statements across 20 languages. The key contribution demonstrates how systematic decomposition of posts using Who, What, Where, When, Why and How questions enables robust cross-lingual transfer despite training exclusively on English data. Our methodology incorporates finetuning Qwen3-14B using LoRA with the provided dataset after intra-post deduplication, token-level recall filtering for semantic alignment and retrieval-augmented few-shot learning with contextual examples during inference. Our system achieves METEOR scores ranging from 41.16 (English) to 15.21 (Marathi); securing third rank on the English leaderboard and fourth rank for Dutch and Punjabi. The approach shows 41.3% relative improvement in METEOR over baseline configurations and substantial gains over existing methods. Results demonstrate effective cross-lingual generalization for Romance and Germanic languages while maintaining semantic coherence across diverse linguistic structures.

##### Paper Link
[View Paper on CEUR-WS](https://ceur-ws.org/Vol-4038/paper_95.pdf)

##### Citation
```BibTeX
@inproceedings{sharma2025tifin,
  title={TIFIN at CheckThat! 2025: Reasoning-Guided Claim Normalization for Noisy Multilingual Social Media Posts},
  author={Sharma, Manan and Suneesh, Arya and Jain, Manish and Rajpoot, Pawan Kumar and Devadiga, Prasanna and Hazarika, Bharatdeep and Shrivastava, Ashish and Gurumurthy, Kishan and Suresh, Anshuman B and Baliga, Aditya U},
  booktitle={CLEF 2025 Working Notes},
  pages={9--12},
  year={2025},
  month={September},
  address={Madrid, Spain},
  publisher={CEUR-WS},
  volume={4038},
  url={https://ceur-ws.org/Vol-4038/paper_95.pdf}
}
```
