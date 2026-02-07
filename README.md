<h1 align="center"> Weather Image Classification </h1>

---

## 📚 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Approach](#approach)
- [Classes](#classes)
- [Setup](#setup)
- [Results](#results)
- [Technology Stack](#teck-stack)
- [Licence](#licence)

---

## 🔍 Overview

This program uses Python and the Tensorflow / Keras modules to classify Weather Images from a Kaggle dataset.

---

## 📊 Dataset

Download from [OFFICIAL](https://www.kaggle.com/datasets/jehanbhathena/weather-dataset).

---

## 🧠 Approach

The [.ipynb](classifier.ipynb) file includes the basic model as well as 4 more variations
(LR, Optimizers , Dropout Rates , Pre-trained models and Data Augmentation). 
The models were trained in 20 epochs, with a MobileNetV2/ResNet150V2 including early stopping for overfitting prevention. The results and the plots are being shown in the [.ipynb](classifier.ipynb)  as well as the commentary.

---

## 🏷️ Classes

The pictures are divided into 11 classes:

  1) dew
  
  2) fog/smog 
  
  3) frost 
  
  4) glaze
  
  5) hail 
  
  6) lightning
  
  7) rain
  
  8) rainbow 
  
  9) rime 
  
  10) sandstorm
  
  11) snow

---

## ⚙️ Setup

1. Create a Google Drive folder named **Colab Notebooks**

2. Upload the `.zip` dataset into the folder
   
3. Make sure Google Drive mount is successful:
```python
from google.colab import drive
drive.mount('/content/drive')
```

4. Verify the folder exists:
```bash
!ls "/content/drive/My Drive/Colab Notebooks/"
```

5. Unzip the dataset:
```bash
!unzip -o "/content/drive/My Drive/Colab Notebooks/archive.zip" -d "/usr/local/dataset"
```

---

## 📊 Results 🚧(under construction)🚧

| Variation        | Characteristics | Plots |
| :--------------- | :-------------- | :--- |
| **Base Model**   | **Pre trained:** MobileNetV2<br> **Optimizer:** Adam<br>**Learning Rate:** 0.001<br>**Dropout:** 0.3 | <img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/92bead64-a134-4995-9e21-cd0c81d4500e" /> |
| **Variation #1** | **Pre trained:** MobileNetV2<br> **Optimizer:** Adam<br>**Learning Rate:** 0.001<br>**Dropout:** 0.5 | <img width="1189" height="490" alt="var1" src="https://github.com/user-attachments/assets/7f597f20-5176-49e0-be0f-e723f7e1e66e" />  |
| **Variation #2** | **Pre trained:** MobileNetV2<br> **Optimizer:** AdamW<br>**Learning Rate:** 0.001<br>**Dropout:** 0.5 | <img width="1189" height="490" alt="var2" src="https://github.com/user-attachments/assets/9e347784-7793-418e-9798-468501827a51" /> |
| **Variation #3** | **Pre trained:** ResNet152V2<br> **Optimizer:** AdamW<br>**Learning Rate:** 0.001<br>**Dropout:** 0.5  | <img width="1189" height="490" alt="var3" src="https://github.com/user-attachments/assets/bf29017e-c25d-495f-ba0e-8b88fb28f128" /> |
| **Variation #4** | (base model + extra Data Aug):<br>rotation_range = 30<br>width_shift_range = 0.2<br>height_shift_range = 0.2<br>brightness_range = (0.5, 1.5)  | |

---

## 🛠️ Technology Stack

- **Language:** Python 3.12.12
- **Modules:** Tensorflow/Keras, Numpy, Matplotlib (& other)
- **Platform:** Google Colab

---

## ⚖️ Licence
See the [Licence](LICENCE.md/) 
