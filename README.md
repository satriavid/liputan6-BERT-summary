
# BERT-Based Summarization of Liputan6 Data

## Overview
This repo is for the 2nd NLP Project as part of AI Bootcamp by Indonesia AI.
I dive into experimenting with BERT for summarizing articles from Liputan6. This project is designed to explore the capabilities of BERT in transforming lengthy news articles into concise, informative summaries.

## Goal
The main goal of this project is to train a BERT model that specializes in summarizing Indonesian news articles, using the distinct style of Liputan 6, a leading news outlet in Indonesia. We're aiming to create a tool that can efficiently condense news into readable summaries, enhancing the engagement and understanding of readers across Indonesia. This approach seeks to mirror the professionalism and clarity typical of Liputan 6, providing a better reading experience.

## Usage
### Data Download
To get started, you’ll first need to download the dataset from:
- [Liputan6 Dataset](https://huggingface.co/datasets/id_liputan6)

### Running the Notebooks
The project is structured in Jupyter notebooks which you can easily run in Google Colab:
1. Open Google Colab: [Google Colab](https://colab.research.google.com/)
2. Upload the `.ipynb` file provided in this repository.
3. Follow the instructions within the notebook to install necessary libraries and set up the environment.

## Exploratory Data Analysis (EDA)
I kick off the project with a comprehensive EDA to understand the nuances of the data:
- **Text Length Analysis:** Understanding the distribution of article and summary lengths.
- **Word Cloud Analysis:** To identify main keywords that has been highlighted in the dataset
- **Frequency Analysis:** Identifying common words and phrases, which helps in fine-tuning the summarization.
- See the notebooks to see more detailed visualizations and insights!

## Model Training
Here, I document the steps taken to train the BERT model, including:
- **Preprocessing:** How the data is cleaned and prepared for training.
- **Model Configuration:** Settings and hyperparameters used.
- **Training Process:** A step-by-step guide to how the model was trained using the processed data.

## Summarization Using BERT
Post-training, the model is put to the test:
- **Summarization Execution:** Instructions on how to use the trained model to generate summaries.
- **Examples:** Showcasing before and after summaries to highlight the model's performance.

## Evaluation and Metrics
To measure the effectiveness of our summarization:
- **ROUGE Scores:** We use ROUGE to evaluate the quality of the summaries compared to human-written ones.
