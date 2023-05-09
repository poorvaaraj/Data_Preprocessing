* Data_Preprocessing *
This repository contains the code and data used to preprocess a movie dataset. 
The dataset contains information about movies such as the title, genre, release year, and ratings, budget,language,Title,etc.
The data preprocessing steps were performed using Python and the Pandas library. The following steps were taken:
1. Load the Dataset
2. Explore the dataset
3. Text preprocessing 
4. Handling data types
5. Handling Date formats
6. Binning the columns


TEXT PREPROCESSING
1. Converting the columns including text data into lower case strings
2. Removing punctuation
3. Removing stop Words
4. Perfroming lemmatization

Numerical columns
1. Chaning the data type of column from float to integer where required
2. Splitting the votes ranging from 1 to 10 in categories - 'superhit', 'hit', 'good','bad', 'very bad'

Date Columns
1.Using pandas library, Extracting year, month and day from release_date column.



