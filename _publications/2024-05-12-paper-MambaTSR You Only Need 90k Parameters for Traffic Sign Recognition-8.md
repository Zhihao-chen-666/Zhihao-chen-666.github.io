---
title: "MambaTSR: You Only Need 90k Parameters for Traffic Sign Recognition"
collection: publications
permalink: /publication/2024-05-12-paper-MambaTSR You Only Need 90k Parameters for Traffic Sign Recognition-8
excerpt: ''
date: 2024-05-18
venue: 'Neurocomputing (JCR Q1)'
paperurl: 'TBD'
citation: 'TBD'
---

Traffic Sign Recognition (TSR) has made significant progress in recent years, and both convolution neural network (CNN)-based and transformer-based models have been widely explored. In addition, combining CNN and transformer can effectively utilize both local and global information for judgment. However, this approach is still affected by the secondary complexity of transformer and cannot maximize the performance. Recently, a state space model (SSM)-based architecture called Mamba has been proposed, which excels in long-range modelling while maintaining linear complexity. When we directly use the Mamba architecture for TSR, it performs poorly because the local features cannot be fully utilized, which are crucial for recognizing traffic sign details. In this paper, we explore the potential of this SSM-based model in TSR from both efficiency and effectiveness perspectives, and we customize a MambaTSR architecture with ~90k parameters and ~1.4ms processing time. Specifically, we use patch embedding and a four-stage encoder at the macro level, while at the micro level we employ three-stream adaptive mining embedding (TAME) to obtain local information and four efficient visual state space (EVSS) blocks to explore global associations. Experiments on German, China, and India datasets show that our method achieves optimal performance and reduces parameters by ~89% and processing time by ~58% compared to the state-of-the-art method. The code can be accessed at https://github.com/1024AILab/MambaTSR.
