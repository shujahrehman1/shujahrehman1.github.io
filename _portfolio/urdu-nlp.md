---
title: "Cross-Lingual Transfer Learning for Urdu"
excerpt: "Pretraining a BERT-based transformer from scratch on Urdu text to benchmark transfer learning for low-resource NLP tasks."
collection: portfolio
date: 2021-03-01
header:
  image: projects/urdu-nlp.svg
  teaser: projects/urdu-nlp.svg
tags:
  - NLP
  - Transfer Learning
  - Low-Resource Languages
---

Urdu has far less labeled NLP data and far fewer pretrained models than English, which makes tasks like propaganda detection, topic classification, and sentiment analysis harder to build reliably. As a Research Officer at UET Lahore's HPCNL, I worked on closing that gap through cross-lingual transfer learning.

**Pretraining.** I pretrained a BERT-based transformer model from scratch on a large Urdu corpus, building the full pipeline myself — from raw text preprocessing through to model training.

**Cross-lingual transfer.** I built NLP pipelines that transferred learned representations across languages for the target Urdu tasks, and benchmarked several popular transfer learning methods against each other to see which approaches held up best for a genuinely low-resource setting.

**Outcome.** This work — [Investigating Cross-Lingual Transfer Learning for Urdu Text Using Word Embeddings](/publication/2021-12-urdu-transfer-learning) — was published at ICOSST 2021.
