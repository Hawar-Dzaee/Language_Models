# Natural Language Processing with Disaster Tweets

## Overview

This repository contains code and data related to the "Natural Language Processing with Disaster Tweets" project. The goal of this project is to classify Twitter messages (tweets) into two main categories: tweets related to disasters and tweets unrelated to disasters.

### Data Source

The dataset used in this project is sourced from Kaggle and can be found [here](https://www.kaggle.com/c/nlp-getting-started/data). It consists of labeled tweets that have been categorized into disaster-related and non-disaster-related categories.

## Project Structure

The repository is organized as follows:

- **data**: This directory contains the dataset used for training and evaluation.
- **notebooks**: Jupyter notebooks used for various stages of the project, including data inspection, data wrangling, model training, and evaluation.
- **src**: Contains Python scripts for utility functions or custom modules used in the notebooks.
- **models**: This directory may contain saved model weights if applicable.
- **results**: Saved model evaluation results, visualizations, or any other project-related output.

## Data Inspection and Wrangling

In the initial stages of the project, the dataset underwent data inspection and data wrangling processes to ensure its suitability for training and evaluation.

## Data Cleaning

Data cleaning steps were performed to handle missing values, remove irrelevant information, and preprocess text data for model training.

## Model Development

The project involved the creation of seven language models for tweet classification:

1. **Baseline Model (Naive Bayes)**
2. **Simple Dense Model**
3. **LSTM (Long Short-Term Memory) Model**
4. **GRU (Gated Recurrent Unit) Model**
5. **Bidirectional Model**
6. **Conv1D Model**
7. **Pretrained Embeddings Model**

Each model's implementation can be found in the respective Jupyter notebook within the `notebooks` directory.

## Usage

To reproduce the results or explore the code, follow these steps:

1. Clone this repository:

   ```shell
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install the required dependencies. You may use a virtual environment for this:

   ```shell
   pip install -r requirements.txt
   ```

3. Open and run the Jupyter notebooks in the `notebooks` directory. Ensure that you have the dataset downloaded and placed in the `data` directory.

## Results

The results of model training and evaluation, including performance metrics and visualizations, can be found in the respective notebook outputs or in the `results` directory.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Kaggle for providing the dataset.
- [OpenAI](https://www.openai.com/) for providing the GPT-3.5 architecture used for creating this README file template.

Feel free to customize this README file with additional information, project-specific details, and acknowledgments as needed.
