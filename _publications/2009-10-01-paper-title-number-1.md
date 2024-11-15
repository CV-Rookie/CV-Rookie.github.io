---
title: "Paper Title Number 1"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Enforcing High Frequency Enhancement in Deep Networks for Simultaneous Depth Estimation and Dehazing.'
date: 2024-06-17
venue: 'Applied Soft Computing'
slidesurl: 'https://doi.org/10.1016/j.asoc.2024.111873'
paperurl: 'https://doi.org/10.1016/j.asoc.2024.111873'
citation: 'Xing Wei,Enforcing high frequency enhancement in deep networks for simultaneous depth estimation and dehazing,Applied Soft Computing,Volume 163,2024,111873,ISSN 1568-4946'
---

Single image dehazing and monocular depth estimation algorithms are crucial for environmental perception for autonomous driving. However, few algorithms can simultaneously perform single-image dehazing and depth estimation to solve the problems of perceiving surrounding information for unmanned vehicles in haze. The current algorithm based on the Transformer and Convolutional Neural Networks cannot effectively extract high frequency information and low frequency information in the image, resulting in poor image dehazing and depth estimation ability. Therefore, we design the DADENet network to solve these problems. We enhanced sensitivity to high-frequency information by incorporating Sobel operators and Gaussian blur into the residual unit structure, resulting in the ResNet-Edge-Encoder block. Furthermore, we improved the capability to extract both high-frequency and low-frequency information from feature maps by effectively combining depthwise convolutions with attention structures in the Transformer-Edge-Decoder block. Additionally, we designed the Depth-Transmission loss function to leverage the relationship between depth maps and transmission maps, thereby enhancing the accuracy of both single-image dehazing and depth estimation tasks. Extensive experiments on the NYU, KITTI and Citycapes datasets demonstrate that our DADENet algorithm effectively performs single-image dehazing and depth estimation, surpassing classical and state-of-the-art algorithms.
