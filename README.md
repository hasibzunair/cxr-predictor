## Chest X-ray disease predictior

This is a package for predicting radiological labels from chest X-ray images.

### Getting started

To use the code, first clone the repo using:
```
git clone https://github.com/hasibzunair/cxr-predictor.git
```

Navitage to the project folder and create a new working environment.
```
conda create -n cxr-predictor python=3.6 anaconda
```

Then install the following dependencies. TensorFlow is version 2.2 at the time of writing.
```
pip install -U efficientnet
pip install opencv-python
conda install -c anaconda tensorflow-gpu
conda install -c conda-forge keras==2.3.1
```

You are all setup!

### Usage
TODO.

### Models
TODO.

### Results
TODO.

### TODO (literally!)
* Train an EfficientNet on CheXpert
	* Preprocess data
		* Resize
		* Convert to TFRecords format
	* Setup data pipeline using tf.data
	* Transfer learning
	* Save model
* Serve model, test locally
* Add features


