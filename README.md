<p align="center">
  <h2 align="center"><b>LHT-CLIP</b>: Improving Visual Discriminability of CLIP for Training-Free Open-Vocabulary Semantic Segmentation</h2>
  <p align="center">
    <a style="text-decoration:none" href="https://jinxinzhou.github.io/">
                       Jinxin Zhou</a><sup>1</sup>
    &nbsp;&nbsp;
    <a style="text-decoration:none" href="https://kongwanbianjinyu.github.io/">
                        Jiachen Jiang</a><sup>1</sup>
    &nbsp;&nbsp;
    <a style="text-decoration:none" href="https://zhihuizhu.github.io/index.html">
                     Zhihui Zhu</a><sup>1</sup>
    <br>
    <sup>1</sup>The Ohio State University
    <br> <a href="https://jmlr.org/tmlr/"><strong>TMLR 2026</strong></a>
    </br>
  <a href="https://arxiv.org/abs/2510.23894"><strong>Paper</strong></a> | <a href="https://jinxinzhou.github.io/LTH-CLIP/"><strong>Project Page</strong></a>
  </p>
</p>

## Abstract

Extending CLIP models to semantic segmentation remains challenging due to the misalignment between their image-level pre-training objectives and the pixel-level visual understanding required for dense prediction. While prior efforts have achieved encouraging results by reorganizing the final layer and features, they often inherit the global alignment bias of preceding layers, leading to suboptimal segmentation performance. In this work, we propose **LHT-CLIP**, a novel training-free framework that systematically exploits the visual discriminability of CLIP across *layer*, *head*, and *token* levels. Through comprehensive analysis, we reveal three key insights: (i) the final layers primarily strengthen image–text alignment with sacrifice of visual discriminability; (ii) a subset of attention heads display consistently strong visual discriminability across datasets; (iii) abnormal tokens display sparse and consistent activation patterns compared to normal tokens. Based on these findings, we propose three complementary techniques: **spatial-semantic reweighting (SSR)**, **selective head enhancement (SHE)**, and **abnormal token replacement (ATR)** to effectively restore visual discriminability and improve segmentation performance without any additional training, auxiliary pre-trained networks, or extensive hyperparameter tuning.

## 🔨 Code

**Code coming soon!** Stay tuned for the release.

## Citation

If you find our work helpful, please kindly cite:
```BibTeX
@article{zhou2025improving,
  title={Improving Visual Discriminability of CLIP for Training-Free Open-Vocabulary Semantic Segmentation},
  author={Zhou, Jinxin and Jiang, Jiachen and Zhu, Zhihui},
  journal={arXiv preprint arXiv:2510.23894},
  year={2025}
}
```

## Acknowledgement

This work was supported by NSF grants CCF-2240708 and CCF-2241298.
