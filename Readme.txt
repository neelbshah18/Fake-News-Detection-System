Fake News Detection System

I have built a system which helps in detecting Fake News. During the recent years there have been lots and lots of false news spreading on the internet or through different medium as a result of which this has became a major concern. If there is a system which can detect the fake news system is used it will solve our problems.

Pre Requisites
1) Python 3 and above
2) Packages:
	a) Numpy
	b) Sklearn
	c) Scipy

Dataset
 The data was obtained from the LIAR dataset which contains three files .tsv format for test, train and validation.
The dataset contains 13 columns in the file which are as follows:

Column 1: the ID of the statement ([ID].json).
Column 2: the label. (Label class contains: True, Mostly-true, Half-true, Barely-true, FALSE, Pants-fire)
Column 3: the statement.
Column 4: the subject.
Column 5: the speaker.
Column 6: the speaker's job title.
Column 7: the state info.
Column 8: the party affiliation.
Column 9-13: the total credit history count, including the current statement.
The new dataset was created on the basis of the data from the LIAR which contains only two columns:
Column 1: Statement (Headline of the News).
Column 2: Label (True/False)

Steps
Step 1:	If python is already installed then go to the command prompt and navigate to the path where the file is present 
Then run the command:
Python Linear_Regression_final_model.py

Step 2: Input the news headline which we want to check and hit enter then the system will print the class label of that headline along with the probability of truth



