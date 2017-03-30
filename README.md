# Deep-LeafSnap
LeafSnap replicated using deep neural networks to test accuracy compared to traditional computer vision methods.


## Installation
To run the models and code make sure you [Python](https://www.python.org/downloads/) installed. 

Install Tensorflow following the instructions [here](https://www.tensorflow.org/install/).

Install all the python dependencies:
```
pip install -r requirements.txt
```
Set Keras to use Tensorflow as backend:
```
nano ~/.keras/keras.json
```
Change your values to look something like:
```
{
    "image_dim_ordering": "tf", 
    "epsilon": 1e-07, 
    "floatx": "float32", 
    "backend": "tensorflow"
}
```
Also make sure you have OpenCV installed either through pip or homebrew. You can check if this works by running and making sure nothing complains:
```
python
import cv2
```
Download Leafsnap's image data from [here](leafsnap.com/dataset/) and extract it to the main directory by running in the directory.
