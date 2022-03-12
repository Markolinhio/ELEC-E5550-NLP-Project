# ELEC-E5550-NLP-Project  
  
# Problem & motivation:  
E-commerce platforms like Amazon have suffered from fake review problems as some shoppers accept gifts and other incentives in exchange for positive reviews, despite a ban on these activities. 
Hence, having a model that assists companies in detecting such issues would help customers shop with confidence knowing the reviews they read are authentic and relevant. 
Engaging in spam detection might also create a competitive advantage for firms regarding customer experience.  
  
# Dataset:  
Link: https://www.kaggle.com/naveedhn/amazon-product-review-spam-and-non-spam  
The dataset contains Amazon product reviews with spam and not spam labeling. This is a large corpus that contains 26.7 million reviews and 15.4 million reviewers.  
The class label is spam and not spam, where "0" indicates not spam and "1" indicates spam reviews.  
  
# Aim of study:  
The aim of the study is to predict whether a review is spam or not by applying different models and evaluating the results from the best model.  
  
# Project plan:  

## Data preprocessing:  
* Change the data format from JSON to the data frame  
* Remove empty rows, retain important columns (text, labels, category of product, review title)  
* Combine review title and review text as the data  
* Apply tokenization and lemmatization, remove stop words, lowercasing  
* Balance class distribution  
* Save the data  
## Data visualization (EDA)  
* Apply vectorization methods: TF-IDF, Word2Vec  
* Embed the matrices and visualize them on 2D scatter plots to see if there are any clusters or structures in the data   
## Modeling  
* Apply NN models: LSTM, CNN, or other models if any interesting ones arise  
* Hyperparameter tuning for each model  
## Model validation and comparison  
* Monitor classification accuracy of train and test sets for each model  
* Compare accuracy between the models  
  
