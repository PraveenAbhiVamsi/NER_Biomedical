
---

# Medical Entity Recognition using Conditional Random Fields (CRF)

This repository contains code for training and using a Conditional Random Fields (CRF) model for Medical Entity Recognition (NER) using Python and scikit-learn.

## Overview

Medical Entity Recognition is a crucial task in Natural Language Processing (NLP) that involves identifying and classifying entities such as diseases, treatments, and patient information in medical texts. This project focuses on training a CRF model to perform this task.

## Dataset

The dataset used for training and testing the CRF model is located in the `Dataset` directory. It contains the following files:
- `train_sent`: Training sentences.
- `train_label`: Labels corresponding to training sentences.
- `test_sent`: Test sentences.
- `test_label`: Labels corresponding to test sentences.



```
```

## Usage

1. Clone this repository:
```
git clone https://github.com/PraveenAbhiVamsi/NER_Biomedical.git
```

2. Navigate to the project directory:
```
cd medical-entity-recognition-crf
```

3. Run the CRF model training script:
```
python train_model.py
```

4. Once the model is trained, you can use it to perform Medical Entity Recognition on new text data.

## Model Evaluation

The performance of the CRF model is evaluated using standard metrics such as precision, recall, and F1-score on the test dataset.

## Results

The results of the model evaluation are presented in the form of performance metrics and can be found in the code file output


## Acknowledgments

- Special thanks to [SpaCy](https://spacy.io/) for providing the pre-trained English language model used for POS tagging.
- Special Thanks to **Leela** (https://github.com/LEELAPRIYA) for being supportive partner of this project 
---
