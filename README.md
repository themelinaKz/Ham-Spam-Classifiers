# Ham-Spam-Classifiers

***Group Project for AI course.***

Implemented 4 ML classification algorithms(Naive Bayes,ID3,AdaBoost,Logistic Regression) from scratch in pure Java.

Distributed data in training(80%),development(10%) and testing(10%).

Performed dimensionality reduction by calculating the information gain of all features(here being tokens from the mails) in order to specify m-best features and then used these features in each algorithm.

Calculated best features number and hyper-parameters(if needed) for each algorithm based on accuracy accomplished in the development data.

Calculated accuracy score for training and testing data and for every 10% of the data(e.g 10%,20% etc.) in order to create learning curves.

Calculated recall,precision and F1 scores for both categories(spam,ham) for training and testing data and for every 10% of the data(e.g 10%,20% etc.) in order to create curves for these scores.

**Instructions for running:** Unzip enron1.zip and run Driver.java 

Dataset used for the project is enron1 ( http://nlp.cs.aueb.gr/software_and_datasets/Enron-Spam/preprocessed/enron1.tar.gz )
Works with all enron datasets in pre-processed form ( http://nlp.cs.aueb.gr/software_and_datasets/Enron-Spam/index.html )  

# Group  
[Marilena Kokkini](https://github.com/MarilenaKokkini)  
[Themelina Kouzoumpasi](https://github.com/themelinaKz)  
[Foivos Charalampakos](https://github.com/wolfie00)  

_Winter 2019_
