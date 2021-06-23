# MasterThesis_MSchwarz
This repository contains the code and additional data for my master thesis about AI-focused summarization of medical research. The following files are included:


Google Colaboratory notebooks:

Fine-Tuning BERT.ipynb
Fine-Tuning DistilBERT.ipynb
Fine-Tuning RoBERTa.ipynb
-> fine-tuning of the LMs with full abstract input

Fine-Tuning Single Sent.ipynb
-> fine-tuning of the LMs with sentence input

DAPT BERT sentence pairs.ipynb
-> domain-adaptive pre-training for BERT with sentence pairs

DAPT full abstracts.ipynb
-> dapt with MLM on full abstracts

AI Method Evaluation.ipynb
-> code for the evaluating the ability of the models to include AI methods


DATA:

cleaned1000.json
-> labeled dataset with 1000 abstracts

pubmed_papers.json
-> unlabeled dataset with >31500 abstracts (zipped because of github file size restriction)

sentence_pairs.json
-> dataset containing sentence pairs for DAPT (zipped because of github file size restriction)

ai_method_list.txt
-> text file with the AI terms for AI method evaluation

human_evaluation.pdf
-> the document which was used for the human evaluation


