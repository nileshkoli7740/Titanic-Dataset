# Titanic-Dataset
Exploratory data analysis (EDA) is an important pillar of data science, a important step required to complete every project regardless of type of data you are working with. Exploratory analysis gives us a sense of what additional work should be performed to quantify and extract insights from our data.

## Details:
We will use the classic Titanic dataset. The dataconsists of demographic and traveling information for1,309 of the Titanic passengers, and the goal isto predict the survival of these passengers. The full Titanic dataset is available from the Department of Biostatistics at the Vanderbilt University School of Medicine (http://biostat.mc.vanderbilt.edu/wiki/pub/Main/DataSets/titanic3.csv)in several formats. The Encyclopedia Titanica website (https://www.encyclopedia-titanica.org/) is the website of reference regarding the Titanic. It contains all the facts, history, and data surrounding the Titanic, including a full list of passengers and crew members. The Titanic datasetis also the subject of the introductory competition on Kaggle.com (https://www.kaggle.com/c/titanic, requires opening an account with Kaggle). You can also find a csv version in GitHub repository at https://github.com/alexperrier/packt-aml/blob/master/ch4.

The Titanic data containsa mix of textual, Boolean, continuous, and categorical variables. It exhibits interesting characteristics such as missing values, outliers, and text variables ripe for text mining–a rich database that will allow us to demonstrate data transformations.

Here’s a brief summary of the 14attributes:

pclass: Passenger class (1 = 1st; 2 = 2nd; 3 = 3rd)
survival: A Boolean indicating whether the passenger survived or not (0 = No; 1 = Yes); this is our target
name: A field rich in information as it contains title and family names
sex: male/female
age: Age, asignificant portion of values aremissing
sibsp: Number of siblings/spouses aboard
parch: Number of parents/children aboard
ticket: Ticket number.
fare: Passenger fare (British Pound).
cabin: Doesthe location of the cabin influence chances of survival?
embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
boat: Lifeboat, many missing values
body: Body Identification Number
home.dest: Home/destination
