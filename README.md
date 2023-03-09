# Financial Disclosure NPL and Data gathering pipeline

Python code for master thesis, including a data extraction pipeline, labeling functions and transformer fine-tuning.

Text sections embedded in annual reports might contain predictive information regarding the stock price development. The code is a suggestion of how to extract the text sections, a lableing approach and applies a deep learning model. 

### Pipeline

- Retrival of the filing URLs
- Extraction of the filing date
- Stock and Index Price retrival from the yahoo query API
- Labeling of the dataset (Stock Price Change in relation to the Index Price Change during the same period)
- Parsing the text sections Item 1A, 7 and 7A
- Parsing quality check


### Fine-tuning

- Longformer, BERT, SBERT, FinBERT
