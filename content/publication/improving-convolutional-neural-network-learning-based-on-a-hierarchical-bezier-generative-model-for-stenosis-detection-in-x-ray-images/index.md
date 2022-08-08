---
title: Improving convolutional neural network learning based on a hierarchical
  bezier generative model for stenosis detection in X-ray images
publication_types:
  - "2"
authors:
  - Emmanuel Ovalle-Magallanes
  - Juan Gabriel Avina-Cervantes
  - Ivan Cruz-Aceves
  - Jose Ruiz-Pinales
doi: 10.1016/j.cmpb.2022.106767
abstract: >-
  Background and Objective: Automatic detection of stenosis on X-ray Coronary
  Angiography (XCA) images may help diagnose early coronary artery disease.
  Stenosis is manifested by a buildup of plaque in the arteries, decreasing the
  blood flow to the heart, increasing the risk of a heart attack. Convolutional
  Neural Networks (CNNs) have been successfully applied to identify
  pathological, regular, and featured tissues on rich and diverse medical image
  datasets. Nevertheless, CNNs find operative and performing limitations while
  working with small and poorly diversified databases. Transfer learning from
  large natural image datasets (such as ImageNet) has become a de-facto method
  to improve neural networks performance in the medical image domain.


  Methods: This paper proposes a novel Hierarchical Bezier-based Generative Model (HBGM) to improve the CNNs training process to detect stenosis. Herein, artificial image patches are generated to enlarge the original database, speeding up network convergence. The artificial dataset consists of 10,000 images containing 50% stenosis and 50% non-stenosis cases. Besides, a reliable Fréchet Inception Distance (FID) is used to evaluate the generated data quantitatively. Therefore, by using the proposed framework, the network is pre-trained with the artificial datasets and subsequently fine-tuned using the real XCA training dataset. The real dataset consists of 250 XCA image patches, selecting 125 images for stenosis and the remainder for non-stenosis cases. Furthermore, a Convolutional Block Attention Module (CBAM) was included in the network architecture as a self-attention mechanism to improve the efficiency of the network.


  Results: The results showed that the pre-trained networks using the proposed generative model outperformed the results concerning training from scratch. Particularly, an accuracy, precision, sensitivity, and F1-score of 0.8934, 0.9031, 0.8746, 0.8880, 0.9111, respectively, were achieved. The generated artificial dataset obtains a mean FID of 84.0886, with more realistic visual XCA images.


  Conclusions: Different ResNet architectures for stenosis detection have been evaluated, including attention modules into the network. Numerical results demonstrated that by using the HBGM is obtained a higher performance than training from scratch, even outperforming the ImageNet pre-trained models.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-03-29T16:59:55.341Z
---
