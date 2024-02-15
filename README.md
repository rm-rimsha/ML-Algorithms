# ML-Algorithms

This project includes implementation of ML algorithms from scratch as well as available implementations.

**1. Simple Linear Regression**

  **Dataset**

      - Used Housing dataset from Kaggle
      - Cleaned the dataset to remove any missing or irrelevant data.
      - Processed the dataset for feature engineering, including ordinal encoding, correlation and mutual information to select features.

      ![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/c7fad140-c4b2-445d-a462-68313514af54)

      ![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/60dae495-84a8-4d9b-8aa9-35b1c185e832)

      
      
  **Model Training**

      - Initially, the model did not converge with different combinations of epochs and learning rates.
      - Normalized the dataset using MinMaxScaler, which improved convergence.
      - Achieved an MSE of 0.014 and a cost of 0.0199 with 100 epochs and a learning rate of 0.5.

      ![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/b4b83ed5-46f4-4cc8-9130-54369f600973)

      ![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/49cf9d21-723b-42a8-af06-8396274ac737)

  **Plotting and Visualization**

      - Plotted the dataset and the line of best fit.
      - Observed that the predicted and real values had minimal difference.

      ![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/84745901-cab5-47a7-8390-6be99b569835)

      ![image](https://github.com/rm-rimsha/ML-Algorithms/assets/105241371/f1632ed3-0985-41c6-9189-e663ce5d79e2)




- Tools:
    Pandas
    Numpy
    Matplotlib
    Seaborn
    Sklearn

