# Differential Surfel Rasterization

This repository contains the rasterization engine used in the paper  
**"Training-Free Hierarchical Scene Understanding for Gaussian Splatting with Superpoint Graphs"** ([arXiv:2504.13153](https://arxiv.org/abs/2504.13153)).

It is built upon the [2D Gaussian Splatting (2DGS)](https://github.com/hbb1/2d-gaussian-splatting) framework and incorporates components adapted from [Occam's LGS](https://github.com/insait-institute/OccamLGS).

This rasterization engine can be used for downstream tasks such as **semantic segmentation** and **depth estimation**.

If you find this repository useful, please consider citing:

> Our work:

```BibTeX
@article{thgs2025,
    title={Training-Free Hierarchical Scene Understanding for Gaussian Splatting with Superpoint Graphs},
    author={Dai, Shaohui and Qu, Yansong and Li, Zheyan and Li, Xinyang and Zhang, Shengchuan and Cao, Liujuan},
    journal={arXiv preprint arXiv:2504.13153},
    year={2025}
}
```

> Along with 2DGS and Occam's LGS:

```BibTeX
@inproceedings{Huang2DGS2024,
    title={2D Gaussian Splatting for Geometrically Accurate Radiance Fields},
    author={Huang, Binbin and Yu, Zehao and Chen, Anpei and Geiger, Andreas and Gao, Shenghua},
    publisher = {Association for Computing Machinery},
    booktitle = {SIGGRAPH 2024 Conference Papers},
    year      = {2024},
    doi       = {10.1145/3641519.3657428}
}
```

```BibTeX
@article{cheng2024occamslgssimpleapproach,
    title={Occam's LGS: A Simple Approach for Language Gaussian Splatting}, 
    author={Jiahuan Cheng and Jan-Nico Zaech and Luc Van Gool and Danda Pani Paudel},
    year={2024},
    eprint={2412.01807}
}
```
