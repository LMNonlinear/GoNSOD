# The Geometry of Nodal Sets and Outlier Detection

This repository contains a Matlab implementation of

![f_N(x) = \sum_{k \leq N}{ \frac{1}{\sqrt{\lambda_k}}
\frac{|\phi_k(x)|}{\|\phi_k\|_{L^{\infty}(M)}}}](/f_N.png)

for outlier detection, described in the paper:
Xiuyuan C., Mishne G. and Steinerberger S. (2017). The Geometry of Nodal Sets and Outlier Detection. [arXiv preprint arXiv:1706.01362](https://arxiv.org/abs/1706.01362).
Included are an implementation of outlier detection on a 3D mesh (Stanford bunny from http://graphics.stanford.edu/data/3Dscanrep) 
and outlier detection on an image.

## Dependencies
[Diffusion Maps Matlab code](https://github.com/gmishne/diffusion_maps)
