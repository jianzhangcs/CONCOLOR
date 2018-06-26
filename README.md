
#### CONCOLOR: COnstrained Non-COnvex LOw-Rank Model for Image Deblocking (TIP 2016)

## Introduction
Due to independent and coarse quantization of transform coefficients in each block, block-based transform coding usually introduces visually annoying blocking artifacts at low bitrates, which greatly prevents further bit reduction. To alleviate the conflict between bit reduction and quality preservation, deblocking as a post-processing strategy is an attractive and promising solution without changing existing codec. In this paper, in order to reduce blocking artifacts and obtain high-quality image, image deblocking is formulated as an optimization problem within maximum a posteriori framework, and a novel algorithm for image deblocking using constrained non-convex low-rank model is proposed. The lp (0 < p <1) penalty function is extended on singular values of a matrix to characterize low-rank prior model rather than the nuclear norm, while the quantization constraint is explicitly transformed into the feasible solution space to constrain the non-convex low-rank optimization. Moreover, a new quantization noise model is developed, and an alternatively minimizing strategy with adaptive parameter adjustment is developed to solve the proposed optimization problem. This parameter-free advantage enables the whole algorithm more attractive and practical. Experiments demonstrate that the proposed image deblocking algorithm outperforms the current state-of-the-art methods in both the objective quality and the perceptual quality.


## Citation
If you find our code helpful in your resarch or work, please cite our paper.
```
@article{zhang2016concolor,
  title={CONCOLOR: Constrained non-convex low-rank model for image deblocking},
  author={Zhang, Jian and Xiong, Ruiqin and Zhao, Chen and Zhang, Yongbing and Ma, Siwei and Gao, Wen},
  journal={IEEE Transactions on Image Processing},
  volume={25},
  number={3},
  pages={1246--1259},
  year={2016},
  publisher={IEEE}
}
```

