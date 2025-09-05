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
- *2025.06*: &nbsp; The BrainIAC downstream model suite (BrainAge, Dementia classification, IDH mutation prediction, Glioma segmentation) [demo](https://huggingface.co/spaces/Divytak) is live for public use! 
- *2025.05*: &nbsp;🎉📝 Our [Blogpost](https://mathematical-oncology.org/blog/gbm-predictions.html) My blogpost on integtation of deep-learning with mechanistic filters and SINDY for GBM reccurance predicton is out on Mathematical Oncology
- *2025.04*: &nbsp;🎉📝 Our [paper](https://ai.nejm.org/doi/full/10.1056/AIoa2400703) on predicting recurrence risk in pediatric gliomas using longitudinal deep learing was published in NEJM AI
- *2025.01*: &nbsp; BrainIAC - A Generalized Brain MRI foundation model [preprint](https://www.medrxiv.org/content/10.1101/2024.12.02.24317992v1) is out! 
- *2024.03*: &nbsp;🎉📝 Our [paper](https://pubs.rsna.org/doi/full/10.1148/ryai.230333) on perdicting BRAF Mutation status for pediatric glioma using deep learning was published on the cover of Radiology AI 

&nbsp;

# 📝 Publications 

### BrainIAC - Generalized Vision Foundation Model for Brain MRI
- `under review Nature Neuroscience` D Tak *et al.* [(https://www.medrxiv.org/content/10.1101/2024.12.02.24317992v1](https://arxiv.org/abs/2501.09001)) 

### Longitudinal Risk Prediction for Pediatric Glioma with Temporal Deep Learning
- `NEJM AI` D Tak *et al.* (https://ai.nejm.org/doi/full/10.1056/AIoa2400703) 

### Noninvasive Molecular Subtyping of Pediatric Low-Grade Glioma with Self-Supervised Transfer Learning
- `Radiology AI` D Tak et al. (https://pubs.rsna.org/doi/full/10.1148/ryai.230333) 

### Path Tracing in Holonomic Drive System with Reduced Overshoot using Rotary Encoders 
- `IEEE SPIN` D Tak *et al.* (https://ieeexplore.ieee.org/abstract/document/9071196) 


&nbsp;
# 🚀 Open Source & Demos 
- Glioma Segmentation using T2 FLAIR Brain MRI [HuggingFace](https://huggingface.co/Divytak)
- Glioma IDH mutation prediction using T1C and FLAIR Brain MRI sequences [HuggingFace](https://huggingface.co/spaces/Divytak/IDH_Classification_BrainIAC)
- Brain age prediction using T1 weighted Brain MRI [HuggingFace](https://huggingface.co/spaces/Divytak/BrainIAC-Brainage-V0)
- Mild Cognitive Impairment / Dementia risk prediction using T1 weighted Brain MRI [HuggingFace](https://huggingface.co/spaces/Divytak/BrainIAC-MildCognitiveImpairment_Classification)

&nbsp;
# 🏆 Miscellaneous 
- Reviewer for MICCAI 2025, European Radiology, Artificial Intelligence in Medicine, AJNR, BMJ Digital Health & AI
- Spotlight Award, Artificial Intelligence in Medicine, Brigham and Women's Hospital
- Minor in Entrepreneurship, Harvard Griffinn GSAS Business Club
- 3rd Place, SAE AutoDrive Challenge 2, Team Buckeye AutoDrive, Ohio State
- National Champion, ABU ROBOCON 2018, India -  Team Nirma University 

