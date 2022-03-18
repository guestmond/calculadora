# VisuWeigh

Project to develop a data pipeline and machine learning models to estimate cattle weight based on visual information. 
 
## Introduction 
 The cattle industry relies heavily on weight information for sales and marketing as well as animal health. The traditional method of weighing cattle is with a mechanical scale that cattle walk onto. These scales are expensive to install and maintain and therefore many smaller cattle producers do not have these scales installed in their facilities. 
 An expert cattle buyer can estimate the weight of a cow by visually looking at the cow. If this visual estimation could be performed with computer vision, cattle producers can quickly and automatically track the weight of their animals without having to transport them to a scale or consult an expert. 
 
## Methods
 The key to a good prediction CNN is good data. The focus of this project is to retrieve and clean large amounts of data in an automated fashon to train a CNN on predicting cattle weight. 

## To Do:
- [x] Create Raw Collection Pipline 
- [x] Create Data Cleaning Pipline
- [x] Train on CNN Model
- [x] Compare Transformer and CNN Models
- [ ] Scale up Data
- [ ] Automate Cleaning and Training
- [ ] Sumbit Paper to AI Conference

## Instructions
Files are under construction... 
Debuggig may be necissary. Run at your own risk.


## Models in Action
![image](https://user-images.githubusercontent.com/28244647/156103607-91e49917-0ef2-49a9-a644-7e792b2a2cdb.png)

These models vary in performance with each image. Overall the Xception model achieves the highest performance on new data. On the first image where the image is distorted, none of the models perform well. This is a good sign that the models are fitting the data in the expected manner. 
