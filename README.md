# Lab Report of Decision Tree and Random Forest

 # 1. Introduction

 This report presents the results of an Exploratory Data Analysis (EDA) and the performance evaluation of Decision Tree and Random Forest models on the Mango Leaf Dataset. The dataset contains images of mango leaves categorized into different classes. These images have been transformed into numerical features for machine learning model training.


# 2.Exploratory Data Analysis (EDA)

  # 2.1 Data Loading and Structure

     The dataset is located at "/kaggle/input/mango-leafbd" Dataset and consists of mango leaf images classified into different disease categories.
     The dataset consists of multiple classes, each representing different categories of mango leaves. The number of images per class was counted to understand the class distribution.
     
 # 2.2 Data Exploration

   1.The dataset contains images in different sizes, and unique image resolutions were identified.
   
   2.A bar plot was created to visualize the distribution of images across different classes. Each bar represents the number of images in each category, indicating that the dataset is well-balanced across classes.
   
   3.Sample images from each class were displayed to verify the dataset contents.
                        output: ![image alt](https://github.com/Riyasaha256/CSE475_lab1-mango_leaf-/blob/main/Screenshot%202025-03-05%20145746%20output1.png?raw=true)
                        
 # 2.3 Data Preprocessing
   1.The images were loaded using OpenCV and converted from BGR to RGB format.
   
   2.The images were flattened into 1D arrays to create a structured dataset suitable for machine learning models.
   
   3.A Pandas DataFrame was created with the processed image data and corresponding labels.
   

# Model Evaluation: Decision Tree vs. Random Forest

  # 3.1 Data Splitting
      1. The dataset was split into training (80%) and testing (20%) sets using train_test_split.
      
      2. Stratified sampling was used to maintain class distribution in both sets.
                       
        
      output: Training set shape: (3200, 12288), (3200,)
              Testing set shape: (800, 12288), (800,)
              
   # 3.1 Decision Tree Classifier

       1. The decision tree was trained on the numerical feature representations of the mango leaf images.

       2. It uses an entropy-based splitting criterion to select the best feature for each split.

       3.The tree structure was limited to a maximum depth of 3 to prevent overfitting.

        output: Accuracy: 0.45
                Precision: 0.39
                Recall: 0.45
                F1-score: 0.39

# confusion matrix:


output:![image alt](https://github.com/Riyasaha256/CSE475_lab1-mango_leaf-/blob/main/Screenshot%202025-03-05%20155812%20output3.png?raw=true)


![image alt](https://github.com/Riyasaha256/CSE475_lab1-mango_leaf-/blob/main/Screenshot%202025-03-05%20160141%20output4.png?raw=true)






                
           

   
           
      

     

        

 


     


 
