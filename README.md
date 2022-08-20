# XIN LIN, 201562265

All code and files included in this link is for the MSc Project, MSc Advanced Computer Science, School of Computing, the University of Leeds, 2022.

The original text dataset is from:
https://github.com/CDU-data-science-team/pxtextmining/tree/main/datasets

'All_Data_Original.csv' is the file after data cleaning based on the original txet dataset

TOPIC MODELLING TASK:

'LDA_comments.csv' includes 5814 comments I finally used for topic modelling.

'10pkl', '10.pkl.expElogbeta.npy', '10.pkl.id2word' and '10.pkl.state' is the best perfoming LDA topic I choose for the project, you can use "gensim.models.ldamodel.LdaModel.load('10.pkl')" to load it.

'LDA_code.ipynb' includes all work I have done to finish topic modelling task, pre-processing, building model and validation.

'LDA_validation.csv' includes 200 comments we used to validate the resultes of LDA model, comparing the LDA topic with munual content label for every comment.


SENTIMENT ANALYSIS TASK:

'Category for All.ipynb' is code for counting and summarise how many different categories are included in the text dataset.

'Sentiment Analysis for All.ipynb' is code for sentiment analysis on all comments and also do statistics for each categhory and sentiment tag(the number of comments under every categroy and sentiment tag).

'RandomEvaForSentiment.ipynb' is code for evaluation of sentiment analysis task.

'visulization.ipynb' is code for generating pie chart.

'All_Data_Sentiment.csv' includes Vader results for comments in the whole dataset.

'All_Data_Biglabel_Cal.xlsx' records the data of 9 big labels. 

'All_Data_Subcategory_Cal.xlsx' records the data of 44 subcategories under 9 big labels. 

'All_evaluation_sentiment1-600.csv' records the 600 comments for evaluation, comparing Vader result and manual sentiment tag.
