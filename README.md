# Unsupervised Domain Adaptation for Semantic Segmentation
[![](https://img.shields.io/badge/last%20commit-jun%202019-brightgreen.svg?style=flat-square)](https://github.com/TillBeemelmanns/DA/commits/master)



The resources only focus on unsupervised domain adapation for semantic segmentation and these include related papers and the codes from top conferences and journals. Repro originally created by [barebell](https://github.com/barebell). See  [Unsupervised Domain Adaption](https://github.com/barebell/DA) for more infos. 

- [Unsupervised Domain Adaptation Semantic Segmentation](#Unsupervised-Domain-Adaptation)
  - [Conference Papers](#Conference-Papers)
    - [2019 Conference Papers](#2019-Conference-Papers)
    - [2018 Conference Papers](#2018-Conference-Papers)
    - [Conference Papers befor 2018](#Conference-Papers-befor-2018)
  - [Journal Papers](#Journal-Papers)
  - [arXiv Papers](#arXiv-Papers)
  - [Other Resources](#Other-Resources)

## Conference Papers

### 2019 Conference Papers
| Abbreviation | Paper Title                                                                                                 | Source Link                                                                                                                                                                                            | Code                                                                                          | Synthia -> Cityscapes (mIoU) | GTA5 -> Cityscapes (mIoU) |
| ------------ | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ------------ |
| **GIO-Ada**   | Learning Semantic Segmentation From Synthetic Data: A Geometrically Guided Input-Output Adaptation Approach | [CVPR2019](https://arxiv.org/pdf/1812.05040.pdf)                                                                                                                                                       |                                                                                               | 43.0%                                                                            | - |
| **DISE**     | All about Structure: Adapting Structural Information across Domains for Boosting Semantic Segmentation      | [CVPR2019](https://arxiv.org/pdf/1903.12212v1.pdf)                                                                                                                                                     | [Pytorch(Official)](https://github.com/a514514772/DISE-Domain-Invariant-Structure-Extraction) | 41.5%                                                                             | 45.4% |
| **BDL**     | Bidirectional Learning for Domain Adaptation of Semantic Segmentation                                       | [CVPR2019](https://arxiv.org/pdf/1904.10620.pdf)                                                                                                                                                       | [Pytorch(Official)](https://github.com/liyunsheng13/BDL)                                      | 51.4%                                                                           | 48.5% |
| **ADVENT**   | ADVENT: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation                     | [CVPR2019 Oral](https://arxiv.org/pdf/1811.12833.pdf)                                                                                                                                                  | [Code(Empty)](https://github.com/valeoai/ADVENT)                                              | 45.5%                                                            | 48.0% |
| **CLAN**     | Taking A Closer Look at Domain Shift: Category-level Adversaries for Semantics Consistent Domain Adaptation | [CVPR2019 Oral](https://arxiv.org/pdf/1809.09478.pdf)                                                                                                                                                  | [Pytorch(Official)](https://github.com/RoyalVane/CLAN)                                              | 47.8%                                           | 43.2% |
| **SWD**      | Sliced Wasserstein Discrepancy for Unsupervised Domain Adaptation                                           | [CVPR2019](https://arxiv.org/pdf/1903.04064.pdf)                                                                                                                                                       |                                                                                               | 48.1%                                                    | 44.5% |
### 2018 Conference Papers

| Abbreviation | Paper Title                                      | Source Link                                                  | Code                                                         | Synthia -> Cityscapes (mIoU) | GTA5 -> Cityscapes (mIoU) |
| ------------ | ------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------- | ------------------------- |
| **CyCADA**   | Cycle Consistent Adversarial Domain Adaptation   | [ICML2018](http://proceedings.mlr.press/v80/hoffman18a/hoffman18a.pdf) | [Pytorch(Official)](https://github.com/jhoffman/cycada_release) | -                            | 39.5 %                    |
| **I2IAdapt** | Image to Image Translation for Domain Adaptation | [CVPR2018](http://openaccess.thecvf.com/content_cvpr_2018/papers/Murez_Image_to_Image_CVPR_2018_paper.pdf) |                                                              | -                            | 31.8 %                    |


## Other Resources

- [transferlearning](https://github.com/jindongwang/transferlearning)
- [awsome-domain-adaptation](https://github.com/zhaoxin94/awsome-domain-adaptation)
- [awesome-transfer-learning](https://github.com/artix41/awesome-transfer-learning)
- [Unsupervised Domain Adaption](https://github.com/barebell/DA)
