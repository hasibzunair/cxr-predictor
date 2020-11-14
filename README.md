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
| EfficientNet B1 | NIH | 224x224 | -- |

### 4. Inference

Demo notebook for model trained on CheXpert is at https://github.com/hasibzunair/cxr-predictor/blob/main/notebooks/chexpert_inference.ipynb

### 5. References
TODO.



