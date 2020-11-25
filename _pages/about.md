---
permalink: /
title: "About me"
excerpt: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my personal webpage! I'm a Postdoctoral researcher at [Ecole Polytechnique](https://www.polytechnique.edu/en) hosted by Prof. [Michalis Vazirgiannis](http://www.lix.polytechnique.fr/Labo/Michalis.Vazirgiannis/). I received my Ph.D. from [Centrale-Supélec](https://www.centralesupelec.fr/), [University of Paris-Saclay](https://www.universite-paris-saclay.fr/en) in 2020, where I was also attached to [CEA](http://www.cea.fr/) (French Atomic Agency) and where I worked on Random Matrix Theory and Machine Learning under the supervision of [Romain Couillet](https://romaincouillet.hebfree.org/) and [Mohamed Tamaazousti](http://mohamed-tamaazousti.com/).

**Main research interests: Random Matrix Theory, Machine Learning, Deep Learning, Graph Neural Networks.**

My Thesis [Slides](link)
======
**Title: Random Matrix Theory for AI: From Theory to Practice**

Composition of the jury:
- Prof. Julie Delon, Université Paris Descartes
- Dr. Jamal Najim, Université Marne la Vallée
- Prof. Méroune Debbah, Huawei Labs & CentraleSupélec
- Prof. Florent Krzakala, ENS Ulm
- Dr. Alexandre Gramfort, Inria Paris
- Dr. Florent Chartelain, Université Grenoble-Alpes
- Prof. Romain Couillet, CentraleSupélec
- Dr. Mohamed Tamaazousti, CEA List

Abstract: AI nowadays relies largely on using large data and enhanced machine learning methods which consist of developing classification and inference algorithms leveraging large datasets of large sizes. These large dimensions induce many counter-intuitive phenomena, leading generally to a misunderstanding of the behavior of many machine learning algorithms often designed with small data dimension intuitions. By taking advantage of (rather than suffering from) the multidimensional setting, random matrix theory (RMT) is able to predict the performance of many non-linear algorithms as complex as some random neural networks as well as many kernel methods such as Support Vector Machines, semi-supervised classification, principal component analysis or spectral clustering. To characterize the performance of these algorithms theoretically, the underlying data model is often a Gaussian mixture model (GMM) which seems to be a strong assumption given the complex structure of real data (e.g., images). Furthermore, the performance of machine learning algorithms depends on the choice of data representation (or features) on which they are applied. Once again, considering data representations as Gaussian vectors seems to be quite a restrictive assumption. Relying on random matrix theory, this thesis aims at going beyond the simple GMM hypothesis, by studying classical machine learning tools under the hypothesis of Lipschitz-ally transformed Gaussian vectors also called concentrated random vectors, and which are more generic than Gaussian vectors. This hypothesis is particularly motivated by the observation that one can use generative models (e.g., GANs) to design complex and realistic data structures such as images, through Lipschitz-ally transformed Gaussian vectors. This notably suggests that making the aforementioned concentration assumption on data is a suitable model for real data and which is just as mathematically accessible as GMM models. Moreover, in terms of data representation, the concentration framework is compatible with one of the most widely used data representations in practice, namely deep neural nets (DNNs) representations, since they consist of a Lipschitz transformation of the input data (e.g., images). Therefore, we demonstrate through this thesis, leveraging on GANs, the interest in considering the framework of concentrated vectors as a model for real data. In particular, we study the behavior of random Gram matrices which appear at the core of various linear models, kernel matrices that appear in kernel methods, and also classification methods that rely on an implicit solution (e.g., Softmax layer in neural networks), with concentrated random inputs. Indeed, these methods are at the heart of many classifications, regression, and clustering machine learning algorithms. In particular, understanding the behavior of these matrices/methods, for concentrated data, allows us to characterize the performances (on real data if we assimilate them to concentrated vectors) of many machine learning algorithms, such as spectral clustering, SVMs, principal component analysis, and transfer learning.  Analyzing these methods for concentrated data yields the surprising result that they have asymptotically the same behavior as for GMM data (with the same first and second-order statistics). This result strongly suggests the universality aspect of large machine learning classifiers w.r.t. the underlying data distribution.



