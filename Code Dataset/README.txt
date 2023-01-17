
!! In the case the code is not run on google colab !!
- Make sure those dataset files are in the same folder as the ipynb folder 
- Comment out -> from google.colab import files
- Comment out -> uploaded = files.upload()

********************************************************************************

The initial dataset we used for our analysis are the following:

sentiment_analysis.csv
tw.csv
tw_reply.csv
30K Tweets with russiaukrainewar hashtag.csv


We compared our model to a pretrained NLP and saved the results in two csv files. Those files are:
Comparisson py_lib - 30K Tweets with russiaukrainewar hashtag.csv
Comparisson py_lib - Elon Musk.csv

The following file is the output of the last line part of our code to analyze some of our results:
df_word_analysis.csv