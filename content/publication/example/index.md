---
abstract: >-
  Despite advances in Deep Learning, the Convolutional Neural Networks methods
  still manifest limitations

  in medical applications because datasets are usually restricted in the number of samples or include poorly

  contrasted images. Such a case is found in stenosis detection using X-rays coronary angiography. In this study,

  the emerging field of quantum computing is applied in the context of hybrid neural networks. So, a hybrid

  transfer-learning paradigm is used for stenosis detection, where a quantum network drives and improves the

  performance of a pre-trained classical network. An intermediate layer between the classical and quantum

  network post-processes the classical features by mapping them into a hypersphere of fixed radius through

  a hyperbolic tangent function. Next, these normalized features are processed in the quantum network, and

  through a SoftMax function, the class probabilities are obtained: stenosis and non-stenosis. Furthermore, a

  distributed variational quantum circuit is implemented to split the data into multiple quantum circuits within

  the quantum network, improving the training time without compromising the stenosis detection performance.

  The proposed method is evaluated on a small X-ray coronary angiography dataset containing 250 image

  patches (50%–50% of positive and negative stenosis cases). The hybrid classical-quantum network significantly

  outperformed the classical network. Evaluation results showed a boost concerning the classical transfer learning

  paradigm in the accuracy of 9%, recall of 20%, and F1-score of 11%, reaching 91.8033%, 94.9153%, and

  91.8033%, respectively.
slides: ""
url_pdf: ""
publication_types:
  - "2"
authors:
  - Emmanuel Ovalle-Magallanes
  - Juan Gabriel Avina-Cervantes
  - Ivan Cruz-Aceves
  - Jose Ruiz-Pinales
author_notes: []
publication: In *Expert Systems with Applications*
summary: "In this study, the emerging field of quantum computing is applied in
  the context of hybrid neural networks. So, a hybrid transfer-learning paradigm
  is used for stenosis detection, where a quantum network drives and improves
  the performance of a pre-trained classical network. An intermediate layer
  between the classical and quantum network post-processes the classical
  features by mapping them into a hypersphere of fixed radius through a
  hyperbolic tangent function. Next, these normalized features are processed in
  the quantum network, and through a SoftMax function, the class probabilities
  are obtained: stenosis and non-stenosis. Furthermore, a distributed
  variational quantum circuit is implemented to split the data into multiple
  quantum circuits within the quantum network, improving the training time
  without compromising the stenosis detection performance. "
url_dataset: ""
url_project: ""
publication_short: In *ESWA*
url_source: ""
url_video: ""
title: Hybrid classical–quantum Convolutional Neural Network for stenosis
  detection in X-ray coronary angiography
doi: 10.1016/j.eswa.2021.116112
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: 0_graphical_abstract.jpg
date: 2021-11-15T23:26:54.113Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
<!--StartFragment-->

## Highlights

* A quantum network boosts the performance of classical neural architecture.
* An L hyperbolic tangent layer bounds the features between classical and quantum stages.
* The X-ray angiography images are analyzed to develop a robust stenosis detector system.
* Transfer learning and quantum network substantially improved stenosis detection.
* An efficient hybrid classical–quantum architecture is focused on stenosis detection.

<!--EndFragment-->