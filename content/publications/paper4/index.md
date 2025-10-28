---
title: "TIFIN at CheckThat! 2025: Cross-Lingual Subjectivity Classification in News through Monolingual, Multilingual, and Zero-Shot Learning"
date: 2025-09-12
tags: ["subjectivity classification", "fact-checking automation", "multilingual modeling", "cross-lingual generalization", "class imbalance mitigation"]
author: ["Kishan Gurumurthy", "Ashish Shrivastava", "Pawan Kumar Rajpoot", "Prasanna Devadiga", "Bharatdeep Hazarika", "Manish Jain", "Manan Sharma", "Arya Suneesh", "Anshuman B Suresh", "Aditya U Baliga"]
description: "A comprehensive approach to cross-lingual subjectivity classification using transformer-based models with resampling and class-weighting techniques, achieving strong performance across monolingual, multilingual, and zero-shot settings in five languages."
summary: "This paper presents TIFIN's solution for CheckThat! Lab CLEF 2025 Task 1, demonstrating effective subjectivity detection in news articles across Arabic, Bulgarian, English, German, and Italian through advanced multilingual modeling and class imbalance mitigation strategies."
---

##### Authors
Kishan Gurumurthy, Ashish Shrivastava, Pawan Kumar Rajpoot, Prasanna Devadiga, Bharatdeep Hazarika, Manish Jain, Manan Sharma, Arya Suneesh, Anshuman B Suresh, Aditya U Baliga

##### Abstract
In an age of widespread digital misinformation, the process of binary classification to differentiate subjective claims from objective reporting is crucial for building efficient automated fact-checking systems. This paper presents our approach for Task 1 of the CLEF 2025 CheckThat! Lab, which requires classifying text segments as either subjective or objective. The evaluation spans three settings-monolingual, multilingual, and zero-shot cross-lingual transfer-across five languages: Arabic, Bulgarian, English, German, and Italian. Our method leverages pretrained transformer-based language models that are fine-tuned specifically for subjectivity detection, with adaptations designed to enhance performance in multilingual and cross-lingual contexts. To address the issue of class imbalance present in the training data, we incorporate resampling and class-weighting techniques during model training, which significantly improve the identification of less frequent classes. Experimental results show consistent and strong performance across all evaluation settings, particularly in scenarios involving limited resources and unseen languages. Additionally, comprehensive error analysis is conducted to explore linguistic and contextual influences on classification accuracy. These results demonstrate the importance of robust multilingual modeling approaches in subjectivity detection and their contribution to advancing automated fact-checking and the promotion of reliable information dissemination.

##### Paper Link
[View Paper on CEUR-WS](https://ceur-ws.org/Vol-4038/paper_72.pdf)

##### Citation
```BibTeX
@inproceedings{gurumurthy2025tifin,
  title={TIFIN at CheckThat! 2025: Cross-Lingual Subjectivity Classification in News through Monolingual, Multilingual, and Zero-Shot Learning},
  author={Gurumurthy, Kishan and Shrivastava, Ashish and Rajpoot, Pawan Kumar and Devadiga, Prasanna and Hazarika, Bharatdeep and Jain, Manish and Sharma, Manan and Suneesh, Arya and Suresh, Anshuman B and Baliga, Aditya U},
  booktitle={CLEF 2025 Working Notes},
  pages={9--12},
  year={2025},
  month={September},
  address={Madrid, Spain},
  publisher={CEUR-WS},
  volume={4038},
  url={https://ceur-ws.org/Vol-4038/paper_72.pdf}
}
```
