# Image Caption Generator using CNN-LSTM (InceptionV3)

## Overview
This project implements an Automatic Image Captioning System using a CNN-LSTM architecture.  
It combines InceptionV3 (CNN) for image feature extraction and LSTM (RNN) for generating meaningful captions.

The model is trained on the Flickr8k dataset, enabling it to generate human-like descriptions for images.

---


## Model Architecture
- CNN (InceptionV3) → Extracts image features  
- LSTM → Processes sequences and generates captions  
- Dense Layers → Final word prediction  

---

## Dataset
- Dataset Used: Flickr8k  
- Contains:
  - 8,092 images
  - 5 captions per image  

Dataset is automatically downloaded in the code:
- Images: Flickr8k_Dataset
- Captions: Flickr8k.token.txt

---

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- tqdm
- InceptionV3 (Transfer Learning)

---


---

## Sample Output
- Random image is displayed along with:
  - Multiple ground-truth captions  
- Model learns to generate similar captions  

---

## Results
- Model successfully learns relationships between images and text  
- Generates context-aware captions  

(Add your accuracy here if you trained the full model)

---



## How to Run
1. Clone the repository:
```
git clone https://github.com/shindevaish/InceptionV3_based_Image_Captioning.git
cd InceptionV3_based_Image_Captioning
```

2. Install dependencies:
```
pip install -r requirements.txt
```

---
