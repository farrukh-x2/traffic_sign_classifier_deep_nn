## Traffic Sign Recognition Classifier

### Overview

This project uses deep neural networks and convolutional neural networks to classify traffic signs. A model is trained so it can decode traffic signs from natural images by using the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). After the model is trained, it is tested on new images of traffic signs found on the web.

The Project
---

The goals of this project are achieved following the steps below:

* Load and visualize the German Traffic Sign Dataset.
* Preprocess and separate training and validation datasets. Test set is already provided.
* Design and implement a deep learning model that learns to recognize traffic signs.
* Model training and tuning of hyperparameters.
* Determine accuracy of the model and save it for later use.
* Test model on images from outside the dataset and check confidence of predictions.


Files
---
* `test_images` test images downloaded from the web
* `checkpoint`, `lenet`, `lenet.meta` are files that contain the saved model
* `signnames.csv` a dictionary that assigns labels to the dataset of traffic sign images.

#### Dataset

Running the first couple of cells will download and unzip the required dataset. The [dataset](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/581faac4_traffic-signs-data/traffic-signs-data.zip) is pickled where the images have already been resized to 32x32.

Notebook
---
The `deep_nn_traffic_sign_classifier.ipynb` notebook goes in thorough details of each of the steps laid out above with accompanying images.
