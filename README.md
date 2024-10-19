# Pinktober2024

Hello!! This is the team **Tech Cells**, we are a group of five girls : Maria, Lamis, Marya, Noor and isra.
We have decided to participate in the pinktober datathon and did our best in order to learn new skills wether it's machine learning or deep learning and enhance skills we already had.

## Challenge 1 :
This challenge consists of making a mchine learning model that is able to classify breast cancer tumors as cancerous or benign based of the symptoms of the cells.
Our solution for this challenge consisted in using a **Logistic Regression classifier** after having understood our data and then preprocessed it, in order to make sure  to get he best performance of our model.
The choice of the algorithm has been done after having experimented on other algorithms and compareded their performances. 

### data preprocessing :
#### outliers: 
detected outliers in all variables and decided to replace them with the median cuz the median doesnt get affected by the ouliers unlike the mean

#### upsampling: 
unbalanced target variable -> turn them somewhat balanced by upsampling
upsampling is adding datapoints to balance the target variable , these new data points have similar features to the existing datapoints that represent the minority class in target variable

#### normalisation: 
turn all the variables homogeneous 

#### PCA: 
we noticed that some variables are highly correlated, so we decided to do
a principle component analysis 
extracting new features(vars that contains 95% infos about vars)
pca we want 3 first vars to explain data so we use 95%

#### tuning: 
we tuned using 5 vfolds from our train data  to tune a logistic regression model and found a penalty value of 1e-10 and mixture of 0

#### model: 
using the found results  we create a logistic reg model and fit it to our train data

#### evaluation:after that we predict on our testing data
using the requested metric f1_score we found a result of 97% on kaggle public score

## Challenge 2 :
This challenge aims to make a deep learning image classifier that will be able to classify mammography scans into two categories indicating wether the cancer is cancerous or not.
For this challenge, we made a **deep learning CNN image classifier**. We first started by importing the necessary libraries and loading our data, in order to be able to explore our data and get a clearer look on how the dataset is, then we scaled our data and constructed our model, we trained our model and then tested it on a few cases and finally generalized to the whole test set.
For building our model, we have experimented with multiple layer architectures until we reached the one that performed best. 

## Challenge 3 :
The third challenge is making a machine learning model for predicting the survival rate of breast cancer patients.
For this challenge, we have used ** ** to train our model, using the date tha we have explored then preprocessed and made sure it's ready to give the best performance.
After having tried many algorithms on this set of training data we have come to this choice of algorithm, for it having the best performance.
