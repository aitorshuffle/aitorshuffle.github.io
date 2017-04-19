---
title: "Deep Convolutional Neural Networks for surface quality inspection of hot long metal products"
collection: publications
permalink: /publication/2016-09-08-alvarez-gila_deep_2016
date: 2016-09-08
venue: 'First European Machine Vision Forum'
paperurl: 'http://www.computervisionbytecnalia.com/wp-content/uploads/2016/09/EMVA-Deep-Convolutional-Neuronal-Networks-for-surface-quality-inspection-of-hot-long-metal-products.pdf'
citation: 'A. Alvarez-Gila, A. Lopez-Cruz, S. Rodriguez-Vaamonde, M. Linares, J. A. Gutierrez-Olabarria, and E. Garrote, “Deep Convolutional Neural Networks for surface quality inspection of hot long metal products,” presented at the First European Machine Vision Forum, Heidelberg, Germany, 2016.'
---

<a href='http://www.computervisionbytecnalia.com/wp-content/uploads/2016/09/EMVA-Deep-Convolutional-Neuronal-Networks-for-surface-quality-inspection-of-hot-long-metal-products.pdf'>Pdf</a>

Abstract: 

>This paper presents the advances incorporated into Tecnalia’s SURFIN surface quality inspection system. SURFIN performs real-time detection and classification of external defects (e.g. roll marks, cracks, etc.) from the manufacturing process of metallic products such as bars, tubes, billets, slabs, beam blanks or structural profiles. The equipment is installed in the production line. It can detect defects at the early stages in the production process, when the product is still incandescent (>1000ºC). This allows preventing the unnecessary addition of value to it. The system is based on laser triangulation and machine learning techniques.\nWe have upgraded SURFIN by replacing the previous commercial software-based detection and classification module –supported by opaque handcrafted feature extraction and Support Vector Machines (SVM)– with an in-house made candidate window detection stage and a Convolutional Neural Network (CNN) performing the actual defect classification (CNNSURFIN). The image database includes 3886 cropped images from long hot bars (2475 good and 1411 showing three defect categories). We evaluated CNN-SURFIN architecturebased classifier over these in a 10-fold cross validation setup for good vs. bad classification, finding that it (AUC=0.9970) significantly outperformed the commercial SVM-based classifier (AUC=0.88). We have also implemented two baselines by extracting texture features (LBP) and training an SVM (AUC=0.92) and a Random Forest classifier (AUC=0.95) on top of these, further supporting the superiority of the deep learning-based approach. Finally, we trained CNN-SURFIN for the full 4-class classification problem, yielding an AUC of 0.9956.

Bibtex: 

```
@inproceedings{alvarez-gila_deep_2016,
	address = {Heidelberg, Germany},
	title = {Deep {Convolutional} {Neural} {Networks} for surface quality inspection of hot long metal products},
	url = {http://www.computervisionbytecnalia.com/wp-content/uploads/2016/09/EMVA-Deep-Convolutional-Neuronal-Networks-for-surface-quality-inspection-of-hot-long-metal-products.pdf},
	language = {en},
	author = {Alvarez-Gila, Aitor and Lopez-Cruz, Antonio and Rodriguez-Vaamonde, Sergio and Linares, Miguel and Gutierrez-Olabarria, José A. and Garrote, Estíbaliz},
	month = sep,
	year = {2016}
}
```