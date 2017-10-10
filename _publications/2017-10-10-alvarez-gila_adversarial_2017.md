---
title: "Adversarial Networks for Spatial Context-Aware Spectral Image Reconstruction from RGB"
collection: publications
permalink: /publication/2017-10-10-alvarez-gila_adversarial_2017
date: 2017-10-10
venue: 'ICCV 2017 Workshop Physics-Based Vision meets Deep Learning'
paperurl: 'https://arxiv.org/abs/1709.00265'
citation: 'A. Alvarez-Gila, J. van de Weijer, and E. Garrote, “Adversarial Networks for Spatial Context-Aware Spectral Image Reconstruction from RGB,” presented at the 1st International Workshop on  Physics Based Vision meets Deep Learning at ICCV2017, Venice, Italy, 2017.'
---

Available: https://arxiv.org/abs/1709.00265

<a href='https://arxiv.org/abs/1709.00265'>Full text preprint</a>

Abstract: 

>Hyperspectral signal reconstruction aims at recovering the original spectral input that produced a certain trichromatic (RGB) response from a capturing device or observer. Given the heavily underconstrained, non-linear nature of the problem, traditional techniques leverage different statistical properties of the spectral signal in order to build informative priors from real world object reflectances for constructing such RGB to spectral signal mapping. However, most of them treat each sample independently, and thus do not benefit from the contextual information that the spatial dimensions can provide. We pose hyperspectral natural image reconstruction as an image to image mapping learning problem, and apply a conditional generative adversarial framework to help capture spatial semantics. This is the first time Convolutional Neural Networks -and, particularly, Generative Adversarial Networks- are used to solve this task. Quantitative evaluation shows a Root Mean Squared Error (RMSE) drop of 44.7% and a Relative RMSE drop of 47.0% on the ICVL natural hyperspectral image dataset.

![Adversarial RGB to hyperspectral image reconstruction]({{ site.url }}/images/advrgb2hs_sample.png)

Bibtex:

```
@inproceedings{alvarez-gila_adversarial_2017,
  address = {Venice, Italy},
  title = {Adversarial {{Networks}} for {{Spatial Context}}-{{Aware Spectral Image Reconstruction}} from {{RGB}}},
  booktitle = {1st {{International Workshop}} on  {{Physics Based Vision}} Meets {{Deep Learning}} at {{ICCV2017}}},
  author = {Alvarez-Gila, Aitor and van de Weijer, Joost and Garrote, Estibaliz},
  year = {2017}
}
```