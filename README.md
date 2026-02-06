<h1 align="center"> Weather Image Classification </h1>

---

## 📚 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Approach](#approach)
- [Classes](#classes)
- [Results](#results)
- [Technology Stack](#teck-stack)
- [Licence](#licence)

---

## 🔍 Overview

This program uses Python and the Tensorflow / Keras modules to classify Weather Images from a Kaggle dataset.

---

## 📊 Dataset

Download from [OFFICIAL](https://www.kaggle.com/datasets/jehanbhathena/weather-dataset)

---

## 🧠 Approach

The [ipynb](classifier.ipynb) file includes the basic model as well as 4 more variations
(LR, Optimizers , Dropout Rates , Pre-trained models and Data Augmentation). 
The models were trained in 20 epochs, with a MobileNetV2/ResNet150V2 including early stopping for overfitting prevention. The results and the plots are being shown in the [ipynb](classifier.ipynb)  as well as the commentary.

** Hyperparameters**


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

## 📊 Results 🚧(under construction)🚧

| Variation        | Characteristics | Plots |
| :--------------- | :-------------- | :--- |
| **Base Model**   | **Optimizer:** Adam<br>**Learning Rate:** 0.0001<br>**Dropout:** 0.3 | |
| **Variation #1** |                  | |
| **Variation #2** |                  | |
| **Variation #3** |                  | |
| **Variation #4** |  (preexisting +):**<br>rotation_range = 30<br>width_shift_range = 0.2<br>height_shift_range = 0.2<br>brightness_range = (0.5, 1.5)                 | |

5) Variation #4 (More data aug)
   ```text
   # preexisting +
   rotation_range=30,
   width_shift_range=0.2,
   height_shift_range=0.2,
   brightness_range = (0.5, 1.5),
  
---

## 🛠️ Technology Stack

- **Language:** Python 3.12.12
- **Modules:** Tensorflow/Keras, Numpy, Matplotlib (& other)
- **Platform:** Google Colab

---

## ⚖️ Licence
See the [Licence](LICENCE.md/) 
