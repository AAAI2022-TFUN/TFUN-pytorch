# TFUN: Trilinear Fusion Network for Cross-Modal

This repository is the **anonymous** Pytorch implementation of the paper: *TFUN: Trilinear Fusion Network for Cross-Modal*

![image](https://github.com/ACM-MM2021/TFUN-pytorch/blob/main/img/framework.pdf)

![image](https://github.com/ACM-MM2021/TFUN-pytorch/blob/main/img/framework.png)

The proposed TFUN method contains three main procedures: 1) During feature embedding, the pre-trained ResNet-50, sentence2vector (S2V) and GRU are utilized to extract embedding of the image, instruction and ingredient respectively; 2) The cross-modal trilinear fusion consisting of attention mechanism and tensor decomposition is used for capturing the interaction between three inputs and learning the similarity score; 3) The similarity score of image-recipe pairs will be selected by our proposed three-stage hard triplet sampling strategy.

