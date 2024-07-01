# CommonLit-Readability 
## Natural Language Processing Project in R
This data analysis project aims to use Machine Learning to predict readability of text passage among grades 3-12. The aim is to identify the appropriate reading level of a passage of text, and help inspire learning. 

### Key Objectives:

1. Extract meaningful features from the 'excerpt' column to enhance our analysis and modeling capabilities.
2. Develop predictive models for reading difficulty based on different aspects of the given paragraph, such as parts of speech, number of words and sentences and overall reading comprehension.
3. Design the model to provide interpretable results, allowing educators to understand the factors contributing to a text's complexity rating.

### Expected Outcomes:
- Develop a highly accurate algorithm for rating the complexity of reading passages for grades 3-12, potentially improving upon existing readability formulas and methods.
- Create a robust feature extraction framework that effectively captures various aspects of text complexity, including cohesion, semantics, and linguistic structures.
- Produce a model that can generalize well across different types of texts and domains, making it versatile for various educational contexts.
- Generate insights into the key factors that contribute to text complexity, which can inform educational practices and curriculum development.

## Data:
### Data Source and Type:
This project utilizes csv data from Kaggle.
https://www.kaggle.com/c/commonlitreadabilityprize/overview

### Data Description:
Type: Text data with associated metadata
Format: CSV files
Source: Kaggle competition dataset
Update Frequency: One-time dataset for the competition

### Key Characteristics:
Size: 
- Train Data: 2834 rows * 6 columns
- Test Data: 7 rows * 6 columns 
Scope: Reading passages for grade 3-12 classroom use

Primary Units: Individual text excerpts with complexity ratings
Notable Features:
Text excerpts from various domains
Complexity ratings for each excerpt

Columns: 
id - unique ID for excerpt
url_legal - URL of source - this is blank in the test set.
license - license of source material - this is blank in the test set.
excerpt - text to predict reading ease of
target - reading ease
standard_error - measure of spread of scores among multiple raters for each excerpt. Not included for test data.

