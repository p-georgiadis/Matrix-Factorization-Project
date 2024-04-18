# BBC News Classification - Kaggle Competition

This repository contains all the necessary files and notebooks for the Kaggle competition on BBC News Classification. This project is part of the "Unsupervised Algorithms in Machine Learning" course in the "Machine Learning: Theory and Hands-on Practice with Python" specialization. It is a component of my pursuit of a Master of Science degree in Computer Science from the University of Colorado Boulder, under the instruction of Geena Kim, Adjunct Professor.

## Overview

The project is divided into two main parts:
1. **Matrix Factorization for News Article Classification** - Utilizing unsupervised learning to discover topics in news articles and categorize them.
2. **Evaluation of sklearn’s Non-negative Matrix Factorization (NMF)** - Analysis of NMF's performance on a movie rating dataset.

## Repository Structure

- `README.md`: This file, describing the project and its structure.
- `data/`: Directory containing datasets used in the analysis.
- `notebooks/`: Jupyter notebooks for each part of the analysis.
  - `01_Exploratory_Data_Analysis.ipynb`: Notebook containing the EDA for the BBC news dataset.
  - `02_Matrix_Factorization_Model.ipynb`: Notebook detailing the matrix factorization model building and predictions.
  - `03_Supervised_vs_Unsupervised.ipynb`: Comparison of supervised and unsupervised learning models.
  - `04_NMF_Movie_Ratings.ipynb`: Analysis of the limitations of sklearn's NMF using movie ratings data.
- `reports/`: Optional directory for any generated report PDFs or Markdown files summarizing the findings.

## Part 1: News Classification

### Exploratory Data Analysis (EDA)
The initial part of the project involves conducting an EDA to inspect, visualize, and clean the BBC news dataset. We explore the data to understand the distribution of words, article lengths, and categories.

### Model Building and Training
Using matrix factorization, we aim to identify latent topics within the news articles and classify them into predefined categories. This part includes:
- Building and training the model using sklearn's NMF.
- Evaluating the model on both training and test datasets.
- Hyperparameter tuning and results visualization.

### Comparison with Supervised Learning
We compare the results of our unsupervised model with a supervised model to assess their efficiencies and discuss the implications of using one over the other in terms of data requirements and overfitting.

## Part 2: NMF Evaluation

### Application to Movie Ratings
We apply NMF to a movie ratings dataset to predict missing ratings and measure the performance using RMSE.

### Limitations of sklearn’s NMF
Discussion on why NMF may not have performed as well as other baseline or similarity-based methods and suggestions for potential improvements.

## Getting Started

This section guides you on how to access and use the materials available in this repository for the BBC News Classification and NMF Movie Ratings projects.

### Prerequisites

There are no separate installation requirements for running the Python code as all necessary libraries and dependencies are included and can be managed directly within the Jupyter notebooks provided in the `notebooks/` directory.

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

## Acknowledgements

- Bijoy Bose. (2019). BBC News Classification. Kaggle. https://kaggle.com/competitions/learn-ai-bbc
- University of Colorado Boulder and Professor Geena Kim for educational support and guidance.
