# Weather Image Classification

## Overview

This program uses Python and the Tensorflow / Keras modules to classify Weather Image from a Kaggle dataset.

** Runned and Tested in Google Colab **

## Dataset

This dataset contains 6862 images of different types of weather, it can be used to implement weather classification based on the photo.

https://www.kaggle.com/datasets/jehanbhathena/weather-dataset

## Classes for Classification

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

## Approach / Methodology

There was a testing of parameters in the model(lr, different optimizers , dropout rates , pre-trained models and data-augmentation). The model was trained in 20 epochs, with a MobileNetV2/ResNet150V2 with early stopping for overfitting prevention. The results and the plots are being shown in the .ipynb file as well as the commentary.

## References

  1. https://www.youtube.com/watch?v=oHGVDtgGbGo
  
  2. https://chatgpt.com
  
  3. https://www.youtube.com/watch?v=FXKMmilL70w
  
  4. https://community.deeplearning.ai/t/include-top-parameter-and-usage-of-custom-model-for-transfer-learning/260359/5
  
  5. https://www.geeksforgeeks.org/top-pre-trained-models-for-image-classification/
  
  6. https://www.youtube.com/watch?v=F8uFAkHfK18
  
  7. https://www.youtube.com/watch?v=LPGAGg3c8SE
