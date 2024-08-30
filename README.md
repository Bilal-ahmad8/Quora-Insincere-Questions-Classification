# Quora Insincere Questions Classification

This repository contains a Jupyter notebook for classifying insincere questions on Quora using machine learning techniques. The notebook demonstrates the workflow for preprocessing data, training a model, and evaluating its performance to filter out insincere questions.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Data](#data)
- [Notebook Structure](#notebook-structure)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview

The goal of this project is to classify questions on Quora as either sincere or insincere based on their content. The project utilizes a dataset of questions from Quora to train a machine learning model that can effectively distinguish between different types of questions.

## Requirements

To run the notebook, you will need the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tensorflow` or `keras` (for deep learning models)
- `nltk` (for natural language processing)

You can install the required libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow nltk
```

## Data

The dataset used in this project contains a collection of questions from Quora, labeled as insincere or sincere. Ensure that the dataset is placed in the `data/` directory or adjust the paths in the notebook accordingly. [Dataset link](https://www.kaggle.com/datasets/arnavsharma45/quora-insincere-questions-dataset), download it from there.

## Notebook Structure

1. **Data Loading and Exploration**: This section involves loading the dataset, exploring the data, and visualizing the distribution of question types.
2. **Preprocessing**: Includes text cleaning, tokenization, and splitting the dataset into training and testing sets.
3. **Model Building**: Implements and trains machine learning or deep learning models for classifying questions.
4. **Evaluation**: Assesses model performance using metrics like accuracy, precision, recall, and F1-score.
5. **Results**: Presents the results and discusses the model's effectiveness in distinguishing insincere questions.

## Usage

To run the notebook, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/Bilal-ahmad8/Quora-Insincere-Questions-Classification.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Quora-Insincere-Questions-Classification
    ```

3. Open the notebook:

    ```bash
    jupyter notebook Quora\ Insincere/quora-incsincere-question.ipynb
    ```

4. Follow the instructions in the notebook to execute the code cells and analyze the results.

## Results

The notebook includes a detailed analysis of the model's performance, with confusion matrices, classification reports, and accuracy metrics. The results highlight the model's ability to effectively classify insincere questions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Thanks to the contributors to the libraries and tools used in this project, as well as to the Quora community for providing the dataset. Special thanks to the open-source community for their support and resources.
