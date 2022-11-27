<h1 align="center"> Virtual Health Medical Journals Analysis </h1> <br>
<p align="center">
  <a href="http://clipart-library.com/clipart/kc8odg89i.htm">
    <img alt="Virtual Health Medical Journals Analysis" title="Virtual Health Medical Journals Analysis" src="http://clipart-library.com/images/kc8odg89i.jpg" width="350">
  </a>
</p>

This project utilizes Text Mining Techniques to recommend Articles Textually, Contextually & based on Topics similarity for the Medical Research using abstracts from the Virtual Health Library database.

## Introduction

The primary purpose is to build a web application platform for article recommendation that will easily help medical researchers to search for articles. The results of the search, either with a keyword or a journal will, allow user to choose from the Articles based on Categorization of Results.

### Models

Following are the three models utilized for this project:

* Latent Dirichlet Allocation (LDA) Multicore 
* Latent Semantic Indexing (LSI)
* BERT NLI Sequence Transformer

### Latent Dirichlet Allocation (LDA) Multicore

This module allows both LDA model estimation from a training corpus and inference of topic distribution on new, unseen documents. LDA Multicore provides a faster implementation, especially for exceptionally large corpora as in this case. Following is the model representation.

<p align="center">
  <a href="https://medium.com/codechef-vit/latent-dirichlet-allocation-812bb8099518">
    <img alt="LDA Multicore Topic Modeling" title="LDA Multicore Topic Modeling" src="https://miro.medium.com/max/828/0*eTImSma37fd3aPka.png" width="850" height="400" />
  </a>
</p>


### Latent Semantic Indexing (LSI) Model

LSI is based on the principle that words that are used in the same contexts tend to have similar meanings. A key feature of LSI is its ability to extract the conceptual content of a body of text by establishing associations between those terms that occur in similar contexts.

<p align="center">
  <a href="https://medium.com/analytics-vidhya/nlp-with-latent-semantic-analysis-b3de6e16ad7d">
    <img alt="LDA Multicore Topic Modelling" title="LDA Multicore Topic Modelling" src="https://miro.medium.com/max/1400/1*tctmPjlqV66mR9s-I5bzMg.jpeg" width="850" height="400" />
  </a>
</p>

### BERT NLI Sentence Transformer

This is a type of Hugging Face transformers [24] typically used for natural language processing. Input for this model is the list of abstract that are cleaned during the data preprocessing.

<p align="center">
  <a href="https://www.arxiv-vanity.com/papers/1904.09675/">
    <img alt="BERT NLI Sentence Transformer" title="BERT NLI Sentence Transformer" src="https://media.arxiv-vanity.com/render-output/6552734/figures/bert_fig.png" width="850" height="400" />
  </a>
</p>

### Web Application - Article Recommender

Based on the above three models, an article recommendation web application is developed. As an input for this application, entire article or just keyword can be taken into consideration.

* Home Page:

![Home Page](screenshots/home_page_latest_1.jpg)

![Home Page](screenshots/home_page_latest_update_2.jpg)

* Topic Page:

![Topic Page](screenshots/topic_page_keyword.jpg)

* Result Page:

![Result Page](screenshots/result_page.jpg)