# Tensor Network Toolbox (Matlab)

Yu-Bang Zheng, Xi-Le Zhao, Qibin Zhao, Junjun Pan, Michael K. Ng, Heng-Chao Li, Ting-Zhu Huang

## 1. Introduction

Tensor network decomposition decomposes an Nth-order tensor into a series of factor tensors, or matrices, and establishes an interactive tensor contraction between these factors, providing the compact representation of high-dimensional data. We develop a tensor network decomposition (termed as TenNet) toolbox in Matlab. The TenNet toolbox can implement tensor operations and tensor network decompositions, including tensor train (TT) [1], tensor ring (TR) [2], and fully-connected tensor network (FCTN) [3] decompositions, which are demonstrated in the task of tensor completion (TC).

## 2. Example

Simply run the “Demo_TN_TC.m” to test all the above functions. The test data is available at http://trace.eas.asu.edu/yuv/.

## 3. Citation

Please cite the corresponding references when using the TenNet toolbox in your papers.

[1] I. V. Oseledets, “Tensor-train decomposition,” SIAM Journal on Scientific Computing, vol. 33, no. 5, pp. 2295–2317, 2011.

[2] Q. Zhao, G. Zhou, S. Xie, L. Zhang, and A. Cichocki, “Tensor ring decomposition,” arXiv preprint arXiv:1606.05535, 2016.

[3] Y.-B. Zheng, T.-Z. Huang, X.-L. Zhao, Q. Zhao, and T.-X. Jiang, “Fully-connected tensor network decomposition and its application to higher-order tensor completion,” in AAAI, vol. 35, no. 12, pp. 11 071–11 078, 2021.

[4] T. G. Kolda and B. W. Bader, “Tensor decompositions and applications,” SIAM Review, vol. 51, no. 3, pp. 455–500, 2009.
