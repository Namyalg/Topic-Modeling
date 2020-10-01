# Topic-Modeling

### Use the notebook : COVID-title-final-groupwork.ipynb (this has the LDA model)
### Use the notebook : COVID-LSA-Finalwork.ipynb (this has the LSA model)
### Use the dataset : COVID-19_title.csv
### Use this google doc to add in your results and conclusions: https://docs.google.com/document/d/1g6U86VO9ffv9M2yU8uz2INr77U9YFSxMQseBHqiryoQ/edit

Topic modelling is a technique to classify the number of topics a given text article contains.
The method that is explained as follows:
- first u take the text/document. Then do the basic pre-processing and identify or try to classify and identify the different groups, or topics that can identified.
- The next is to group sentences with those topics together.


So first you need to identify the topics then get the content pertaining to that topic.


Given a set of documents u need to identify all the topics that are spoken about, then given an article u should be able to classify it
and also classify the existing documents into topics or groups. The number of groups needs to be mentioned explicitly, but the goal here is to assign that value K based on some paramters and not do it manually

Most common in LDA
Documents exhibit multiple topics - LDA
Latent Dirchilet Allocation

Latent : Cannot be seen but is observed by some characterstics

Dirchilet is a distribution where total probablity is 1 of all

Allocation : is exactly what it means

VISUALIZING THE topic modeling
https://github.com/bmabey/pyLDAvis

## LSA
Latent semantic analysis
https://www.datacamp.com/community/tutorials/discovering-hidden-topics-python

## Topic model evaluation
This is a walkthrough guide on hyperparameter tuning related to the alpha and beta and coherence

https://towardsdatascience.com/evaluate-topic-model-in-python-latent-dirichlet-allocation-lda-7d57484bb5d0

### Official docs for coherence and the Gensim library
https://radimrehurek.com/gensim/models/coherencemodel.html
