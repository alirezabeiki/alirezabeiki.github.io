---
title: "Parametric Study of Convolution Autoencoder for Reduced-Order Modeling of Turbulent Flow"
collection: publications
category: manuscripts
permalink: /publication/2023-03-09-parametric-study-convolution-autoencoder
excerpt: 'This paper analyzes multiscale convolutional autoencoder architectures for reduced-order modeling of turbulent flow, proposing modified convolution to reduce training parameters and computational cost.'
date: 2023-03-09
venue: 'Iranian Journal of Science and Technology, Transactions of Mechanical Engineering'
paperurl: 'https://link.springer.com/article/10.1007/s40997-023-00632-2'
doi: '10.1007/s40997-023-00632-2'
citation: 'Beiki, A., & Kamali, R. (2023). "Parametric Study of Convolution Autoencoder for Reduced-Order Modeling of Turbulent Flow." <i>Iranian Journal of Science and Technology, Transactions of Mechanical Engineering</i>, 47, 1679–1691.'
---

**Abstract**  
In this paper, we analyze the capabilities of several multiscale convolutional autoencoder architectures for reduced-order modeling of two-dimensional unsteady turbulent flow over a cylinder and the collapse of the water column. The results demonstrate the significance of multiscale convolution design for precision. Multiscale convolution, on the other hand, leads to the creation of millions of training parameters that require a large amount of memory. This results in an increase in the computational cost of the system. As a solution to this problem, we propose using modified convolution to reduce the number of training parameters within the model. As far as accuracy and computational efficiency are concerned, separable convolution yields the most efficient results in terms of accuracy. Moreover, the encoder component of the architecture is responsible for encoding high-dimensional data into a latent space with a low dimension. The latent spaces are transferred to the recurrent neural-type network and decoder section for the temporal evolution of the latent spaces and reconstruction of the flow field. In addition, the results demonstrate that GRU has fewer parameters than LSTM while maintaining the same accuracy.

**Key Highlights**  
- Analysis of multiscale convolutional autoencoder architectures for reduced-order modeling.
- Proposal of modified convolution to reduce training parameters and computational cost.
- Demonstration that separable convolution yields the most efficient results in accuracy.
- Comparison showing GRU maintains LSTM's accuracy with fewer parameters.

**Links**  
- [View on Springer](https://link.springer.com/article/10.1007/s40997-023-00632-2)
- [DOI: 10.1007/s40997-023-00632-2](https://doi.org/10.1007/s40997-023-00632-2)