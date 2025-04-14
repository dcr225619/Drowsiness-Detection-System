# Drowsiness-Detection-System

## Get Started

Install the required dependencies with: pip install -r requirements.txt --upgrade.

You might need to download **cmake** (https://cmake.org/download/) to build dlib.

### Download Dataset and Pretrained Model

Dataset1: https://www.kaggle.com/datasets/rakibuleceruet/drowsiness-prediction-dataset/data

Dataset2: https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd

Facial Landmark Detection Model (shape_predictor_68_face_landmarks.dat): https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat

Set the dataset path as the following:
<pre>
```
Drowsiness-Detection-System/
│
├── Driver Drowsiness Dataset1/
│   ├── 0 FaceImages/
│   │   ├── Active Subjects/
│   │   └── Fatigue Subjects/
│   ├── Active Subjects (empty folder created for CNN.ipynb)/
│   └── Fatigue Subjects (empty folder created for CNN.ipynb)/
│
├── Driver Drowsiness Dataset2/
│   ├── Active Subjects/
│   ├── Fatigue Subjects/
│   └── masked (empty folder created for CNN_2.ipynb)/
│       ├── Active Subjects (empty folder created for CNN_2.ipynb)/
│       └── Fatigue Subjects (empty folder created for CNN_2.ipynb)/
```
<pre>


### Train CNN models
<pre>
```
run CNN.ipynb

run CNN_2.ipynb
```
<pre>

### Run Detection System

This may require camera permissions.

<pre>
```
run CNN+EAR.ipynb

run CNN+EAR2.ipynb
```
<pre>
