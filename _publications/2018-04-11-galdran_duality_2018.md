---
title: "On the Duality Between Retinex and Image Dehazing"
collection: publications
permalink: /publication/2018-04-11-galdran_duality_2018
date: 2018-04-11
venue: 'Computer Vision and Pattern Recognition (CVPR) 2018'
paperurl: 'https://arxiv.org/abs/1712.02754'
citation: 'A. Galdran, A. Alvarez-Gila, A. Bria, J. Vazquez-Corral, and M. Bertalmio, “On the Duality Between Retinex and Image Dehazing,”in CVPR 2018, Salt Lake City, USA, 2018. 

---

<a href='https://arxiv.org/abs/1712.02754'>Full text</a>

Abstract: 

>Image dehazing deals with the removal of undesired loss of visibility in outdoor images due to the presence of fog. Retinex is a color vision model mimicking the ability of the Human Visual System to robustly discount varying illuminations when observing a scene under different spectral lighting conditions. Retinex has been widely explored in the computer vision literature for image enhancement and other related tasks. While these two problems are apparently unrelated, the goal of this work is to show that they can be connected by a simple linear relationship. Specifically, most Retinex-based algorithms have the characteristic feature of always increasing image brightness, which turns them into ideal candidates for effective image dehazing by directly applying Retinex to a hazy image whose intensities have been inverted. In this paper, we give theoretical proof that Retinex on inverted intensities is a solution to the image dehazing problem. Comprehensive qualitative and quantitative results indicate that several classical and modern implementations of Retinex can be transformed into competing image dehazing algorithms performing on pair with more complex fog removal methods, and can overcome some of the main challenges associated with this problem.

![fig1]({{ site.url }}/images/galdran_duality_2017_fig1_screenshot.png)

Bibtex:

```
@inproceedings{galdran_duality_2018,
  title = {On the Duality Between Retinex and Image Dehazing},
  address = {Salt Lake City, USA},
  booktitle = {CVPR 2018},
  url = {http://arxiv.org/abs/1712.02754},
  author = {Galdran, Adrian and Alvarez-Gila, Aitor and Bria, Alessandro and Vazquez-Corral, Javier and Bertalmio, Marcelo},
  year = {2018},
}
```