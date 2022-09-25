# Compression and Reinforced  Class Separability in Hyperspectral Image
This is the main code of the paper "Compression and Reinforced Class Separability in Hyperspectral Image", which is [here](https://doi.org/10.1016/j.asoc.2022.109650)

## Abstract
In Hyperspectral images (HSI), dimensionality reduction methods (DRM) play a critical role in reducing the input data dimension and complexity. As much as the deep learning methods (DLM) have presented very aggressive achievements, preprocessing methods and DRM are very important to enhance the learning of DLMs. This study introduces a novel DRM called Compression and Reinforced Variation (CRV), which is used to reduce the input data dimension. The CRV minimizes the gap between the big and small related data in each class and omits the noise and redundant data. It selects the most informative features and normalizes them to enhance data distribution before inserting them into the learning model. The learning model of this study is multi-hybrid deep learning (MHDL) model to improve the extraction of multi-class HSI and spectral-spatial features. MHDL is a novel classification model that includes hybrid layers of conventional neural networks and batch normalization to avoid overfitting, normalizing the training, and extracting the spectral-spatial features for HSI. The proposed CRV provided highly efficient methods for reducing the HSI dimension and improving the classification accuracy of the MHDL model. In contrast to other conventional DRMs, CRV gave the highest accuracy in the shortest time. CRV-MHDL was also compared to seven existing classification models for three distinct datasets, and the findings demonstrated that the CRV-MHDL outperforms all of them by more than 2%. 


### The operation of the compression and reinforced variation (CRV) method
![alt text](https://github.com/DalalAL-Alimi/CRV-/blob/main/images/1.PNG)

### The main framework of the study
![alt text](https://github.com/DalalAL-Alimi/CRV-/blob/main/images/MainF.png)


### The requested packages:
 
  
> - Tensorfolow 2.6.0 
> - keras 2.10.0 
> - matplotlib 3.53 
> - numpy 1.23.2 
> - pandas 1.4.4 
> - plotly 5.10.0 
> - scikite-image 0.19.3 
> - seaborn 0.12.0 
> - sklearn 
> - spectral 0.22.4 


---
### The time of the five preprocessing and reducing dimensionality methods.
![alt text](https://github.com/DalalAL-Alimi/CRV-/blob/main/images/preprocessing_time.png)

> **The results of Indian Pines (IPs) dataset:**

| Ground Trouth        | Production           |
| ------------- |:-------------:|
| ![alt text](https://github.com/DalalAL-Alimi/CRV-/blob/main/images/ground_truth_IP_model1.png)      | ![alt text](https://github.com/DalalAL-Alimi/CRV-/blob/main/images/CRV_MHDL.png) |

## Citation
### We would appreciate a citation to the original paper if you use any part of this code (CRV + MHDL or anyone) for your research works.
```
{
  @Article{ALALIMI2022109650,
  AUTHOR = {Dalal AL-Alimi and Zhihua Cai and Mohammed A.A. Al-qaness and Abdelghani Dahou and Eman Ahmed Alawamy and Sakinatu Issaka},
  TITLE = {Compression and reinforce variation with convolutional neural networks for hyperspectral image classification},
  JOURNAL = {Applied Soft Computing},
  YEAR = {2022},
  issn = {1568-4946},
  doi = {https://doi.org/10.1016/j.asoc.2022.109650},
  url = {https://www.sciencedirect.com/science/article/pii/S1568494622006998},
  }
}
```
