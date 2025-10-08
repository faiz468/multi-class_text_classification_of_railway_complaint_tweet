# Multi Label Text Classification of Indian Railway complaint tweets
This project is important to simplify the process of resolving complaints reported to the indian_railway on twitter.
It separates reported tweets into complaint tweets and non-complaint tweet.
It also classifies complaint tweets into the different categories according to different departments to split the task of resolving users complaints and to speed the process.
we prepare the dataset for this problem from scratch.
we used BERT transformer in our project.

•	Distinguishes between complaints and non-complaints with an accuracy of 81% outperforming the baseline model.
•	Further categorizes complaints into 12 predefined types to enhance query resolution workflows. [github]
•	Developed a dataset with 4,536 instances for this problem and employs the self made semi automated pipeline to label the tweets. 

We use a semi-automated process to label our dataset, take help of zero-shot-classification model, gpt and 
also a manual check to maintain the accuracy of labelling. More Details- https://github.com/faiz468/data_labelling_for_textclassification

system using BERT transformer to classify railway related tweets:

•	Semi-Automated Data Labeling Pipeline for Text Classification: Employed a semi-automated process for labeling datasets, integrating zero-shot classification models, GPT, and manual verification to ensure labeling accuracy for text classification tasks
