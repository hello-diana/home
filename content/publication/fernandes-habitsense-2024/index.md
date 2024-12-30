---
title: 'HabitSense: A Privacy-Aware, AI-Enhanced Multimodal Wearable Platform for
  mHealth Applications'
authors:
- Glenn J. Fernandes
- Jiayi Zheng
- Mahdi Pedram
- Christopher Romano
- Farzad Shahabi
- Blaine Rothrock
- Thomas Cohen
- Helen Zhu
- Tanmeet S. Butani
- Josiah Hester
- Aggelos K. Katsaggelos
- Nabil Alshurafa
date: '2024-09-09'
publishDate: '2024-12-30T13:44:55.620897Z'
publication_types:
- article-journal
doi: 10.1145/3678591
abstract: Wearable cameras provide an objective method to visually confirm and automate
  the detection of health-risk behaviors such as smoking and overeating, which is
  critical for developing and testing adaptive treatment interventions. Despite the
  potential of wearable camera systems, adoption is hindered by inadequate clinician
  input in the design, user privacy concerns, and user burden. To address these barriers,
  we introduced HabitSense, an open-source1, multi-modal neck-worn platform developed
  with input from focus groups with clinicians (N=36) and user feedback from in-wild
  studies involving 105 participants over 35 days. Optimized for monitoring health-risk
  behaviors, the platform utilizes RGB, thermal, and inertial measurement unit sensors
  to detect eating and smoking events in real time. In a 7-day study involving 15
  participants, HabitSense recorded 768 hours of footage, capturing 420.91 minutes
  of hand-to-mouth gestures associated with eating and smoking data crucial for training
  machine learning models, achieving a 92% F1-score in gesture recognition. To address
  privacy concerns, the platform records only during likely health-risk behavior events
  using SECURE, a smart activation algorithm. Additionally, HabitSense employs on-device
  obfuscation algorithms that selectively obfuscate the background during recording,
  maintaining individual privacy while leaving gestures related to health-risk behaviors
  unobfuscated. Our implementation of SECURE has resulted in a 48% reduction in storage
  needs and a 30% increase in battery life. This paper highlights the critical roles
  of clinician feedback, extensive field testing, and privacy-enhancing algorithms
  in developing an unobtrusive, lightweight, and reproducible wearable system that
  is both feasible and acceptable for monitoring health-risk behaviors in real-world
  settings.
links:
- name: URL
  url: https://doi.org/10.1145/3678591
---
