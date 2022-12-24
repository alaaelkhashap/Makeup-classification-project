# Makeup-classification-project

## Main Topic
* Image classification using manual collected dataset
* Testing the models using low resoluation images 
* Using Super Resoluation (SR) model for enhancement

## Abstract
Nowadays, most individuals, especially women, consider cosmetics to be vital. Despite this, many women and virtually all men struggle to tell different makeup products apart. The goal of this research is to create a makeup categorization system that focuses on tiny, low-quality datasets. Our dataset was personally compiled via coworkers and internet evaluations (SHEIN specifically). 500 photos make up the dataset, which is divided into 10 equal classes. Before preprocessing, the photos were scaled to 64*64 in order to deal with low-quality data. Transfer learning was the ideal method to apply because we deal with low-quality and sparse data, and Inception, ResNet, and Mobile Net were the pre-trained models that were selected.We used a baseline model that applies super-resolution using an enhanced deep super-resolution network (EDSR) approach, as well as an upgraded model that applies super-resolution using the dataset that has been scaled and resized. The baseline model's final accuracy with MobilNet was 43%, while the upgraded model's accuracy with inception was 53%. Although the SR was able to increase accuracy, the performance was not as excellent as we had hoped. With a larger dataset, we anticipate better performance.


## Dataset 
The dataset was collected manually by the team members, part of the data was from real life (pictures we took from our colleagues), and the other part was scrapped from customers' reviews on makeup websites (SHEIN). We have collected 500 images divided into 10 classes. Each class includes 50 images.

* Visualize samples from the dataset

![image](https://user-images.githubusercontent.com/60587913/209417630-89bcbeea-b6d1-42de-a794-d9604f2b607f.png)

## Methodology
* Basline Models
    - MobileNet Model
    - Inception Model
    - Resnet

* Enhanced model:
An enhanced deep super-resolution network (EDSR)  technique was applied to enhance the 64*64*3 images. Then they were fed to the pre-trained models.
The hyperparameter tuning is done for each model separately. 

  
 ## CONCLUSION AND FUTURE WORK
 The goal of this project is to develop a makeup classification system that targets low resolution (LR), small-sized manually collected datasets with perfect hyperparameter tuning and apply Super Resolution (SR) technique to assess how different SR can add to performance when used with LR data and various state-of-the-art transfer learning models (Inception, ResNet, and Mobile Net). The upgraded models take the data after applying SR using an enhanced deep super-resolution network (EDSR) approach, whereas the baseline models take the data after resizing and scaling. The Mobil-Net model, which has an accuracy of 45% and is the best for the baseline approach, is overfitted. ResNet barely attained 30%, and inception net just 0.38%.After using SR, the accuracy increased to 53%, which is still higher than the baseline but not very high. For future study, we found that accumulating more data and working with high-quality and larger-sized data might help transfer learning overcome the overfitting issue and even allow for autonomous training.
    
## contact 
![image](https://user-images.githubusercontent.com/60587913/209285099-911ab4b9-604a-45e5-8c96-ce618df56870.png)https://www.linkedin.com/in/%D9%90%D9%90alaa-elkhashap/
    
