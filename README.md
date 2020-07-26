# Drowsiness Detector using OpenCV

## Requirements

```IMPORTANT

Download shape_predictor_68_face_landmarks.dat from http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2

numpy==1.15.2
dlib==19.16.0
pygame==1.9.4
imutils==0.5.1
opencv_python==3.4.3.18
scipy==1.1.0
Use pip install -r requirements.txtto install the given requirements.

```
### The facial landmarks produced by dlib are an indexable list

![alt text](https://github.com/rohitdubey03/Drowsiness-Detector-OpenCV/blob/master/facial_landmarks_68markup-768x619.jpg)

#### Facial landmark prediction is the process of localizing key facial structures on a face, including the eyes, eyebrows, nose, mouth, and jawline.

### Our drowsiness detector hinged on two important computer vision techniques:

⋅⋅* Facial landmark detection
⋅⋅* Eye aspect ratio

