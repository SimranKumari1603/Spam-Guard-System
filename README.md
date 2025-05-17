Spam Guard System 
Step 1 - DATA CLEANING

remove nan value from dataset
label Encoder apply(ham = 0 , spam = 1)
remove duplicates values
now check no nan and duplicate value
done with basic cleaning

Step 2 - EDA

understand the data -draw pie chart and find data is imbalance(88% ham , 12%spam) -take num_character to build model 

Step 3 - DATA PREPROCESSING 

convert to lower case -Tokenization(break into words) -remove special characters -remove stop words and punctuation -apply stemming 

Step 4 - Model building 

used naive bayes algorithm(because in textual data it is best working) 

Step 5 - Model improvement 

taken max-feature = 3000 as large dataset so take only top 3000 words with highest term frequency

Step 6 - website
