---
title: "Driver Behavior Recognition via Interwoven Deep Convolutional Neural Nets with Multi-stream Inputs"
collection: publications
permalink: /publication/2018-interweaving
excerpt: ''
date: 2018-11-01
venue: 'Draft'
paperurl: 'https://arxiv.org/abs/1811.09128'
citation: 'Chaoyun Zhang, Rui Li, Woojin Kim, Daesub Yoon and Paul Patras (2018). &quot; 
Driver Behavior Recognition via Interwoven Deep Convolutional Neural Nets with Multi-stream Inputs.&quot; <i>
Draft </i>. arXiv preprint arXiv:1811.09128'
---
Abstract: 
Recognizing driver behaviors is becoming vital for in-vehicle systems that seek to reduce the incidence of car accidents rooted in cognitive distraction. In this paper, we harness the exceptional feature extraction abilities of deep learning and propose a dedicated Interwoven Deep Convolutional Neural Network (InterCNN) architecture to tackle the accurate classification of driver behaviors in real-time. The proposed solution exploits information from multi-stream inputs, i.e., in-vehicle cameras with different fields of view and optical flows computed based on recorded images, and merges through multiple fusion layers abstract features that it extracts. This builds a tight ensembling system, which significantly improves the robustness of the model. We further introduce a temporal voting scheme based on historical inference instances, in order to enhance accuracy. Experiments conducted with a real world dataset that we collect in a mock-up car environment demonstrate that the proposed InterCNN with MobileNet convolutional blocks can classify 9 different behaviors with 73.97% accuracy, and 5 aggregated behaviors with 81.66% accuracy. Our architecture is highly computationally efficient, as it performs inferences within 15ms, which satisfies the real-time constraints of intelligent cars. In addition, our InterCNN is robust to lossy input, as the classification remains accurate when two input streams are occluded.

[PDF](http://ruihuili.github.io/files/zhang18drive.pdf)
