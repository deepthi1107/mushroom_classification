# mushroom_classification
- Classification of mushroom whether it is edible or poison.
- Data set downloaded from Kaggle.

## Ensemble Methods
## [Click here to listen the audio](https://drive.google.com/file/d/1MewRtso4wgmKkDeUFSFrHG18PV7GbvRa/view?usp=sharing)

-  It is a machine learning technique 
-  It combines several base models in order to produce one optimal model.

## Types of Ensemble Methods:
- Bagging
- Stacking
- Boosting

**_Bagging:_**
-  The goal of bagging is to reduce the variance of a decision tree classifier.
-  The objective is to create subsets of data from training sample that are chosen randomly with replacement. Each collection of subset data that chosen is used to train their decision trees.
-  Then, Bagging algorithm is used to aggregate over the Decision Trees for the most efficient predictor.
![image](https://user-images.githubusercontent.com/79050917/143415022-25390d6f-ed39-4bea-92b5-32669602ec4c.png)
![image](https://user-images.githubusercontent.com/79050917/143415812-5db0f5db-f256-4089-9982-7670a0bfd8a6.png)

**_Boosting:_**
- It is used to create a collection of predictors.
- It creates a strong classifier from a number of weak classifiers.
![image](https://user-images.githubusercontent.com/79050917/143416050-1fa60fc2-b1bb-4e8d-aff5-4ec77a6011f3.png)

**_Stacking:_**
- It learns on how to combine the predictions from multiple machine learning models.
- It uses predictions for multiple nodes(for example kNN, decision trees, or SVM) to build a new model.
![image](https://user-images.githubusercontent.com/79050917/143418238-8cf4c56f-d67f-4bd0-bc05-082807d07289.png)

**Advantages:**
- Better predictions
- Increase the efficiency
- Increase the model performance.

**Disadvantages:**
- Increases the complexity within the model.
- Takes time to evaluate.

## Conclusion:
- A minimum benefit of using ensembles is to reduce the spread in the average skill of a predictive model.
- A key benefit of using ensembles is to improve the average prediction performance over any contributing member in the ensemble.

## Data Wrangling using Pandas
## [Click here to see the video]()

- It is most importing step in data science.
- It helps in reducing the complexity of the dataset and makes easy for the model.
- Improves the model performance.
- Pandas is the open-source library which is used in data science field for data analsysis.

## Import Data:
- Its the basic for the data science project to load the dataset.
- pd.read_csv() : is widely used for loading the dataset.

![image](https://user-images.githubusercontent.com/79050917/143427957-804eb315-1e81-4c57-a851-6df70fb8f6ab.png)

## Merge the dataset:
- It is important in data science project to merge the data set when two or more data set is available when doing the project
- pd.merge() : is used to merge the datasets

![image](https://user-images.githubusercontent.com/79050917/143428229-3b07d9aa-6d23-439e-b9e0-a09e2a74fc23.png)

## Concatenation:
- It is importing in the project to concat the data sets after encoding.
- pd.concat(): is used to concatination of datasets.

## Data Cleaning:
- For droping the duplicates
- drop_duplicates() : is used to drop the duplicates
- For treating the missing values:
- df.isnull().sum(): is used to know the count of missing values
- fillna(): is used to fill the missing values.

![image](https://user-images.githubusercontent.com/79050917/143428101-3acb5e5f-4406-4606-af6f-a10aa4fb0677.png)
![image](https://user-images.githubusercontent.com/79050917/143428144-a9f9c4da-4438-404a-91fe-ebd9775ee72b.png)

## Data Analysis:
- It is important to do data analysis.
- This helps in increasing the model performance and also improves the flexibility within the data set.
- describe() : is used to draw some if the statastical information.

![image](https://user-images.githubusercontent.com/79050917/143428013-61967cc9-8236-4aea-9da0-7b0467c39a16.png)

## Export:
- It very important to store the output after building the model for thre test data.
- df.to_csv(): is widely used to export the dataset.

## Conclusion:
- Data Wrangling is the process of gathering, collecting, and transforming Raw data into another format for better understanding, decision-making, accessing, and analysis in less time.
















