# Transformer-Summarizer

This is the second project I have built in the **Natural Language Processing with Attention Models** course on Coursera.

This readme is taken exactly from the project description in the Notebook itself.

<img src = "transformerNews.png">

Summarization is an important task in natural language processing and could be useful for a consumer enterprise. For example, bots can be used to scrape articles, summarize them, and then you can use sentiment analysis to identify the sentiment about certain stocks. Anyways who wants to read an article or a long email today, when you can build a transformer to summarize text for you. Let's get started, by completing this assignment you will learn to:  

- Use built-in functions to preprocess your data
- Implement DotProductAttention
- Implement Causal Attention
- Understand how attention works
- Build the transformer model
- Evaluate your model
- Summarize an article

As you can tell, this model is slightly different than the ones you have already implemented. This is heavily based on attention and does not rely on sequences, which allows for parallel computing.      

## Outline

- Introduction
- Part 1: Importing the dataset
    - 1.1 Encode & Decode helper functions
    - 1.2 Defining parameters
    - 1.3 Exploring the data
- Part 2: Summarization with transformer
    - 2.1 Dot product attention
        - Exercise 01
    - 2.2 Causal Attention
        - Exercise 02
    - 2.3 Transformer decoder block
        - Exercise 03
    - 2.4 Transformer Language model
        - Exercise 04
- Part 3: Training
    - 3.1 Training the model
        - Exercise 05
- Part 4: Evaluation
    - 4.1 Loading in a trained model
- Part 5: Testing with your own input
    - Exercise 6
    - 5.1 Greedy decoding
        - Exercise 07   
