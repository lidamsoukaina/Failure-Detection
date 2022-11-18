# Failure-Detection
NLP algorithm for identification of customer reviews reporting product failures.

## Data Set - Overview

- The dataset is made of reviews scraped from Amazon website.
- Those reviews deal with tablets.
- The attributes given in the datasets are the **review id**, **the tablet model id**, the customer **review**, the **rating** given to the product, the **failure degree** label.
- The labels are given in the "Failure class" column of the csv files.
    - "IF" means "Intolerable Failure", i.e. the product broke and is unusable.
    - "TF" means "Tolerable Failure", i.e. the product broke but can be used.
    -  An empty field means that there is no known failure.

## Evaluation Metrics
To evaluate the model performance, we rely on **F1-score** and **Balanced Accuracy**.