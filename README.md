# Pakistani Currency Detection WebApp

## Overview
The model is developed on Teachable ML

### Model

More API functions here: https://github.com/googlecreativelab/teachablemachine-community/tree/master/libraries/image

the link to your model provided by Teachable Machine export panel
const URL = "./my_model/";

Load the image model and setup the webcam

load the model and metadata
Refer to tmImage.loadFromFiles() in the API to support files from a file picker
or files from your local hard drive
Note: the pose library adds "tmImage" object to your window (window.tmImage)

run the webcam image through the image model

predict can take in an image, video or canvas html element

#### Web App uses the model.json

#### Teachable ML

