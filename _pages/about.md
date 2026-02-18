---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
I'm a PhD student at the AIM lab at Harvard Medical School and Brigham and Women's Hospital focused on developing deep learning models for healthcare applications with [Benjamin Kann, MD](https://www.dana-farber.org/find-a-doctor/benjamin-h-kann) and [Dr. Hugo Aerts](https://scholar.google.com/citations?user=v7G4QvIAAAAJ&hl=en) `. My work includes building generalized and tumor specific Brain MRI vision foundation models, and deep-learning brain tumor prognosis tools currently being used in clinical trials.

My research interests lie in computer vision, self-supervised learning, and vision-language alignment, with a focus on deployment in clinical settings. 

Before transitioning into healthcare AI, I worked on the development of the AI perception stack for autonomous driving with [Dr. Harry Chao](https://sites.google.com/view/wei-lun-harry-chao/home?authuser=0) at The Ohio State University for [SAE AutoDrive 2](https://www.sae.org/attend/student-events/autodrive-challenge-series2) Year 1. And before transitioning to Autonomous driving, I worked on the development of electrical and software stack for autonomous robots for Team India (2018) as a part of the yearly [ABU Robocon](https://aburobocon2025.mnb.mn/en) challenge. 

Outside of work, I love to play soccer and follow MMA.

&nbsp;
# 📰 News
- *2026.02*: &nbsp;🚀 BrainIAC-Platform is now live for public and research use! [Try it here](https://brainiac-platform.com)
- *2026.02*: &nbsp;🎉📝 BrainIAC - A foundation model for generalized Brain MRI analysis [paper](https://www.nature.com/articles/s41593-026-02202-6) is now published in Nature Neuroscience  
- *2025.05*: &nbsp;🎉📝 Our [Blogpost](https://mathematical-oncology.org/blog/gbm-predictions.html) on integtation of deep-learning with mechanistic filters and SINDY for GBM reccurance predicton is out on Mathematical Oncology
- *2025.04*: &nbsp;🎉📝 Our [paper](https://ai.nejm.org/doi/full/10.1056/AIoa2400703) on predicting recurrence risk in pediatric gliomas using longitudinal deep learing was published in NEJM AI
- *2025.01*: &nbsp; BrainIAC - A Generalized Brain MRI foundation model [preprint](https://www.medrxiv.org/content/10.1101/2024.12.02.24317992v1) is out! 
- *2024.03*: &nbsp;🎉📝 Our [paper](https://pubs.rsna.org/doi/full/10.1148/ryai.230333) on perdicting BRAF Mutation status for pediatric glioma using deep learning was published on the cover of Radiology AI 

&nbsp;

# 📝 Publications 

### BrainIAC - Generalized Vision Foundation Model for Brain MRI
- `Nature Neuroscience` D Tak *et al.* [(https://www.nature.com/articles/s41593-026-02202-6]) 

### Longitudinal Risk Prediction for Pediatric Glioma with Temporal Deep Learning
- `NEJM AI` D Tak *et al.* (https://ai.nejm.org/doi/full/10.1056/AIoa2400703) 

### Noninvasive Molecular Subtyping of Pediatric Low-Grade Glioma with Self-Supervised Transfer Learning
- `Radiology AI` D Tak et al. (https://pubs.rsna.org/doi/full/10.1148/ryai.230333) 

### Path Tracing in Holonomic Drive System with Reduced Overshoot using Rotary Encoders 
- `IEEE SPIN` D Tak *et al.* (https://ieeexplore.ieee.org/abstract/document/9071196) 


&nbsp;
# 🚀 BrainIAC-Platform

[BrainIAC-Platform](https://brainiac-platform.com) is the first an open-source hub hosting deep learning models for Brain MRI analysis. 

Currently available models on the platform include:
- BrainIAC backbone (T1, T1CE, T2, T2 FLAIR Brain MRI)
- Time since stroke onset prediction (T1 Brain MRI)
- Glioma segmentation (T2 FLAIR Brain MRI)
- IDH mutation prediction (T1C & FLAIR Brain MRI)
- Brain age prediction (T1-weighted MRI)
- Mild Cognitive Impairment / Dementia risk prediction (T1-weighted MRI)


&nbsp;
# 🏆 Miscellaneous 
- Reviewer for MICCAI 2025, European Radiology, Artificial Intelligence in Medicine, AJNR, BMJ Digital Health & AI
- Spotlight Award, Artificial Intelligence in Medicine, Brigham and Women's Hospital
- Minor in Entrepreneurship, Harvard Griffinn GSAS Business Club
- 3rd Place, SAE AutoDrive Challenge 2, Team Buckeye AutoDrive, Ohio State
- National Champion, ABU ROBOCON 2018, India -  Team Nirma University 

