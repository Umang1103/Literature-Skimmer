# SkimLit

NLP classifier to segregate abstract sentences into the role they play (i.e. objective, methods, results, etc) to enable researchers to skim through the literature. Implemented using the (**PubMed 200k RCT**) dataset.

Achieved the best **accuracy** of **84.30%** and **F1-score** of **0.8395** using a tribrid model composed of token-level embeddings model (using Universal Sentence Encoder), character-level embeddings model(using bidirectional LSTM) and a concatenated model of total no. of lines and each line number.

## Tribrid Model
![alt text](https://github.com/Umang1103/Literature-Skimmer/blob/main/model.png)
