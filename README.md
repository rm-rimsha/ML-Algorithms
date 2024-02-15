# ML-Algorithms

This project includes implementation of ML algorithms from scratch as well as available implementations.

**1. Simple Linear Regression**

  **Dataset**

   Used Housing dataset from Kaggle
      
   Cleaned the dataset to remove any missing or irrelevant data.
      
   Processed the dataset for feature engineering, including ordinal encoding, correlation and mutual information to select features.

![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/15b2a87e-8a20-4d3e-b0b1-c3920acfaa23)

![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/8a6221fd-27bb-4631-9cba-802d5f9a9ab1)

![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/ce482674-14d7-4fcb-998c-0902caca45bf)

      
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



_**Tools:**_

    Pandas
    Numpy
    Matplotlib
    Seaborn
    Sklearn

