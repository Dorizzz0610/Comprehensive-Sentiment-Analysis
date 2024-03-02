
# Enhancing Twitter Sentiment Analysis with RoBERTa and Tweet Length Integration

You may view our final report of this research [here](https://drive.google.com/file/d/1pNxNr6_gkSvAZyYLlhXsIOTUxfc7SIA8/view?usp=drive_link).


## Introduction
This project aims to elevate sentiment analysis on Twitter data by integrating tweet length with the RoBERTa model. The objective is to discern the underlying sentiment of tweets originally containing positive :) or negative :( smileys based solely on the text.


## Project Scope
Our approach involves comparing sentiment analysis methods to optimize performance for Twitter data. We focus on:
* Benchmarking under diverse conditions.
* Prioritizing accuracy and computational efficiency.
* Investigating advanced text representation techniques.


## Dataset and Preprocessing
Our dataset comprises tweets subjected to:
* Rigorous text normalization and cleaning.
* Robust outlier and missing value management.
* State-of-the-art text representation.


## Repository Structure
```Bash
--Data              To store the original dataset
--Manipulated       To store the trained models
--Src               Providing the code we used in this project
run.py              To get the submission file using the best model we find
```

## Dependencies
Dependencies include Python 3.8, Pandas, Numpy, Sklearn, NLTK, TensorFlow, PyTorch.

## Environment & Execution Instructions
- Run in a Python environment, preferably a virtual environment.
- Main execution file is `run.py`.
    - The `run.py` is simply a prediction function of the best model we find (Roberta with 5 fold majority voting). On GPU, the prediction should be given within minutes. To train the model, please go to src folder and check different methods. But training is very time-consuming.
