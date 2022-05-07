CS657A: Group Project
Topic - Image Clustering using Topic Modelling

Abstract - 

"We can't go on a trip without taking hundreds of photographs. With the rapid growth in technology, it is easier to take pictures and can store them in large. 
As a result we ended up taking similar images multiple times till we get a perfect shot. Manually going through such huge collections of images and clustering into one is a tedious job.  
Our problem statement is inspired from the same problem. The main goal of this report is to predict the topics of images and then combine them into one cluster based on topics."

To run the code-

We have run the experiments on kaggle so it is recommended that please upload the notebook on kaggle and the data provided in the link below.

Datasets link - 
1.  Flickr8k - https://www.kaggle.com/datasets/adityajn105/flickr8k
2.  Microsoft COCO - https://cocodataset.org/#download

For COCO you don't need to download, it'll be downloaded automatically from the script itself. 
You just need to change variable "data_name" - choices = ['flickr8k', 'coco']

Results and all other plots are there in the zip folder.
LOGS are also there in the folder which was generated while training the model.

Data Folder contains 
1. flickr8k-resutls - It contains the plots of training vs validation loss for different sets of topics and prediction of topics on test data. It also has one directory of predicted topics.
2. coco-resutls - It contains the plots of training vs validation loss for different sets of topics and prediction of topics on test data. It also has one directory of predicted topics.
3. final-ir-proj.ipynb - Main code
4. Group_12_IR_Final_Report.pdf - Main report
5. logs.txt - It contains the logs of training process.
6. ReadME.md - Readme file.
