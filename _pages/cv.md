---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---


{% include base_path %}

Education
======
* M.S. in Electrical Engineering (Graduated with Distinction), Lahore University of Management Sciences (LUMS), Pakistan, 2024
* B.S. in Electrical Engineering, Lahore University of Management Sciences (LUMS), Pakistan, 2019

Work experience
======
* **September 2025 - Present: Research Specialist**
  * RISC Lab, King Abdullah University of Science and Technology (KAUST), Saudi Arabia
  * Perception for Agriculture and Underwater Robotic Applications
  * Built end-to-end CV pipeline for autonomous date-palm harvesting, deployed on Jetson AGX Orin
  * Curated and annotated 7,000+ real-world images using CLIP-based filtering and instance segmentation
  * Trained and optimized YOLOv8-Seg for challenging outdoor agricultural conditions
  * Achieved 30 FPS embedded inference via model scaling and INT8/FP16 quantization
  * Integrated perception with ROS2 robotics pipelines

* **September 2022 - August 2025: Research Associate**
  * Algorithms in Theory and Practice (ATP) Lab, Lahore University of Management Sciences (LUMS)
  * Semi-Supervised Learning for Medical Imaging Data
  * Implemented complete pipeline from pre-processing to training deep learning models for semi-supervised medical image segmentation for both 2D and 3D Cardiac MRI datasets in PyTorch
  * Proposed a computationally efficient U-Net based approach with two decoders for 3D Cardiac MRI scans leading to state-of-the-art performance
  * Explored self-supervised and fine-tuning approaches to enhance the generalizability of deep learning models for multi-center medical datasets

* **July 2022 - October 2022: Research Assistant**
  * Computer Vision & Graphics Lab, Lahore University of Management Sciences (LUMS)
  * Crop Classification for LBDC Region
  * Collaborated with a team to assess and improve the classification accuracy of a Random Forest Classifier for Rabi and Kharif seasons in the LBDC region, Punjab, Pakistan, using Google Earth Engine
  * Developed visualizations for key indices (NDVI, EVI, NDWI) to track seasonal variations and enhance model performance
  * Conducted qualitative and quantitative analysis on the impact of NDVI thresholds, masking, and monthly intervals on classification accuracy

* **March 2021 - August 2021: Research Officer**
  * High Performance Computing and Networking Lab (HPCNL), University of Engineering and Technology (UET) Lahore
  * Cross-lingual Transfer Learning for Urdu Text
  * Built and analyzed datasets, including Urdu-English word dictionaries and bilingual corpora for NLP tasks like propaganda detection, topic classification, and sentiment analysis
  * Implemented end-to-end pipelines for Urdu text processing and transfer learning in Python, covering dataset pre-processing to model deployment
  * Performed benchmarking of popular transfer learning methods for Urdu text classification tasks
  * Implemented complete pipeline from pre-processing of Urdu text data to implementation of Transformers-based BERT model for Urdu text

* **October 2019 - August 2020: Research Assistant**
  * Advanced Communications Lab, Lahore University of Management Sciences (LUMS)
  * Indoor Localization using Wi-Fi Received Signal Strength
  * Implemented outlier removal using K-Means clustering and confidence intervals to reduce localization error
  
Skills
======
* **Programming Languages**: Python, MATLAB, C++
* **Machine Learning & Computer Vision**: PyTorch, Scikit-learn, OpenCV, NumPy, Pandas, Matplotlib, Seaborn
* **Tools & Technologies**: Docker, Bash Scripting, LaTeX, Google Earth Engine, ROS2, NVIDIA Jetson

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

