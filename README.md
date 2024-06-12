# Matrix Factorization Project

This repository contains all the necessary files and notebooks for the Kaggle competition on BBC News Classification. This project is part of the "Unsupervised Algorithms in Machine Learning" course in the "Machine Learning: Theory and Hands-on Practice with Python" specialization. It is a component of my pursuit of a Master of Science degree in Computer Science from the University of Colorado Boulder, under the instruction of Geena Kim, Adjunct Professor.

## Overview

The project is divided into two main parts:

1. **BBC News Classification Using Matrix Factorization**
     - Using unsupervised matrix factorization techniques to categorize news articles into predefined categories.
     - Using supervised matrix factorization techniques to categorize news articles into predefined categories and comparing the results with the unsupervised learning methods.

3. **Evaluation of sklearn’s Non-negative Matrix Factorization (NMF) on Movie Ratings** - Analyzing the performance and limitations of sklearn's NMF library on a movie ratings dataset.

## Part 1: BBC News Classification

### Exploratory Data Analysis (EDA)
The initial part of the project involves conducting an EDA to inspect, visualize, and clean the BBC news dataset. We explore the data to understand the distribution of words, article lengths, and categories. This includes:
- Visualizing the distribution of news categories.
- Analyzing text lengths and word counts.
- Cleaning the text data by removing stopwords and performing lemmatization.

### Model Building and Training
Using matrix factorization, we aim to identify latent topics within the news articles and classify them into predefined categories. This part includes:
- Building and training a model using sklearn's Non-negative Matrix Factorization (NMF).
- Evaluating the model on the training data.
- Comparing the performance of the NMF-based model with a supervised learning model (e.g., Logistic Regression) using TF-IDF features.

### Comparison with Supervised Learning
We compare the results of our unsupervised model with a supervised model to assess their efficiencies and discuss the implications of using one over the other in terms of data requirements and overfitting. This includes:
- Evaluating models on validation data.
- Discussing the strengths and weaknesses of each approach.

## Part 2: Evaluation of sklearn’s NMF on Movie Ratings

### Application to Movie Ratings
We apply NMF to a movie ratings dataset to predict missing ratings and measure the performance using Root Mean Squared Error (RMSE). This part includes:
- Loading the movie ratings data.
- Applying matrix factorization techniques to predict missing ratings.
- Measuring the performance using RMSE.

### Limitations of sklearn’s NMF
Discussion on why NMF may not have performed as well as other baseline or similarity-based methods and suggestions for potential improvements. This includes:
- Analyzing the results and performance of the NMF model.
- Comparing NMF with simple baseline or similarity-based methods.
- Suggesting possible ways to improve the performance of matrix factorization techniques.

## Repository Structure

- `README.md`: This file, describing the project and its structure.
- `data/`: Directory containing datasets used in the analysis.
- `notebooks/`: Jupyter notebooks for each part of the analysis.
  - `01_EDA.ipynb`: Notebook containing the EDA for the BBC news dataset.
  - `01_Unsupervised_Matrix_Factorization.ipynb`: Notebook detailing the unsupervised matrix factorization model building and predictions.
  - `01_Supervised_Matrix_Factorization.ipynb`: Notebook detailing the supervised matrix factorization model building and predictions.
  - `02_Movie_Evaluation_of_sklearn_NMF.ipynb`: Analysis of the limitations of sklearn's NMF using movie ratings data.
- `reports/`: Directory for Markdown files summarizing the findings.
  - `01_Discussion.md`: Comparison of Supervised and Unsupervised Approaches
  - `02_Discussion.md`: Limitations of sklearn's NMF

## Getting Started

This section guides you on how to access and use the materials available in this repository for the BBC News Classification and NMF Movie Ratings projects.

### Prerequisites

Before running the Jupyter notebooks, ensure you have Python installed on your system. To install all necessary dependencies for this project:

**Install Dependencies**: Run the following command in your terminal to install the required Python packages from the `requirements.txt` file located in the root of the `News-Classification` directory:
    ```bash
    pip install -r requirements.txt
    ```

### Data Files

The datasets needed for the analyses are already included in the repository, located within the `data/` directory:
- News dataset: `data/news/*.csv`
- Movie ratings dataset: `data/movies/*.csv`

### Running the Notebooks

To work with the Jupyter notebooks:
1. Ensure you have Jupyter installed. If not, you can install it via Anaconda or with pip
2. Navigate to the `notebooks/` directory
3. Launch Jupyter Notebook
4. Open any `.ipynb` file to view, run, or modify the analysis.

### Viewing the Reports

For a summarized view of the findings and analyses, refer to any reports or summarized notebooks located in the `reports/` directory.

## Contribute

Feel free to fork this repository or submit pull requests. If you find an error or have suggestions for improvement, please open an issue.

## License

This project is open-sourced under the MIT license.

## Authorship

This project was developed by Panagiotis Georgiadis, a Master's student in Computer Science at the University of Colorado Boulder. All work, including the exploratory data analysis, model building, training, and evaluation, was conducted by Panagiotis Georgiadis. This project is part of the coursework for the "Unsupervised Algorithms in Machine Learning" course, instructed by Geena Kim, Adjunct Professor.

## Acknowledgements

- Bijoy Bose. (2019). BBC News Classification. Kaggle. https://kaggle.com/competitions/learn-ai-bbc
- University of Colorado Boulder and Professor Geena Kim for educational support and guidance.
