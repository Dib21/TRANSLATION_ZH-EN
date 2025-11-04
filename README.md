# ZH-EN-POETRY
This project is an experiment in automatic translation from English to Chinese that compares two different prompting techniques for a Large Language Model (LLM). Objective: To verify whether an advanced prompting technique called Chain of Thought (CoT) produces higher quality translations than a direct and concise baseline model.

Model used: mistralai/Mistral-7B-Instruct-v0.2.
Dataset: The chosen dataset is a standard English-Chinese translation dataset (iwslt2017) of 8549 rows, of which a sample of 100 sentences is used for the experiment.
Evaluation Metric: The BLEU (Bilingual Evaluation Understudy) score, a standard metric for measuring the quality of a machine translation by comparing it to a human reference translation. A higher score indicates a better translation.
Automatic analysis between CoT and Non_CoT: The two models will be compared on 100 random samples and evaluated by an LLM judge who will decide which of the two has a higher BLEU average.
