# PDF-Answering-AI

The goal of this project is to develop a model that answers questions asked from a pdf and that can be done by  Retrieval-Augmented Generation (RAG) pipeline that operates on a local GPU. The pipeline is designed to open a PDF document, process its content, and use a Large Language Model (LLM) to answer questions based on the content of the PDF. 

## What is RAG?

RAG stands for Retrieval-Augmented Generation. It was introduced in the paper "Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks". The process can be broken down into three main steps:
Retrieval: Seeking relevant information from a source given a query. For example, retrieving relevant passages of text from a PDF document based on a question.
Augmentation: Using the retrieved information to modify an input to a generative model.
Generation: Generating an output based on the augmented input. For instance, using an LLM to generate an answer based on the retrieved passages.

workflow:-

![image](https://github.com/AayushiChoudhary01/PDF-Answering-AI/assets/152921756/603dd705-529b-45cc-bae1-5570e56a146c)

### PDF Used :- 
https://pressbooks.oer.hawaii.edu/humannutrition2/

### Environment Setup :- 
this code can be directly run in google colab.

