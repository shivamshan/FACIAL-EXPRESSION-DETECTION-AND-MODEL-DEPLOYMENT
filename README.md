# FACIAL-EXPRESSION-DETECTION-AND-MODEL-DEPLOYMENT
## This is a  FACIAL EXPRESSION DETECTION project made using Convolutional Neural Networks and deployed using FLASK.

The CNN model is trained on approximately _27000 images_ that belong to seven basic facial expressions namely-</br>
* ANGRY</br>
* DISGUST</br>
* FEAR</br>
* HAPPY</br>
* NEUTRAL</br>
* SAD</br>
* SURPRISE</br></br>

The model was separately trained on 15 and 50 epochs respectively, achieving a maximum accuracy of **66.8** percent on validation set.
</br>
</br>
The model was trained on a **GPU** supported GOOGLE COLLAB NOTEBOOK as training on a simple CPU supported system was taking too much time.
</br>
</br>
The model was then deployed using **FLASK** framework on localhost.
</br>
</br>
The _camera.py_ file contains the code for reading from webcam or file and for performing facial detection.The current mode is reading from a file
that can be changed to read from webcam.
</br>
</br>
## RESULT
<img src="https://github.com/shivamshan/FACIAL-EXPRESSION-DETECTION-AND-MODEL-DEPLOYMENT/blob/master/on_image.jpg">
</br>

**It can be seen that the model misclassifes some of the expressions in the below video because of non-uniformity in the number of images available for training the model for each expression category.**
</br>
### The predictions along with the actual expression label in a video file can be viewed from this link:-</br>
<a href="https://drive.google.com/file/d/1iEdfRnqBZ7kvunusY2U8pbx2bt3uE3Kj/view?usp=sharing">Link To Video</a>
</br></br>
</br></br>
**P.S**</br>
* Anyone interested in forking this project can do so. All the major requirements to run the model are provided in _requirements.txt_ file.
</br>

* Also i would advise everyone to create a virtual environment first and install the requirements seperately in that environment.
</br>

* A GPU is a must for training as training on a cpu can take hours just for few epochs.I suggest the use of Google Collab.
</br>

* If you want to train the model locally the make sure you have the right **.dll** files and **CUDA** and **CUDNN** versions installed.
I myself had a nightmare doing so. Also make sure the GPU drivers match the requiremnets of the tensorflow version you are using.
</br>

* I suggest Tensorflow 2.0.0 with gpu support.
</br></br>

#### ALL THE NEEDED FILES ALONG WITH THE IMAGE FILES CAN BE FOUND IN THIS ARCHIVED FOLDER-
<a href="https://drive.google.com/file/d/1eVDKWdpwG4yUirXZYUAzSUcd0tkkVTjX/view?usp=sharing">DOWNLOAD COMPRESSED FILE</a>

