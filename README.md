# Data-Extraction-and-NLP Analysis

### Introduction
The objective of this project is to extract textual data articles from the given URL and perform text analysis to compute variables such as Avg_Sentence_Length,	Percentage_Complex_Words,	Fog_Index,	Avg_Words_Per_Sentence,	Complex_Word_Count,	Word_Count,	Syllable_Count_Per_Word,	Personal_Pronoun_Count,	Avg_Word_Length. 

### Work Process
#### 1. Data Extraction
For each of the articles, given in the input.xlsx file, extract the article text and save the extracted article in a text file with URL_ID as its file name.
While extracting text, please make sure your program extracts only the article title and the article text. It should not extract the website header, footer, or anything other than the article text. 

#### 2. Data Analysis
For each of the extracted texts from the article, perform textual analysis and compute variables, given in the output structure excel file. You need to save the output in the exact order as given in the output structure file, “Output Data Structure.xlsx”

### Conclusion
I used Jupiter Notebook to perform Python coding to achieve the targeted result. This project is divided into 3 parts: 

1. Function to extract the article title and text from a URLs given in Input.xlxs file and extracting each articles into txt
2. Sentiment Analysis: Function to load positive and negative dictionaries from files and Function to perform sentiment analysis and calculate scores
3. Text Analysis: Functions to Calculate Avg_Sentence_Length,	Percentage_Complex_Words,	Fog_Index,	Avg_Words_Per_Sentence,	Complex_Word_Count,	Word_Count,	Syllable_Count_Per_Word,	Personal_Pronoun_Count,	Avg_Word_Length

Lastly to read file into the desired manner of output in excel file.
