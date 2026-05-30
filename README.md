# Pneumonia_Detection_Project
Detects whether a patient has pneumonia from xray images 

STEP 1: DOWNLOAD DATASET
Dataset: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download

File Structure:
chest_xray/
├── train/
│ ├── NORMAL/
│ └── PNEUMONIA/
├── test/
│ ├── NORMAL/
│ └── PNEUMONIA/
└── val/ (optional)

STEP 2: UPLOAD DATASET TO YOUR DRIVE AND CHANGE FILE PATHS TO CONVENIENCE
The following project is done in google collab, for doing on IDEs remove drive mount code and change file paths to the structure of storing in your system

STEP 3: PREPROCESSING OF IMAGES
Images resized to 224*224
- Pixel values normalized to range [0,1]
- Data augmentation applied:
  - Rotation
  - Zoom
  - Horizontal flip
  
STEP 4: TRAIN THE MODEL
The model is trained with 10 epochs and batch size 32. It is based on a CNN architecture

STEP 5: TEST THE MODEL
Test the model on an xray image
