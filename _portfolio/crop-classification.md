---
title: "Satellite-Based Crop Classification"
excerpt: "Improving Random Forest crop classification accuracy across growing seasons using Google Earth Engine and spectral indices."
collection: portfolio
date: 2022-07-01
header:
  image: projects/crop-classification.svg
  teaser: projects/crop-classification.svg
tags:
  - Remote Sensing
  - Google Earth Engine
  - Classical ML
---

As a Research Assistant in LUMS's Computer Vision & Graphics Lab, I worked with a team to improve crop classification for the LBDC region of Punjab, Pakistan — distinguishing Rabi and Kharif season crops from satellite imagery.

**Approach.** The team's existing pipeline used a Random Forest classifier over multi-band satellite imagery; my focus was on improving what fed into it. I built visualizations of key spectral indices — NDVI, EVI, and NDWI — to track how vegetation and water signatures shifted across the growing season, entirely in Google Earth Engine.

**Analysis.** I ran quantitative and qualitative analysis on how NDVI thresholds, masking strategies, and the choice of monthly intervals affected downstream classification accuracy, to find settings that generalized rather than overfit to a single season.

**Outcome.** The resulting index visualizations and threshold analysis fed directly into improving the classifier's accuracy across both growing seasons.
