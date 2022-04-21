# 360° SINGLE IMAGE SUPER RESOLUTION VIA DISTORTION-AWARE NETWORK AND DISTORTED PERSPECTIVE IMAGES
This repository is for 360SISR introduced in the following paper

[Akito Nishiyama](https://github.com/Anishishi), [Satoshi Ikehata](https://satoshi-ikehata.github.io/), [Kiyoharu Aizawa](https://www.hal.t.u-tokyo.ac.jp/~aizawa/), "360° SINGLE IMAGE SUPER RESOLUTION VIA DISTORTION-AWARE NETWORK AND DISTORTED PERSPECTIVE IMAGES", ICIP 2021, [[Paper]](https://ieeexplore.ieee.org/document/9506233) 

The code is built on [RCAN (PyTorch)](https://github.com/yulunzhang/RCAN)

## Contents
1. [Introduction](#Introduction)
2. [Dataset](#Dataset)
3. [Citation](#Citation)
4. [Acknowledgements](#Acknowledgements)
5. [Contact](#Contact)

## Introduction
Effective 360° imaging requires a very high resolution because the field of view is extraordinarily high. Single-image super-resolution (SISR) applied to 360° imaging has the potential to solve the resolution/quality problem in this modality. In this paper, we exploit existing perspective SISR networks to address this problem by (1) introducing a distortion map as an additional input with the 360° distortion-aware loss function, and (2) augmenting the training 360° images by distorting the perspective images. We also present a new 360° image dataset from YouTube for training. Our extensive experiments show that how each component contributes to the better transfer from the perspective domain to the 360° domain and merging all the ideas leads to the best performance in quantitative and qualitative ways for the 360° SISR task.

## Dataset
This dataset is for research purposes only and is not for commercial use.  
If you need the YouTube360 data, please contact us. We will share the download link.

## Citation
If you find the dataset helpful in your resarch or work, please cite the following paper.
```
@INPROCEEDINGS{9506233,
  author={Nishiyama, Akito and Ikehata, Satoshi and Aizawa, Kiyoharu},
  booktitle={2021 IEEE International Conference on Image Processing (ICIP)}, 
  title={360° Single Image Super Resolution via Distortion-Aware Network and Distorted Perspective Images}, 
  year={2021},
  volume={},
  number={},
  pages={1829-1833},
  doi={10.1109/ICIP42928.2021.9506233}}
```

## Acknowledgements
This code is built on [RCAN (PyTorch)](https://github.com/yulunzhang/RCAN) and [EDSR (PyTorch)](https://github.com/thstkdgus35/EDSR-PyTorch). We thank the authors for sharing their codes of RCAN and EDSR.


## Contact
If you have any question, please feel free to send an e-mail to aki.nishi.work@gmail.com.