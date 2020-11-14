#### WORK IN PROGRESS
## Predict different radiological conditions from chest X-ray images 

This is a package for predicting different radiological conditions from chest X-ray images.

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
| EfficientNet B1 | NIH | 224x224 | [NIH_EfficientNetB1_res224.h5](https://github.com/hasibzunair/cxr-predictor/releases/latest/download/NIH_EfficientNetB1_res224.h5) |

### 4. Inference

Demo notebooks are available in `notebooks/`

### 5. References
TODO.



