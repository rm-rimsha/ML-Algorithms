# Machine Learning Algorithms Implementation

This project includes implementation of ML algorithms from scratch as well as available implementations.

**1. Simple Linear Regression**

  **Dataset**

   Used Housing dataset from Kaggle
      
   Cleaned the dataset to remove any missing or irrelevant data.
      
   Processed the dataset for feature engineering, including ordinal encoding, correlation and mutual information to select features.
   
      
  **Model Training**

    Initially, the model did not converge with different combinations of epochs and learning rates.
    
    Normalized the dataset using MinMaxScaler, which improved convergence.
    
    Achieved an MSE of 0.014 and a cost of 0.0199 with 100 epochs and a learning rate of 0.5.
      
![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/26bf03da-0665-4842-a823-390c38cd85f5)

![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/880064b9-f2f7-46ed-bbe2-993a68427de8)


  **Plotting and Visualization**

    Plotted the dataset and the line of best fit.
    
    Observed that the predicted and real values had minimal difference.

![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/f16f6741-a7c6-4ab7-8840-f53cdb1b79a3)


![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/e0607894-5e47-4d10-a1a7-8c1ec9a57e68)


**2. Logistic Regression**

  **Dataset**

   Used Heart Disease dataset from Kaggle
      
   Cleaned, Preprocessed, and normalized the dataset using Python 

   Analyzed the dataset in Tableau 

   ![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/61a0424c-77b3-4481-a261-b62b17c3f3f9)

   
      
  **Model Training**

   Initially, the model did not converge. However, the cost reduced due to the normalization of features using Normalization Techniques such as Min-Max and Z-Score. The Xavier Weight initialization played a vitol role to improve the accuracy of the model. 

   ![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/5cceea32-ceda-44dd-8862-690a2b7b41ab)

   ![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/2051a3d5-1412-4912-8560-5a3bec8ccbbf)



_**Tools:**_

    Pandas
    Numpy
    Matplotlib
    Seaborn
    Sklearn

