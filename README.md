# <div align='center'> Modeling the Histopathology of Breast Cancer </div>
## <div align='center'>Imaging breast tissue for invasive cancer </div>

## Introduction

Cancer has fascinated me since my high school days. It is a unique disease in that it is our own cells that cause us great harm. I obtained my Master's Degree by analyzing the disease-free survival of women with a benign (but potentially becoming malignant) form of breast cancer known as Ductal Carcinona *in situ*.

For this project, I wanted to look at breast cancer again, this time looking at a more aggresive form known as Invasive Ductal Carcinoma (IDC). this is a very serious form of breast cancer, and catching it treating it early is vital.

5-year survival for IDC located:*
* Only in the breast: 99%
* Regional lymph nodes: 86%
* Distant part of the body: 27%

To help identify IDC as early as possible, I sought to design a convolutional neural net (CNN) capable of identifying IDC from tumor specimen images.

To get a look at what the images look like, I have included an image of healthy breast histology and IDC breast histology below.


**Health Breast Histology<sup>1</sup>**

![normal](img/normal_breast_histology.jpg)

**IDC Breast Histology<sup>2</sup>**

![invasive](img/invasive-ductal-carcinoma.jpg)

<hr>

## Data

The data consisted of 277,524 breast histopathologic images.
* 198,738 IDC negative
* 78,786 IDC positive

### Training Ddta set
222,020 images

### Validation data set

* 39,672 IDC negative
* 15,832 IDC positive

<hr>

## Results

![ROC curve](img/roc_curve.png)

<hr>

## Sources

<sup>1</sup>[Normal breast at low power](https://webpath.med.utah.edu/HISTHTML/NORMAL/NORM005.html)

<sup>2</sup>[pathology.jhu.edu](ttps://pathology.jhu.edu/breast/types-of-breast-cancer/)

<sup>3</sup>[cancer.net](https://www.cancer.net/cancer-types/breast-cancer/statistics)