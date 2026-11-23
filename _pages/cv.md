---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download my resume [here](https://yqwang01.github.io/files/Resume_Yiqing_En.pdf).

## Education

* **Duke University**, Durham, North Carolina, USA, 2023 -\
  Ph.D. Candidate, Vision and Image Processing Lab, Department of Biomedical Engineering
  * GPA: 3.84/4.0
  * See more on my [transcript](https://yqwang01.github.io/files/OfficialTranscript_DUKEU_20260222.pdf)

* **Shanghai Jiao Tong University (SJTU)**, Shanghai, China, 2019 - 2023\
  Bachelor's Degree of Engineering, major in Biomedical Engineering, minor in Computer Science and Engineering
  * GPA: 3.84/4.3 (Top 10%)
  * See more on my [final transcript](https://yqwang01.github.io/files/Final_Transcript.jpg)

## Scholar experience

**Jun. 2026 - Sep. 2026**: United Imaging Intelligence directed by Boris Mailhé and Shanhui Sun

  3D Vision Language Model for CT Report Generation
  * **Finding-level recognition**: Decomposed chest CT reports into 93 clinical findings and built a uNexus 3D CNN recognizer with global–local CLIP-style image–text pretraining, achieving state-of-the-art finding recognition on CT-RATE.
  * **Grounded generation**: Built a Qwen3-VL-8B report generator that uses a finding classifier to choose which findings to report and localizes anatomy with 3D boxes as a chain-of-thought step. It then writes and assembles one sentence per finding.
  * **RL optimization**: Refined the generator with GRPO on a composite factuality/NLG reward, outperforming four published baselines on CT-RATE.
  * A paper in preparation (expected in Jan. 2027)

**Aug. 2023 - Present**: VIP Lab @ Duke directed by Sina Farsiu

  PRIMA: Pre-training with Risk-integrated Image-Metadata Alignment for Medical Diagnosis via LLM
  * **Knowledge-enhanced encoding**: elevate structured metadata into semantic knowledge by injecting RAG-derived risk--disease priors into a clinical text encoder, without requiring massive paired datasets.
  * **Multi-granular alignment**: Introduce complementary objectives that align images, textual priors, and metadata-derived semantics at global and local levels.
  * **LLM-driven diagnosis**: Develop a unified pipeline that uses LLM to synthesize metadata-aligned image features and knowledge-pretrained text features, achieving strong performance on both dermatology and keratitis datasets.
  * An abstract accepted as an **Oral Presentation** at *ARVO 2026*, a full paper submitted to *CVPR 2027* and available on arXiv.

  A Multi-Granularity Language Learning Approach to Boost Visual Understanding
  * **Multi-Granular contrastive learning**: Proposed a contrastive learning framework with multi-granular objectives that enables joint multi-label and cross-granularity alignment for medical image understanding, improving representation consistency across hierarchical label structures.
  * **Large-Scale medical image-Text datasets**: Constructed large-scale retinal and X-ray image-text datasets to facilitate systematic evaluation across diverse label granularities.
  * Demonstrated strong performance across multiple benchmarks; accepted by *ICLR 2026*.

  An Automated Quantitative Ulcer Analysis (AQUA) Algorithm for Microbial Keratitis Organism Classification
  * Proposed a contrastive learning-based approach to extract robust representations across heterogeneous clinical data patterns.
  * Developed a three-stage multimodal framework integrating imaging, metadata, and clinical features for organism-type classification.
  * An article submitted to *Ophthalmology*.

**Jun. 2022 – Nov. 2022**: CCVL @ JHU directed by Alan Yuille & VLAA @ UCSC directed by Yuyin Zhou & Cihang Xie
  
  Multi-view MAE for 3D medical image representation learning
  * **Masked Multi-View Self-Supervised Learning**: Proposed SwinMM, a masked multi-view self-supervised learning framework for data-efficient 3D medical image representation learning, addressing the scarcity of large-scale medical pre-training data.
  * **Cross-View Attention Decoder**: Designed a masked multi-view encoder with diverse proxy tasks and a cross-view decoder with cross-attention to exploit cross-view consistency and aggregate latent multi-view information from 3D volumes.
  * **Data-Efficient 3D Segmentation**: Achieved superior segmentation performance and improved data efficiency compared to Swin UNETR.
  * Published in *MICCAI 2023* (Oral Presentation).

**Feb. 2022 – Jan. 2023**: Advanced MRI Lab @ SJTU directed by Hongjiang Wei
  
  Brain Region Segmentation and Age Estimation Using QSM
  * Developed a novel segmentation network for key brain regions on QSM images to support brain age estimation.
  * Improved brain age prediction accuracy compared to prior T1-weighted MRI-based approaches.
  * Published in ISMRM 2023 and IEEE Journal of Biomedical and Health Informatics (JBHI).

## Publications

## 2026

**Y Wang**, MA Woodward, Z Yang, NV Prajna, C He, LM Niziol, ... & S Farsiu. Multimodal Knowledge Aggregation for Microbial Keratitis: Geographic Confounding and Shortcut Risk in Pooled Multicountry Data. _ArXiv:2607.03740._ 

**Y Wang**, C He, MC Lu, M Pawar, L Niziol, M Woodward, S Farsiu. PRIMA: Pre-training with Risk-integrated Image-Metadata Alignment for Medical Diagnosis via LLM. _ArXiv:2602.23297._ 

Z Li<sup>1</sup>, **Y Wang<sup>1</sup>**, S Farsiu, P Kinahan. Boosting Medical Visual Understanding From Multi-Granular Language Learning. *The Fourteenth International Conference on Learning Representations (ICLR)*.

B Guo, X Chen, B Mailhe, J Yao, **Y Wang**, A Mukherjee, Y Liu, Z Zhang, H Yu, T Chen, S Sun. Learning Where to Look: Anatomical Grounding and Guided Attention for Cardiac MRI Vision-Language Models. _ArXiv:2609.39899_.

C He, D Zhang, F Xiao, X Guo, J Feng, **Y Wang**, S Farsiu. Toward Multimodal Understanding in Low-Level Vision: The Rise of Vision-Language Models. _Preprints 2026, 2026061854._ 

**Y Wang**, C He, LM Niziol, M Pawar, M Lu, MA Woodward, & S Farsiu. Large-Language-Model-Enhanced Multi-Modal Subtype Diagnosis of Microbial Keratitis on Slit-Lamp Photographs and Metadata. *Association for Research in Vision and Ophthalmology (ARVO) 2026 Annual Meeting*.

Z Li<sup>1</sup>, **Y Wang<sup>1</sup>**, S Farsiu, P Kinahan. Large‑scale data harmonization of radiology studies via multigranular vision‑language alignment. *SPIE Medical Imaging 2026.* 

J Ong, MC Lu, C Thanitcul, M Pawar, JN Hart, EL Vogt, C Deng, S Farsiu, **Y Wang**, P Dmitriev, A Gupta. Deep Learning-Based Classification of Slit-Lamp Photograph Quality in Microbial Keratitis. *Ophthalmology Science.* 2026 Jan 21:101086. 

## 2025

EL Vogt, LM Niziol, Z Yang, **Y Wang**, M Pawar, P Dmitriev, ... & MA Woodward. Association of deep learning imaging algorithm measures of microbial keratitis with vision outcomes. _Cornea_, pp.10-1097. 

J Ong, M Lu, C Thanitcul, M Pawar, JN Hart, E Vogt, S Farsiu, **Y Wang**, ... & MA Woodward. Automated Deep Learning Classification of the Quality of Slit-Lamp Photographs of Microbial Keratitis. _Investigative
Ophthalmology & Visual Science_, 66(8), 4436-4436. 

Z Yang, MA Woodward, LM Niziol, M Pawar, NV Prajna, A Krishnamoorthy, **Y Wang**, M Lu, S Selvaraj, & S Farsiu. Self-knowledge distillation-empowered directional connectivity transformer for microbial keratitis biomarkers segmentation on slit-lamp photography. *Medical Image Analysis*, 102, 103533.

## 2023

M Chen<sup>1</sup>, **Y Wang<sup>1</sup>**, Y Shi<sup>1</sup>, J Feng, R Feng, X Guan, ... & H Wei. Brain Age Prediction Based on Quantitative Susceptibility Mapping Using the Segmentation Transformer. *IEEE Journal of Biomedical and Health Informatics*.

**Y Wang<sup>1</sup>**, Z Li<sup>1</sup>, J Mei<sup>1</sup>, Z Wei<sup>1</sup>, L Liu, C Wang, ... & Y Zhou. SwinMM: Masked Multi-view with Swin Transformers for 3d Medical Image Segmentation. *2023 International Conference on Medical Image Computing and Computer-Assisted Intervention.* (pp. 486-496). Cham: Springer Nature Switzerland. 

**Y Wang**, Y Shi, H Wei. A Brain Age Estimation Network based on QSM using the Segment Transformer. *2023 International Society for Magnetic Resonance in Medicine (ISMRM)*. 

## Awards

* 2026 Duke Graduate School \& BME Department Travel Grants
* 2026 Oral Presentation at ARVO 2026
* 2026 Imaging Informatics Best Paper Award Runner Up at SPIE Medical Imaging 2026
* 2023 Oral Presentation at MICCAI 2023
* 2023 Outstanding Graduate of Shanghai Jiao Tong University (Top 5%)
* 2022 Scholarship of School of Biomedical Engineering Alumni Association
* 2022 Merit Student of Shanghai Jiao Tong University (Top 3%)
* 2021 Shanghai Municipal Government Scholarship (Top 1%)
* 2020 Class A Scholarship of Shanghai Jiao Tong University (Top 1%)

## Service

* **Conference Reviewer**   MICCAI 2026; MICCAI 2025; MICCAI 2024;
* **Journal Reviewer**   IEEE Journal of Biomedical \& Health Informatics (JBHI); IEEE Transactions on Medical Imaging (TMI); Image and Vision Computing; ACM Transactions on Computing for Healthcare; Frontiers In Neuro Informatics;
* **Teaching Assistant**  BME790 Intro to AI for BME;


<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
 -->
