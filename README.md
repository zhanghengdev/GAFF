# Guided Attentive Feature Fusion for Multispectral Pedestrian Detection

By Heng Zhang, Elisa FROMONT, Sébastien LEFEVRE, Bruno AVIGNON

## Introduction

<img align="center" src="https://github.com/zhangheng19931123/GAFF/blob/master/doc/gaff.png">

Multispectral image pairs can provide complementary visual information, making pedestrian detection systems more robust and reliable. To benefit from both RGB and thermal IR modalities, we introduce a novel attentive multispectral feature fusion approach. Under the guidance of the inter- and intra-modality attention modules, our deep learning architecture learns to dynamically weigh and fuse the multispectral features. Experiments on two public multispectral object detection datasets demonstrate that the proposed approach significantly improves the detection accuracy at a low computation cost. 
For more details, please refer to our [WACV paper](https://openaccess.thecvf.com/content/WACV2021/papers/Zhang_Guided_Attentive_Feature_Fusion_for_Multispectral_Pedestrian_Detection_WACV_2021_paper.pdf). 

## Results

In this repository we provide the detection results of GAFF model for [KAIST dataset](https://soonminhwang.github.io/rgbt-ped-detection/). 

| **Reasonable-aLL** | **Reasonable-day** | **Reasonable-night** | **Runtime(1080Ti)** |
|:-----:|:-------:|:-------:|:-------:|
| 6.48% | 8.35% | 3.46% | 9.34ms |

## Citing GAFF

Please cite our paper in your publications if it helps your research:

    @inproceedings{zhangguided,
      title={Guided Attentive Feature Fusion for Multispectral Pedestrian Detection},
      author={Zhang, Heng and Fromont, Elisa and Lefevre, Sebastien and Avignon, Bruno},
      booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
      pages={72--80}
    }