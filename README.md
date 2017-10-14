# DSG_Recruitment
Mushroom Data Set

It is the analysis of the mushroom data set where we were expected to classify the mushroom categories into two categories i.e. edible 
or poisonous.The dataset has 25 attributes including the target variable class.It had two continuous variables radius and weight.
So first after performing the library and dataset imports, I have performed exploratory data analysis. F\
First performing a univariate analysis and then a bi-variate analysis of all the attributes.
For the univariate analysis first analysing the continuous variable, first using the describe() method on the dataset I found out the mean,
standard deviation and other statistical quantities.After that I performed some visual analysis by plotting histograms,jointplot and boxplots.
After the visualisation we could infer about the outliers and also comment about the correlation between the two continuous variables.

After this moving to the categorical variables, I used some factorplot to plot the variation in the categorical variables with respect
to the target variable class.From this we get some insights which are mentioned in the jupyter notebook.

After the visual analysis part, I performed outlier treatment on the radius attribute.

After this I did variable preprocessing for fitting our data into our machine learning model.For that first I performed feature scaling on
the continuous variables radius and weight so that their ranges are same,and a longer range of one variable does'nt disturb our prediction.
After that I performed label encoding of the categorical variables.

So after the variable preprocessing part I applied random forest algorithm on the dataset,for the parameter tuning of the algorithm I used the
GridSearchcv method and then applied the algorithm to the training data set.Thereafter I used the train_test_split method to verify the accuracy
of my method.Then I predicted the target variable by applying the random forest model on the test dataset.

