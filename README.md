# Generative AI for Developers

## LLMs (Large-Language Models) and Transformer Models

### LMM
A sophisticated deep learning algorithm. Capable of handling,
* Summarization
* Translation
* Classification
* Text generation

### Datasets
trained on enormous data on the Internet like Reddit and Wikipedia. The datasets are huge at petabyte levels (which is 1,000 terabytes).
* Petabytes level datasets
* 500 billion printed pages
* huge parameter size

### Top LLMs
Pathways Language Model (PaLM)
* April 2022
* Google
* 540B parameters

Megatron-Turing Natural Language Generation (MT-NLG)
* October 2021
* Nvidia and Microsoft
* 530B

GPT-3
* June 2020
* OpenAI
* 175B

LaMDA (Language Model for Dialogue Application)
* May 2021
* Google
* 173B

GPT-4
* March 2023
* OpenAI
* over 1T?

### Cost of LLMs
A study from AI21 estimates that training 1.5 billion parameters can cost $1.6 million. 
* 1.5 billion parameters at $1.6 million
* inference cost: $87,000 for a signle AWS instance per year

## AI Evolution

### Natural language processing (NLP) 
In 1965 MIT Professor Joseph Eisen Bal developed the first chatbot called Eliza.

#### General principles of NLP.
* Tokens - break down language into components and attached numbers to them. This is known as pre-processing or tokenization.
* Tagging parts of speech, Entity recognition, Topic modeling

Progress has been slow until 2021 when deep learning became a major force in AI. Researchers start to use Recurrent Neural Networks (RNN). RNN will ingest data in a time sequence.

#### Changes with RNNs
* Long short-term memory (LSTM) models
* Challenges with large text
* Emergence of attention models

#### Word2Vec Model
Efficient estimation of word representations in vector space. 
* word embeddings
* better understand the context of the words
* processing with a neural network
* windows

#### Transformer Model
In 2017 Google researchers published an influential paper called "attention is all you need".

* the Encoder
* positional encodeing
* multi-headed attention
* masked mmulti-headed attention

#### type of transformers
* encorder-only models (Bert)
* decorder-only models (gpt3)
* encoder-decorder models (google's T5)
* parallel processing with GPUs
* Pretrained models














