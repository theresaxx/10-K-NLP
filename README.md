# Financial Disclosure NPL and Data gathering pipeline

Python code for master thesis, including a data extraction pipeline, labeling functions and transformer fine-tuning.

### Pipeline

- Retrival of the filing URLs
- Extract the filing date
- Stock and Index Price retrival from the yahoo query API
- Parsing the text sections Item 1A, 7 and 7A
- Parsing quality check


### Fine-tuning

- Longformer, BERT, SBERT, FinBERT
