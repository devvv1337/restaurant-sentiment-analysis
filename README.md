# Restaurant Sentiment Analysis

## Description

This notebook performs sentiment analysis on restaurant reviews using pre-trained models RoBERTa and LLaMA. The analysis includes data preprocessing, applying sentiment classification models, evaluating their performance, and deploying an interactive web interface with Gradio for real-time sentiment prediction. The combined approach leverages prompt engineering to handle ambiguous classifications by utilizing the LLaMA model when necessary.

## Technologies Used

- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **Scikit-learn**: Machine learning utilities for model evaluation.
- **Transformers (Hugging Face)**: Utilizing pre-trained RoBERTa and LLaMA models for sentiment analysis.
- **Requests**: Handling HTTP requests to interact with the LLaMA API.
- **Gradio**: Creating an interactive web interface for the sentiment classifier.
- **Matplotlib & Seaborn**: Data visualization libraries.
- **NumPy**: Numerical computing.
- **Prompt Engineering**: Designing effective prompts for LLaMA to handle ambiguous sentiment classifications.

## Workflow

![Workflow diagram](https://i.imgur.com/O6lo4mS.png)


## Usage

Simply execute the `sentiment_analysis.ipynb` notebook using Jupyter Notebook or JupyterLab to perform the analysis and launch the interactive Gradio interface.

