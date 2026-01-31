### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 30/01/2025
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:

<img width="1175" height="468" alt="Screenshot 2026-01-30 161010" src="https://github.com/user-attachments/assets/2e864a24-3709-477e-8a53-d9a2703c25bc" />

<img width="1188" height="357" alt="Screenshot 2026-01-30 161511" src="https://github.com/user-attachments/assets/d20e495f-269a-4861-96a6-54fd6ce27e40" />

<img width="1336" height="1027" alt="Screenshot 2026-01-30 163051" src="https://github.com/user-attachments/assets/b45b0678-e4ac-48d8-9bca-64164e0780c0" />


### Result:

Implemented preprocessing technique on Twitter Data using Rapidminer was successfully.
