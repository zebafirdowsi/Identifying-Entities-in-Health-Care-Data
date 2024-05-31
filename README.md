# Identifying-Entities-in-Health-Care-Data

# Medical Named Entity Recognition (NER) using CRF

This project aims to build a custom Named Entity Recognition (NER) system to identify diseases and treatments from medical text data using Conditional Random Fields (CRF). The project is part of an assignment to enhance the understanding and application of NER in the healthcare domain.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [File Descriptions](#file-descriptions)
- [Results](#results)
- [Requirements](#requirements)
- [Acknowledgements](#acknowledgements)

## Overview
The main objective is to process medical text data to extract diseases and their corresponding treatments. The project involves:
1. Data preprocessing to convert tokenized words into sentences.
2. Concept identification using POS tagging.
3. Feature engineering for the CRF model.
4. Building and evaluating the CRF model.
5. Extracting and mapping diseases to treatments using a custom NER.

## Dataset
The datasets used in this project include:
- `train_sent.txt`: Training sentences (tokens).
- `train_label.txt`: Training labels for each token.
- `test_sent.txt`: Test sentences (tokens).
- `test_label.txt`: Test labels for each token.

## File Descriptions
- `train_sent.txt`: Training sentences dataset.
- `train_label.txt`: Training labels dataset.
- `test_sent.txt`: Test sentences dataset.
- `test_label.txt`: Test labels dataset.
- `medical_ner_crf.ipynb`: Jupyter Notebook containing the complete code and steps for the project.
- `README.md`: Project description and instructions.

## Results
The CRF model is evaluated using precision, recall, and F1-score. The final output includes a dictionary where diseases are keys and their predicted treatments are values. Additionally, the model predicts treatments for specific diseases, such as 'hereditary retinoblastoma'.

## Requirements
The project requires the following libraries:
- numpy
- pandas
- sklearn
- sklearn-crfsuite
- spacy
- nltk


Sure, here's a README.md file for your project:

markdown
Copy code
# Medical Named Entity Recognition (NER) using CRF

This project aims to build a custom Named Entity Recognition (NER) system to identify diseases and treatments from medical text data using Conditional Random Fields (CRF). The project is part of an assignment to enhance the understanding and application of NER in the healthcare domain.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Steps to Run](#steps-to-run)
- [File Descriptions](#file-descriptions)
- [Results](#results)
- [Requirements](#requirements)
- [Acknowledgements](#acknowledgements)

## Overview
The main objective is to process medical text data to extract diseases and their corresponding treatments. The project involves:
1. Data preprocessing to convert tokenized words into sentences.
2. Concept identification using POS tagging.
3. Feature engineering for the CRF model.
4. Building and evaluating the CRF model.
5. Extracting and mapping diseases to treatments using a custom NER.

## Dataset
The datasets used in this project include:
- `train_sent.txt`: Training sentences (tokens).
- `train_label.txt`: Training labels for each token.
- `test_sent.txt`: Test sentences (tokens).
- `test_label.txt`: Test labels for each token.

## Steps to Run
Follow these steps to run the project:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/medical-ner-crf.git
    cd medical-ner-crf
    ```

2. **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Download and place the datasets in the project directory.**

4. **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook medical_ner_crf.ipynb
    ```

## File Descriptions
- `train_sent.txt`: Training sentences dataset.
- `train_label.txt`: Training labels dataset.
- `test_sent.txt`: Test sentences dataset.
- `test_label.txt`: Test labels dataset.
- `medical_ner_crf.ipynb`: Jupyter Notebook containing the complete code and steps for the project.
- `requirements.txt`: List of required Python libraries.
- `README.md`: Project description and instructions.

## Results
The CRF model is evaluated using precision, recall, and F1-score. The final output includes a dictionary where diseases are keys and their predicted treatments are values. Additionally, the model predicts treatments for specific diseases, such as 'hereditary retinoblastoma'.

## Requirements
The project requires the following libraries:
- numpy
- pandas
- sklearn
- sklearn-crfsuite
- spacy
- nltk


## Acknowledgements
- Sumit Bhatia, Senior ML Researcher, Adobe Systems, for providing guidance on the project.
- spaCy and NLTK for POS tagging and text processing utilities.
- sklearn-crfsuite for the CRF model implementation.
