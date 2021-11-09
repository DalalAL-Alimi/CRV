# Compression and Reinforced  Class Separability in Hyperspectral Image
This is the main code of the paper "A Novel Multi-hybrid Deep Learning Model with Compression and Reinforced Variation for Hyperspectral Images Classification", which is [here](https://doi.org/10.3390/rs11212525)

## Abstract
In Hyperspectral (HS) images, dimensionality reduction methods (DRM) play a critical role in reducing the input data dimension and complexity. Although the deep learning methods (DLM) have presented very aggressive achievements, the preprocessing methods and DRM are very important to enhance the learning of DLMs. This study introduces a novel DRM called Compression and Reinforced Variation (CRV) to reduce the input data dimension. The CRV is an effective method to minimize the gap between the big and small related data of the same class and omits the noise and redundant data. It selects the most informative features and normalizes them to enhance that data distribution before inserting them into the learning model. The learning model of this study is multi-hybrid deep learning (MHDL) model to improve the extraction of multi-class Hyperspectral images and spectral-spatial features. MHDL model employs hyper layers of conventional neural network and batch normalization to avoid overfitting and normalizing the training. The proposed CRV provides a considerably effective way to reduce the HS images dimension and enhance the final classification accuracy of the MHDL model. Moreover, CRV is the best to provide high accuracy in a short time when it is compared with other common DRMs. Also, CRV-MHDL was compared with seven existing methods for three different datasets, and it outperforms all of them. 


#### The main framework of the study
![alt text](https://github.com/DalalAL-Alimi/CRV-/blob/main/MainF.png)


<dl>
  <dt>The requerments:</dt>
  
> Tensorfolow 2.6.0
</dl>

---
#### The time of the five preprocessing and reducing dimensionality methods.
![alt text](https://github.com/DalalAL-Alimi/CRV-/blob/main/preprocessing_time.png)

> **The results of Indian Pines (IPs) dataset:**

| Ground Trouth        | Production           |
| ------------- |:-------------:|
| ![alt text](https://github.com/DalalAL-Alimi/CRV-/blob/main/ground_truth_IP_model1.png)      | ![alt text](https://github.com/DalalAL-Alimi/CRV-/blob/main/CRV_MHDL.png) |

## Citation
#### We would appreciate a citation to the original paper if you use any part of this code (CRV + MHDL or anyone) for your research works.
```
{
  @Article{rs11212525,
  AUTHOR = {AL-Alimi, Dalal and Shao, Yuxiang and Feng, Ruyi and Al-qaness, Mohammed A. A. and Elaziz, Mohamed Abd and Kim, Sunghwan},
  TITLE = {Multi-Scale Geospatial Object Detection Based on Shallow-Deep Feature Extraction},
  JOURNAL = {Remote Sensing},
  VOLUME = {11},
  YEAR = {2019},
  NUMBER = {21},
  ARTICLE-NUMBER = {2525},
  URL = {https://www.mdpi.com/2072-4292/11/21/2525},
  ISSN = {2072-4292},
  DOI = {10.3390/rs11212525}
  }
}
```

https://www.google.com.hk/search?q=markdown+cheat+sheet&newwindow=1&source=hp&ei=dBV1YaHTJqKQxc8P1YSvsAY&iflsig=ALs-wAMAAAAAYXUjhCiA2tsJz4NyHUYYVJKLiojiyz3I&oq=markdown+cheat+sheet&gs_lcp=Cgdnd3Mtd2l6EAMYADIICAAQgAQQsQMyCAgAEIAEELEDMggIABCABBCxAzIICAAQgAQQsQMyCAgAEIAEELEDMggIABCABBCxAzIICAAQgAQQsQMyCAgAEIAEELEDMggIABCABBCxAzIFCAAQgARQClgKYLsaaABwAHgAgAGnBIgBpwSSAQM1LTGYAQCgAQE&sclient=gws-wiz
