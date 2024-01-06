# Siamese Network Deep Learning Model: Utilizing Audio Data Features for Similarity Measurement in Application

## Description
- **People**: Haewon Jeon, Hwajung Lee, Haim Lee, Hyunju Song
- **Abstract**: This is the project for UGRP(Undergraduate Group Research Program) in DGIST. Through this project, we wanted to create a deep learning model that verifies the similarity of music.

## Files

- **training**: Files for training deep learning models
  - [Siamese_model_MFCC.ipynb](training/Siamese_model_MFCC.ipynb): Siamese network model trained with MFCC data
  - [Siamese_model_SG.ipynb](training/Siamese_model_SG.ipynb): Siamese network model trained with Spectrogram data
  - [Siamese_model_CG.ipynb](training/Siamese_model_CG.ipynb): Siamese network model trained with Chromagram data
  - [Siamese_model.ipynb](training/Siamese_model.ipynb): Enhanced performance version of the siamese network
- **test**: Files for testing deep learning models
  - [Model_test.ipynb](test/Model_test.ipynb): Verifying Model Performance with Test Dataset
- **data augmentation**:
  - File for data augmentation: Implementing data augmentation by modifying keys and introducing noise
  - [data augmentation.ipynb](/data_augmentation.ipynb)

## Required packages
- **tensorflow**: ```2.1.0```
- **keras**: ```2.2.4-tf```
- **sklearn**: ```1.0.2```
- **scipy**: ```1.7.3```
- **numpy**: ```1.21.5```
- **matplotlib**: ```3.5.3```
- **h5py**: ```2.10.0```
