# BERT Question Answering

An extractive question-answering system built with **Python, BERT, PyTorch, and Hugging Face Transformers**. The model takes a question and a given text context, then identifies and extracts the most relevant answer from the context.

## How It Works

1. A text context is provided to the model.
2. The user enters a question about the context.
3. The question and context are tokenized using a BERT tokenizer.
4. BERT predicts the start and end positions of the answer.
5. The predicted tokens are decoded into a readable answer.

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* BERT
* Natural Language Processing (NLP)

## Example

**Context:**
Sunset Motors is an automobile dealership that specializes in selling new and used vehicles. The company was founded in 2010 and is located in Lagos, Nigeria.

**Question:**
When was Sunset Motors founded?

**Answer:**
2010

## Installation

Install the required dependencies:

```bash
pip install torch transformers
```

Then run the Python script:

```bash
python bert_question_answering.py
```

The BERT model and tokenizer will be downloaded automatically the first time the program runs.

## Project Purpose

This project was built to explore **Natural Language Processing and extractive question answering using pre-trained transformer models**.
