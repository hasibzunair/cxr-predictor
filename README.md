#### WORK IN PROGRESS
## Pretrained models for classification, segmentation and detection of different radiological conditions from chest X-ray images

This is a package with pretrained models to interpret different radiological conditions from chest X-ray images.

### 1. Getting started

To use the code, first clone the repo using:
```
git clone https://github.com/hasibzunair/cxr-predictor.git
```

Navigate to the project folder and create a new working Python 3.6 environment with `conda` or `pip`. Then install the following dependencies. 

```
pip install -r requirements.txt
```
You are all setup!

### 2. Usage
TODO.

### 3. Pretrained models

Here's the list of pretrained models that are available. Training details/codes will be added later.

| Model | Dataset | Image Size | Checkpoint |
|:---:|:---:|:---:|:---:|
| DenseNet121 | CheXpert | 224x224 | [CheXpert_DenseNet121_res224.h5](https://github.com/hasibzunair/cxr-predictor/releases/latest/download/CheXpert_DenseNet121_res224.h5) |
| EfficientNet B1 (featurewise std) | NIH | 224x224 | [NIH_EfficientNetB1_res224.h5](https://github.com/hasibzunair/cxr-predictor/releases/latest/download/NIH_EfficientNetB1_res224.h5) |
| EfficientNet B1 (0-1 normalization) | NIH | 224x224 | [NIH_EfficientNetB1_res224_rescale01.h5](https://github.com/hasibzunair/cxr-predictor/releases/latest/download/NIH_EfficientNetB1_res224_rescale01.h5) |
| Mask RCNN | RSNA Pneumonia Detection  | 224x224 | [RNSA_Pneumonia_MaskRCNN_7epochs.h5](https://github.com/hasibzunair/cxr-predictor/releases/latest/download/RNSA_Pneumonia_MaskRCNN_7epochs.h5) |
| U-Net | SIIM-ACR Pneumothorax Segmentation  | 224x224 | [SIIM-ACR_UEfficientNetB4_res256.h5](https://github.com/hasibzunair/cxr-predictor/releases/latest/download/SIIM-ACR_UEfficientNetB4_res256.h5) |
| U-Net with SWA | SIIM-ACR Pneumothorax Segmentation  | 224x224 | [SIIM-ACR_UEfficientNetB4_SWA_res256.h5](https://github.com/hasibzunair/cxr-predictor/releases/latest/download/SIIM-ACR_UEfficientNetB4_SWA_res256.h5) |

### 4. Inference
Demo notebooks are available in `notebooks/`

### 5. References
Datasets used to build the models
* [CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/)
* [NIH Chest X-rays](https://www.kaggle.com/nih-chest-xrays/data)
* [RSNA Pneumonia Detection](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data)
* [SIIM-ACR Pneumothorax Segmentation](https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation/data)

