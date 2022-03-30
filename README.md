# ICADL_2021

This repository contain 3 directory

a) Raw_Dataset - NCG Dataset - Train, Trial and Test
b) Raw_CSV_Dataset - CSV Format of Raw Dataset
c) Preprocessed_Dataset - Preprocessed Dataset used for training the model

**Steps to train the model**

All file path should start with Prepocessed_Dataset

Train the model with following command
**python multitasking-both-scaffold.py**

Inference for test data
**python test.py**

Other Helper files
Heading.ipynb, Test_Heading.ipynb - Used OCR to extract Main Heading and Sub Heading of a sentence in a paper
NCG_Preprocessing.ipynb - Convert Raw dataset into CSV format
Submission - Generates Submission folder on test_data. Submit it to Codalab Task Page for results
