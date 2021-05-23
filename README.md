# DogeCoin_Analasys_And_Deeplearning
Analayzing DogeCoin stock data and using deeplearning to predict future prices.  
My kaggle [notebook](https://www.kaggle.com/elitefrog/dogecoin-analysis-and-deeplearning)
# Installation  
to run the notebook you will need:  
1- python 3.x  
2- jupiter notebook  
3- plotly  
4- matplotlib  
5- numpy  
6- pandas  

# Project Motivation
with the current intrest in DogeCoin as a real cryptocurrency, I try to analyse it stock data and build a deeplearning model to predict the future price of the coin.  

# File Descriptions  
Doge_Coin_Analysis.ipynb: A notebook with all the analysis and deeplearning model.  

# How To Interact With Your Project  
Make sure to download everything you need from the installation section.  
Download the notebook then run all the cells.  

# Results Summery  
Data contains a lot of duplicated data like High, Low, and open, they mimic the price column and do not add any new information.  
![pic](/Price_HL.png)  
 
 Therefore these three columns were droped from the data set.  
 
 After training the LSTM model and using squared_mean_error as both our loss function and evaluation metric the following results were prodused.  
 ![pic](/loss.png)  
 No over fitting is present.  
 
 The following graphs show the model's predictions VS the actual data.  
 ![pic](/test.png)  
 ![pic](/full.png)  
 
# Acknowledgment 
I would like to thank [Tarandeep Singh](https://www.kaggle.com/tarandeep97/dogecoin-historical-data20172021) for collecting the data and uploading it to kaggle.
