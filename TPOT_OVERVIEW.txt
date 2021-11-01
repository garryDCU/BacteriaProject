I used TPOT to try predict bacteria strains from in each chemical column. You can find the input data in the file 'bacteria.csv'.
I decided to replace all nulls in the dataset with 0's and as the target column consisted of categorical data, I converted them to numbers using labelEncoder() from sci-kit learn. 
The primaryEDA.ipynb file was made locally using Jupyter Notebook via Anaconda Navigator and then I used Google Colab to create 'tpot.ipynb' as I was having a lot of compatibility issues on my laptop.

The results obtained were reasonable following cross validation with an average score of over 80%. 
