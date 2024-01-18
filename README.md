**Overview**

The following script is designed to use methods from spacytextblob* to analyse sentiment and polarity of Amazon reviews. 

It is run on a sample data set from Kaggle, which has just under 29,000 Amazon reviews on Alkaline Household batteries compiled in a csv file. 

The user is offered the choice of comparing two reviews. S/he is prompted to enter the index of the first and second review to be compared. 

**Important notes**

Please note that this runs on Python 3.11.7 (conda). 
Please note that I have used ‘en_core_web_md’ and not ‘en_core_web_sm’ as the latter was generating a number of issues (see below)
