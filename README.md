<h1 align="center"> 📄 Medical Paper Abstracts </h1> 


The purpose of this notebook is to build a NLP model to make reading medical abstracts easier.

The paper we're replicating (the source of dataset that we'll be): is avalable here https://arxiv.org/abs/1612.05251

<H3>1. Problem Definition</H3>

The goal of the dataset was to explore the ability for NLP models to classify sentences which appear in sequential order.

>In other words, given the abstract of a RCT, what role does each sentence serve in the abstract?

<H3>2. Data</H3>

Since we'll be replicating the paper above (PubMed 200k RCT), let's download the dataset they used.

We can do so from the authors GitHub: https://github.com/Franck-Dernoncourt/pubmed-rct

<H3>What we're going to cover</H3>

  * Using TensorFlow Datasets to download and explore data.
  * Creating preprocessing function for our data.
  * Batching & preparing datasets for modelling (making our datasets run fast).
  * Creating modelling callbacks.
  * Building a Model Experiments.
      * Model 1: Conv1D with Token Embedding.
      * Model 2: Tfhub Pretrained feature extraction
      * Model 3: Conv1D with Character Embedding
      * Model 4: Pretrained token embedding + character embedding + Positional embedding.

<h3>4. Result</h3>

Trained a NLP model with competitive performance to a research paper and in far less time ad with accuracy of 85.6%.

<Br>
If you liked what you saw, want to have a chat with me about the portfolio, work opportunities, or collaboration, shoot an email at <a href="mailto:mishraanmol258@gmail.com?subject=Hello%20Anmol" target="_top">
mishraanmol258@gmail.com</a> 

