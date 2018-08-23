# MSP-AzureML-Workshop
Slide deck and .csv file for introductory workshop to Machine Learning with Azure ML Studio

Alternate download source of Train.csv acquired from Kaggle's tutorial competition "Titanic: Machine Learning from Disaster". 
Source link : https://www.kaggle.com/c/titanic/data

This workshop was based off of a tutorial created by Jennifer Marsman at Microsoft
Source link: https://channel9.msdn.com/Blogs/raw-tech/Using-Azure-Machine-Learning-to-Predict-Who-Will-Survive-the-Titanic-Part-1

## Data Dictionary

### Variable  Definition  Key

survival  Survival	0 = No, 1 = Yes

pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd

sex Sex	

Age	Age in years	

sibsp	# of siblings / spouses aboard the Titanic	

parch	# of parents / children aboard the Titanic	

ticket	Ticket number	

fare	Passenger fare	

cabin	Cabin number	

embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton
Variable Notes

pclass: A proxy for socio-economic status (SES)

1st = Upper

2nd = Middle

3rd = Lower



age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5


sibsp: The dataset defines family relations in this way...

Sibling = brother, sister, stepbrother, stepsister

Spouse = husband, wife (mistresses and fiancés were ignored)



parch: The dataset defines family relations in this way...

Parent = mother, father

Child = daughter, son, stepdaughter, stepson

Some children travelled only with a nanny, therefore parch=0 for them.

