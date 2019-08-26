
---
title: "Self-Supervised Blur Detection from Synthetically Blurred Scenes"
collection: publications
permalink: /publication/2019-08-25-alvarez-gila_self-supervised_2019
date: 2019-08-25
venue: 'Image and Vision Computing'
paperurl: 'https://doi.org/10.1016/j.imavis.2019.08.008'
citation: 'A. Alvarez-Gila, A. Galdran, E. Garrote, and J. van de Weijer, “Self-supervised blur detection from synthetically blurred scenes (IN PRESS),” Image and Vision Computing, Aug. 2019.'     
---

<a href='https://doi.org/10.1016/j.imavis.2019.08.008'>Full text (official)</a>

<a href='https://github.com/aitorshuffle/synthblur'>Full text (preprint)-AVAILABLE SOON</a>

<a href='https://github.com/aitorshuffle/synthblur'>Code, models and data </a>

Abstract: 

> Blur detection aims at segmenting the blurred areas of a given image. Recent deep learning-based methods approach this problem by learning an end-to-end mapping between the blurred input and a binary mask representing the localization of its blurred areas. Nevertheless, the effectiveness of such deep models is limited due to the scarcity of datasets annotated in terms of blur segmentation, as blur annotation is labor intensive. In this work, we bypass the need for such annotated datasets for end-to-end learning, and instead rely on object proposals and a model for blur generation in order to produce a dataset of synthetically blurred images. This allows us to perform self-supervised learning over the generated image and ground truth blur mask pairs using CNNs, defining a framework that can be employed in purely self-supervised, weakly supervised or semi-supervised configurations. Interestingly, experimental results of such setups over the largest blur segmentation datasets available show that this approach achieves state of the art results in blur segmentation, even without ever observing any real blurred image. 

![fig1]({{ site.url }}/images/alvarez-gila_self-supervised_2019_fig1_abstract.png)

Bibtex:

```
@article{alvarez-gila_self-supervised_2019,
  title = {Self-Supervised Blur Detection from Synthetically Blurred Scenes ({{IN PRESS}})},
  issn = {0262-8856},
  abstract = {Blur detection aims at segmenting the blurred areas of a given image. Recent deep learning-based methods approach this problem by learning an end-to-end mapping between the blurred input and a binary mask representing the localization of its blurred areas. Nevertheless, the effectiveness of such deep models is limited due to the scarcity of datasets annotated in terms of blur segmentation, as blur annotation is labor intensive. In this work, we bypass the need for such annotated datasets for end-to-end learning, and instead rely on object proposals and a model for blur generation in order to produce a dataset of synthetically blurred images. This allows us to perform self-supervised learning over the generated image and ground truth blur mask pairs using CNNs, defining a framework that can be employed in purely self-supervised, weakly supervised or semi-supervised configurations. Interestingly, experimental results of such setups over the largest blur segmentation datasets available show that this approach achieves state of the art results in blur segmentation, even without ever observing any real blurred image.},
  journal = {Image and Vision Computing},
  doi = {https://doi.org/10.1016/j.imavis.2019.08.008},
  author = {{Alvarez-Gila}, Aitor and Galdran, Adrian and Garrote, Estibaliz and van de Weijer, Joost},
  month = aug,
  year = {2019},
  keywords = {_deep_learning_based,_read,Blur,Deep learning,Defocus,Motion,Self-supervised learning,Synthetic}
}
```