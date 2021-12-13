# Stock-Prediction-Using-SEC-NLP

# Project

I will use the SEC Filings, excluding 10-K, 10-Q and Form 4 to predict the t+1 stock return. Applying NLP techniques to predict stock price has always been an interesting topic. From the Efficient Market Hypothesis, the market moves by ingesting new information. Official announcements like: merger and acquisition, major shareholder changes, dispose of company stocks, etc should have impacts on the company's stock price. Because 10-K, 10-Q and Form4 contain more quantitative information than the other fillings, I will exclude these three types of fillings in this project. The input will be the text of SEC filings from a selected group of companies. And target output will be that company’s next day return(+/-).


For data, I will collect the texts from the sec filings website. Because of the simple setup, I can apply and experiment with a variety of models. I will use BOW, TF-IDF, Word2Vec, Doc2Vec to vectorize our data and predict the target using machine learning models like random forest or lightgbm.After implementing above baseline models, I will try to implement deep learning techniques like RNN and BERT to make more sophisticated predictions.
Since this is a binary classification problem, precision, recall, accuracy and F1 score will be used to measure the model performance. For machine learning approaches, the local environment should suffice. For deep learning models, I may use cloud platforms like GCP or AWS to run the models.


Data:

SP500 Stocks training 2015-2019 testing 2021 

Total File Size > 36GB

![Alt text](Presentations/data_flow.png?raw=true "Data Flow")

![Alt text](Presentations/model_flow.png?raw=true "Model Flow")

![Alt text](Presentations/evaluation.png?raw=true "Evaluation")


