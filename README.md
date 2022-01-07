# Assessing-MT

Assessing open-source MT models in terms of their abilities to preserve the level of formality, politeness and sentiment. See this [notebook](https://github.com/liye/Assessing-MT/blob/main/Assessing_Style_Preservation_with_MT.ipynb) for details. 

### Data

Diagnostic test data (and translations) used in the notebook are saved under `data`. They are sampled from the following sources:

* Formality: sentences processed from the [Enron corpus](https://www.cs.cmu.edu/~./enron/) released by Madaan et al., see this [repo](https://github.com/tag-and-generate/politeness-dataset) for details.  
* Politeness: [Customer Support on Twitter](https://www.kaggle.com/thoughtvector/customer-support-on-twitter) for English, and [Large-scale Cleaned Chinese Conversation (LCCC)](https://github.com/thu-coai/CDial-GPT) for Chinese. 
* Sentiment: [Amazon product data](http://jmcauley.ucsd.edu/data/amazon/)

Note that to respect Twitter's terms of service, we do not include tweet contents in our data, but instead provide IDs from which one can retrieve the content from the original source. 

### Classifiers 

Pre-trained style classifiers used in the notebook can be downloaded from the following links:

* Formality: [Google drive link](https://drive.google.com/drive/folders/1__QdEuOanLqJI2cfpLuTfiPoI_aMFyYe?usp=sharing)
* Politeness (English): [Google drive link](https://drive.google.com/drive/folders/1wgjt48TDN1nXgRLPbKa8_j4zhXM7_RbB?usp=sharing)
* Politeness (Chinese): [Google drive link](https://drive.google.com/drive/folders/1qwJC5tLMmWQLGhc5bQolgYMg-8maP_Ak?usp=sharing)
* Sentiment: [nlptown/bert-base-multilingual-uncased-sentiment](https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment)

