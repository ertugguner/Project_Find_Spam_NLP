# Finding Spam Messages (Natural Language Processing): Project Overview
- Creating a machine learning model which detecting spam messages.
- The data I'am using is from Kaggle's dog breed identification competition.
https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection
- I completed this project with what I learned from this course:
https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/

- Due to the spacing we can tell that this is a [TSV](http://en.wikipedia.org/wiki/Tab-separated_values) ("tab separated values") file, where the first column is a label saying whether the given message is a normal message (commonly known as "ham") or "spam". The second column is the message itself. 

- Using these labeled ham and spam examples, I'll **train a machine learning model to learn to discriminate between ham/spam automatically**. Then, with a trained model, I'll be able to **classify arbitrary unlabeled messages** as ham or spam.
Python Version : 3.7

Packages: Pandas, Numpy, Matplotlib, Sklearn, Seaborn

 ![](/images/fig2.png)
 
 ![](/images/fig1.png)
  
  ## Model Performance
  
  ![](/images/evaluation.png)
