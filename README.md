This was a course project for **COMS 5790 - Natural Language Processing** at Iowa State University during the Spring 2025 Semester. 

Multiple approaches were tested on a research paper dataset (redacted on request of professor) to correctly classify relevant papers. A full report of the findings can be found in `coms5790_Proj2.pdf`.

Baseline models can be found in `Project2.ipynb`, which are trained on the N-gram TF-IDF vectors of the corpus.

The BERT-based models were trained on an Azure compute environment, with the best performing deBERTa model derived from a multi-class classifier which is present in `deberta_reference.ipynb`. The script was modified accordingly to handle binary classification, with redundant code pertaining to multi-class classification removed.

In an attempt to handle class imbalance, the DeepSeek R1 LLM API provided by [together.ai](https://www.together.ai/) was utilized to synthetically generate data. The report contians more information regarding this.
