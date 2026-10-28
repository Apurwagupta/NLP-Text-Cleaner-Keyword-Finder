# NLP Text Cleaner and Keyword Finder

## Project Overview
This mini project demonstrates basic Natural Language Processing (NLP) techniques using Python. It cleans short text documents, analyzes word frequencies, and extracts important keywords using TF-IDF.

## Objectives
- Load a dataset containing 150 short texts.
- Convert text to lowercase and remove punctuation and unwanted characters.
- Remove English stop words.
- Apply Porter stemming.
- Visualize the 10 most frequent words using a bar chart.
- Extract the top 10 keywords using TF-IDF.

## Technologies Used
- Python
- Google Colab
- Pandas
- NLTK
- Scikit-learn
- Matplotlib

## Project Workflow
1. Create and load the CSV dataset.
2. Clean the text using regular expressions.
3. Remove stop words and apply stemming.
4. Calculate word frequencies.
5. Generate a bar chart of the top 10 words.
6. Calculate average TF-IDF scores and display the top 10 keywords.
7. Export the cleaned dataset to CSV.

## Repository Contents
- `NLP_Text_Cleaner_Keyword_Finder.ipynb` — source code and executed outputs.
- `sample_texts.csv` — original text dataset.
- `cleaned_texts.csv` — cleaned text output.
- `outputs/` — screenshots of the results.
- `NLP_Project_Report.pdf` — project report.

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Install the required libraries when prompted.
4. View the word-frequency chart and TF-IDF keyword results.

## Results
The project produces a cleaned text dataset, a bar chart of the 10 most frequent words, and a list of the 10 highest average TF-IDF keywords.

See the notebook and screenshots for the actual results.

## Conclusion
This project demonstrates how text preprocessing, frequency analysis, and TF-IDF can be used to explore and extract useful information from a collection of text documents.
