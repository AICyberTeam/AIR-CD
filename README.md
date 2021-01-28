# AIR-CD
We build a challenging cloud detection data set called AIR-CD, with higher spatial resolution and more representative landcover types. The data set is open to the community to provide support for research in the field of cloud detection.

# 1.Introduction

AIR-CD is a GF-2 high-resolution cloud detection data set that includes 34 full scenes collected by GF-2 satellite from different regions of China from February 2017 to November 2017. To the best of our knowledge, AIR-CD may be one of the earliest publicly available remote sensing image cloud detection data sets collected from GF-2 satellite. Moreover, compared with previous data sets, the scenes in AIR-CD are more complex and diverse, so it is more challenging to achieve high-accuracy cloud detection. The images contain various land-cover types, including city, wasteland, snow, and forest. The data set consists of near-infrared and visible bands, with a spatial resolution of 4 m and a size of 7300 × 6908 pixels. Considering the radiation difference between PMS1 and PMS2 sensors in the GF-2 satellite imaging system, the scenes from both sensors are taken as experimental data to guarantee the generalization of the model. Besides, the reference cloud mask of the data set has been digitally annotated and available online. We believe that the open AIR-CD data set can help promote the research in cloud detection.

In the process of building the data set, experts manually labeled the position of the cloud in the image pixel by pixel and created a reference mask by. Considering the high spatial resolution of the GF-2 satellite image and the relatively few cloud shadows, only cloud is labeled in the reference mask. To ensure the accuracy of the label, the reference mask has been iterative inspection and correction. 

# 2.Download

To help readers to download the AIR-CD data set, we have uploaded part of the data set, including 7 original remote sensing images and corresponding labels. To facilitate the observation, we visualize the label, using white pixels to represent the cloud and black pixels to represent the background. The complete data set can be downloaded from:

BaiduNetdisk: https://pan.baidu.com/s/1WLlaJRXaxXAMfBNZ7bABPw  password: trsm

## Citation
If you find **AIR-CD** useful in your research, please consider citing:

```
@ARTICLE{9314019,
  author={Q. {He} and X. {Sun} and Z. {Yan} and K. {Fu}},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={DABNet: Deformable Contextual and Boundary-Weighted Network for Cloud Detection in Remote Sensing Images}, 
  year={2021},
  volume={},
  number={},
  pages={1-16},
  doi={10.1109/TGRS.2020.3045474}}
```
