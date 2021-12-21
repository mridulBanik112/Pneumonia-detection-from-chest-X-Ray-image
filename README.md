# Pneumonia-detection-from-chest-X-Ray-image
We have used https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia this dataset for detecting Pneumonia. This Dataset contains chest
XRay images. There are three sets. Train, Test, Validation.
We have implemented 10 different pretrained network and also experimented the effect of dropout and two customized CNN. Some of the models output were really great.
We achieved 92 percent accuracy in mobilenet with dropout layer from validation dataset which contain 618 images. MobileNet with dropout and MoileNetV2 performed perfect 
in Test set (16 images). With a few margial exception we noticed that almost all the models had better Recall score than Precision for both Validation and test set. The higher 
number of positive images in training set could be one possible reason. If training can execute by making the train set balanced, the outcome may result to better 
precision and accuracy result.
