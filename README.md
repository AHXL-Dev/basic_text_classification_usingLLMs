# Customer Feedback Theme Classifier

This program is one of my first uses of testing how to analyse customer feedback data and classify this into a set of predefined themes.
It combines multiple text fields—Problem Description, Resolution, and Customer Feedback—into a single input and prompts the model to determine whether each theme applies.

### Dataset Used

I have hard-coded some feedback to mirror a typical situation that one might encounter when analysing feedback data with other contextual information.

The examples are based on this dataset: https://www.kaggle.com/datasets/chaudharyanshul/airline-reviews 

This is a BA Airlines Dataset from Kaggle which was uploaded by Chaudhary Anshul & Muskan Raisinghani

### What it does
- Each theme is added as a column in the dataset, the program goes through each row and then essentially puts a key of each theme and a simple 'Yes/No'
- There is no explanation, no chain of thought usage etc. This was my first attempt and it was really simple and probably not the most robust solution.

## Requirements
- Install packages as per the requirements.txt file
- You will need access to an API key for whatever model you are using
- You need to use a model that uses the chat completions API

### Output
A CSV file with the date and the model you used
