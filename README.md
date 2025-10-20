# 🐳 [NeurIPS 2025] Feature-Based Instance Neighbor Discovery: Advanced Stable Test-Time Adaptation in Dynamic World

This is the official project repository for [Feature-Based Instance Neighbor Discovery: Advanced Stable Test-Time Adaptation in Dynamic World (NeurIPS 2025)](https://arxiv.org/abs/2506.06782) by Qinting Jiang, Chuyang Ye, Dongyan Wei, Bingli Wang, Yuan Xue, Jingyan Jiang, Zhi Wang.

The code is being sorted out and will be coming soon! For any questions, please contact jqt23@mails.tsinghua.edu.cn.


## 🚀 Overview

>  Real-world data streams are **dynamic and diverse**, making traditional "**one-size-fits-all**" test-time normalization ineffective.

>  FIND addresses this challenge with a "**divide-and-conquer**" approach, combining in-layer feature grouping with adaptive normalization.

>  This innovative strategy delivers approximately **5%-10% accuracy improvements** in dynamic scenarios, all while maintaining efficient inference.

<div align="center">
  <img src="https://github.com/Peanut-255/image-hosting/blob/main/NIPS-Overview.png" alt="Teaser Image" width="500">
</div>

## 🍀 Acknowledgements

We owe special thanks to the **LINs-lab** —without their excellent open-source framework, this project would simply not exist.

Their work [TTAB 🔗](https://github.com/LINs-lab/ttab) laid the foundation for everything we've built.


## 🐚 Method Illustration

The proposed FIND involves three novel designs, including layer-wise feature disentanglement (LFD), feature-aware batch normalization (FABN) and selective FABN (S-FABN).

* 1️⃣ We introduce the pioneering test-time normalization framework specifically designed for realistic dynamic scenarios, addressing the limitations of current one-size-fits-all normalization approaches in practical applications.
* 2️⃣ Our method employs instance-level statistics to identify and cluster features with similar distributions, achieving robust dynamic adaptation through the aggregation of group-specific knowledge and generic knowledge from the source domain.
  
<div align="center">
  <img src="https://github.com/Peanut-255/image-hosting/blob/main/NIPS-method.png?raw=true" alt="Teaser Image" width="1000">
</div>

## 🍀 Results on Corruption Datasets

<div align="center">
  <img src="https://github.com/Peanut-255/image-hosting/blob/main/results.png?raw=true" alt="Teaser Image" width="800">
</div>



## 🎓 Citation

If you use this code for your research, please cite our paper.

```bibtex
@article{jiang2025feature,
  title={Feature-Based Instance Neighbor Discovery: Advanced Stable Test-Time Adaptation in Dynamic World},
  author={Jiang, Qinting and Ye, Chuyang and Wei, Dongyan and Wang, Bingli and Xue, Yuan and Jiang, Jingyan and Wang, Zhi},
  journal={arXiv preprint arXiv:2506.06782},
  year={2025}
}
```
