# TMDB Predictions
This problem is taken from Kaggle specifically because the data given for this problem is in very 
raw format and it needs most data cleaning and feature engineering.
Many features contain data that is in categorical format and in each feature within the cell there are 
more than two categorical values. For example, see the below screenshot to understand what i mean.

Link for the competition is given below:
https://www.kaggle.com/c/tmdb-box-office-prediction/overview
### Things we can learn from this problem
* Data cleaning
* Feature engineering
* Handling categorical features
* Application of different encoding techniques
* Modelling the data

**Note :** All the notebooks in this folder are created in **Google Colab** and every code snippet is as
according to **colab**. So, to ease the work, you can click on the **colab badge** and can directly work
on the notebooks in colab.

### Pre Requisities
* Kaggle username, apikey
* Colab + Google Drive

### Data
Data for this problem statement is directly downloaded and used in colab local session with the help of 
api-keys. So go ahead and create API key of your Kaggle account to download the data sets. I prefer this
kind of downloading coz i need not to store the data in **Google Drive**, which provides limited storage
of 15 GB.<br>
If you are not aware of how to dowload the API key for kaggle, follow the below link.<br>
https://medium.com/@yvettewu.dw/tutorial-kaggle-api-google-colaboratory-1a054a382de0
<br>
Data set files in the entire project is stored in the form of **parquet file** with **gzip** compression. Again for same reason, to save the storage space i'm using this fileformat.
You can use any other format other than csv, as csv doesn't come in handy when a very large data like 2 - 4 GB data file, takes more time and disk space. To know more about different fileformats explore
the below link. <br>
https://luminousmen.com/post/big-data-file-formats
<br>

## Miscellaneous
I used many libraries which i often use in all of my works that eases our feature engineering and feature transformation process when dealing with large datasets.
