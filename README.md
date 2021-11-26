# mushroom_classification
- Classification of mushroom whether it is edible or poison.
- Data set downloaded from Kaggle.

## Fuel Efficiency Prediction
## [Click here to listen the audio](https://drive.google.com/file/d/1WZ7OD5mo7NNVNpukec2eRj1jqAIyjtDk/view?usp=sharing)
# Introduction:
- Context: The data is technical spec of cars. The dataset is downloaded from UCI Machine Learning Repository
- Content:
     - Title: Auto-Mpg Data

- This dataset is a slightly modified version of the dataset provided in the StatLib library. In line with the use by Ross Quinlan (1993) in predicting the attribute "mpg", 8 of the original instances were removed because they had unknown values for the "mpg" attribute. The original dataset is available in the file "auto-mpg.data-original".

- "The data concerns city-cycle fuel consumption in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5 continuous attributes." (Quinlan, 1993)

- Attribute Information:

    - mpg: continuous
    - cylinders: multi-valued discrete
    - displacement: continuous
    - horsepower: continuous
    - weight: continuous
    - acceleration: continuous
    - model year: multi-valued discrete
    - origin: multi-valued discrete
    - car name: string (unique for each instance)


Here is the link of the dataset : https://www.kaggle.com/uciml/autompg-dataset

## Goal:
Predicting the fuel efficiency of cars

## Libraries used :
The required libraries for this project work
- Numpy==1.19.2
- Pandas==1.2.4
- Matplotlib==3.4.2
- Sklearn
- Seaborn

## Data Visualization :
![image](https://user-images.githubusercontent.com/79050917/143542394-322637e5-95d8-413f-9db5-f84a194500db.png)
- Countplot of cylinder column

![image](https://user-images.githubusercontent.com/79050917/143542444-a5e1d08a-d73b-4a68-a565-6662b21505eb.png)
- Countplot of model_year column

![image](https://user-images.githubusercontent.com/79050917/143542516-9662f911-683c-4dab-8738-8a7b9b1dbe70.png)
- Histogram of mpg column

![image](https://user-images.githubusercontent.com/79050917/143542587-afb10966-6f83-4065-b2e3-dda107e3575d.png)
- histogram of displacement column

I have used RandomForestRegressor, LogisticRegression, DecisionTreeClassifier.

## Compaing the accuracy of models used:
Accuracy scores:
- RandomForestRegressor : 87.47275424730756
- Linear Regression : 99.13394166672107
- Lasso regression : 79.7450859009941
- As the accuracy of linear regression is more i have used linear regression to predict the output of test data.

## Conclusion:
- linear Regression is used to train the data.
- Goal is to predict the fuel efficiency using Linear regression.


----------------------------------------------------------------------------------

## Cat and Dog Image Classification
## [Click here to listen the video]()
# Introduction:
The Asirra data set
- Web services are often protected with a challenge that's supposed to be easy for people to solve, but difficult for computers. Such a challenge is often called a CAPTCHA (Completely Automated Public Turing test to tell Computers and Humans Apart) or HIP (Human Interactive Proof). HIPs are used for many purposes, such as to reduce email and blog spam and prevent brute-force attacks on web site passwords.
- Asirra (Animal Species Image Recognition for Restricting Access) is a HIP that works by asking users to identify photographs of cats and dogs. This task is difficult for computers, but studies have shown that people can accomplish it quickly and accurately. Many even think it's fun! Here is an example of the Asirra interface:
- Asirra is unique because of its partnership with Petfinder.com, the world's largest site devoted to finding homes for homeless pets. They've provided Microsoft Research with over three million images of cats and dogs, manually classified by people at thousands of animal shelters across the United States. Kaggle is fortunate to offer a subset of this data for fun and research. 

Image recognition attacks
- While random guessing is the easiest form of attack, various forms of image recognition can allow an attacker to make guesses that are better than random. There is enormous diversity in the photo database (a wide variety of backgrounds, angles, poses, lighting, etc.), making accurate automatic classification difficult. In an informal poll conducted many years ago, computer vision experts posited that a classifier with better than 60% accuracy would be difficult without a major advance in the state of the art. For reference, a 60% classifier improves the guessing probability of a 12-image HIP from 1/4096 to 1/459.


Here is the link of the dataset : https://www.kaggle.com/c/dogs-vs-cats/data

## Goal:
CLassification of dog and cat

## Libraries used :
The required libraries for this project work
- Numpy==1.19.2
- Pandas==1.2.4
- Matplotlib==3.4.2
- Sklearn
- Seaborn

## Data Visualization :
![image](https://user-images.githubusercontent.com/79050917/143545649-2306b0e7-4832-408e-a69d-3a046ba8422d.png)
- Countplot of dog and cat

![image](https://user-images.githubusercontent.com/79050917/143545736-725faea4-8269-4a05-a93c-44116ab8ef9a.png)
- pictures of cat and dog

I have used keras to train the model.


## Conclusion:
- Used keras to classify the pictured into cat and dog
- the number of epochs used are 30.















