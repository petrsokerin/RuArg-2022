# RuArg-2020

Repo for solution of competition [Argument Mining Competition (RuArg-2022)](https://codalab.lisn.upsaclay.fr/competitions/786) as a task for Homework of Neural Natural Language Processing course @ Skoltech '22.

## Idea

The goal of competition is solve multi-classification task: we have text corpora and 6 task: find in texts connected with COVID-19 statements and arguments for vaccination, quarantine, masks and if they exist, classify the sentiment of arguement/statement. For solving this task different embeddings and classification models was used. 

## Repository contents

| File or Folder | Content |
| --- | --- |
| russe-wsi-kit | original repo with data and benchmarks|
| Assignment_template_v10.ipynb | jupyter notebook contains solution and used model describtions|
| math_lectures.model | weights for one of the models|
| active_res.png, wiki_res.png, btc_res.png | pictures for importing in jupyter notebook |

## Results

For every task, according F1-score, I get the next best model and embeddings:
- 'masks_stance': feature extraction 'TF-IDF', model logistic regression
- 'masks_argument': feature extraction 'TF-IDF', model logistic regression
- 'quarantine_stance': feature extraction'TF-IDF', model logistic regression
- 'quarantine_argument': feature extraction 'BERT', model support-vector-machine
- 'vaccines_stance': feature extraction 'TF-IDF', model Neural network MLP
- 'vaccines_argument': feature extraction 'BERT', model Neural network LSTM

more details you can see in jupyter notebook with more experiment details. 

## Contacts

| **Name** | **Telegram** |
|----:|:----------:|
| Petr Sokerin | @Petr_Sokerin |
