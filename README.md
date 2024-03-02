# Mined-2024-Hackathon
## Image Classification
## Cactus


**Problem Statement:** We are basically looking to build a tool that can classify Life Science images like Microscopies 
(confocal, light, fluorescence, and electron), Histology Slides, Pathology Slides, Western blot 
bands, Gel Electrophoresis, Flow Cytometry (FC), Fluorescence activated cell sorting (FACS), 
Cell Culture, etc.<br>
Input – Scientific Image (individual single image) <br>
Output – Which image class does it belong.

## Dataset
Repository for BioFors (Biomedical Image Forensics) Dataset and MONet (Model for duplication detection in biomedical images)<br>
Download [Dataset](https://drive.google.com/file/d/1UVSJ6h7r8pmOWYZkqWeAZ_YvwbFr1wV3/view?usp=sharing),
[JSON label file](https://github.com/vimal-isi-edu/BioFors/tree/main/annotation_files)

## Description
In the dataset mentioned above, there are 4 labelled classes which are to be classified.
The dataset and the json file with labels were linked at first and then a labelencoder was used to normalize the labels.
Then for training the dataset was divided into x_train,y_train,x_test and y_test with the testing sets being 25% of the original
size of the dataset. For image preprocesing the image size of 50x50 was taken as the standard size.<br>
For this type of image classification we have used the VGG16 (pretrained model) which has lead to a 98.152% prediction accuracy.<br>
The Notebook is attached with a short video demo.
