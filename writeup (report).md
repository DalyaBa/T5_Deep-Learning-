## Smart Sentiment Analysis and classification of Arabic Tweets 



- ## Abstract </br>
    Nowdayes people from all around the world use social media sites to share information. Twitter is one of them. we choose Twitter to collect our data and from this point we start our journey to dealing with Arabic Text. Building an AI deep learning model to understand the context of sentences of Arabic tweets. This will help campanies, universities and initiatives to benefit from this massive platform by collecting data that related to people's opinions.
    
    
    
 - ## Design </br>
    There are two parts of this project one is for sentiment analysis classify weather if the tweet is positive or negative. And two is for classification tweet depending on 5 main catogories sport, politiic, religion, art and econmey. </br>
    we filtered the content of tweets in web scraping phase by using keywords as clustring our data.
    
    
 - ## Data
    We scraped more than 47k tweets and 6 columns from Twitter ligally by using API's keys access from developer account </br>
    Columns:  Username(text), Tweets(text), Timestamp(date), followers(int), label(int), categorie(text).</br>
    Data Size:  47k rows and 6 columns.
    
    
 - ## Algorthims </br>
    Model Selection: LSTM, KNN, BERT (Bidirectional Encoder Representation from Transformer) and fine tuning </br>
    Libraries: Keras, Tensorflow, ktrain, AraBERT, NLTK.</br>
    Tools: Jupyter, GoogleColab, Spyder.</br>
 - ## The Results </br>
    BERT is the best model for both Sentiment Analysis and Classification </br> 
    
    Report for Classification: 
   
   ```
   precision    recall  f1-score   support

           0       0.94      0.95      0.95      1891
           1       0.96      0.95      0.95      1803
           2       0.93      0.93      0.93      1894
           3       0.95      0.95      0.95      1855
           4       0.96      0.97      0.96      1974

    accuracy                           0.95      9417
   macro avg       0.95      0.95      0.95      9417
   
   ```
      
    
    Report for Sentiment Analysis:
    
     ``` 
     learner.validate(val_data=tst)
              precision    recall  f1-score   support

           0       0.79      0.81      0.80      4514
           1       0.80      0.78      0.79      4535

    accuracy                           0.79      9049
   macro avg       0.79      0.79      0.79      9049
    
    ```
- ## Communication </br>
  
 ![dashboard](https://user-images.githubusercontent.com/74211933/150449524-fbb9fa4f-9286-4b24-8f20-46a0f127f4d4.PNG)

![download (23)](https://user-images.githubusercontent.com/74211933/150449163-6828274e-b5df-4763-9f1d-772a1a40ec8c.png)
![download (22)](https://user-images.githubusercontent.com/74211933/150449168-99d7b170-a61f-49b8-ba97-abb99fa90fbb.png)

![sentiment_Bert_plot](https://user-images.githubusercontent.com/74211933/150449191-e888731d-cd31-4ff1-a423-f9806e4f2997.png)

![newplot (16)](https://user-images.githubusercontent.com/74211933/150449271-eda1da35-1be1-4947-b1cb-07b2fdf788d1.png)

![newplot (11)](https://user-images.githubusercontent.com/74211933/150449242-589952fb-8923-4b37-935d-502f587a333f.png)

![newplot (13)](https://user-images.githubusercontent.com/74211933/150449321-7572d735-62df-47ea-a0ac-060d279126c4.png)

![سياسة](https://user-images.githubusercontent.com/74211933/150449747-b72b8c03-bf15-4027-aace-bdabb83a35f9.png)



  
  
  
  
