# AM Coding Challenge - AI (NLP)

## The case study: Train a BERT NER Model on our Dataset

![AM NLP NER Challenge](https://github.com/AM-code-treasure/coding-challenge-ai-nlp-ner/blob/main/6_business_entity_recognition.png)

We have a dataset of a few hundred insurance invoices with fake customer data, perfectly suited for named-entity-recognition. 
Please use this dataset, clean it and fine-tune a BERT NER model with Pytorch (transfer learning). How you do this, is your decision.

## Requirements

- [ ] A trained NER Model, able to detect the following categories: Insurance company, Invoice Recipient Name, Invoice Recipient Address, Invoice Date, Invoice Total Amount.
- [ ] The NER model needs to be build as an API. Input of the NER Model API are png-images. You need to convert these png images via an OCR into text and process the text with your NER model. The output of the API is a json, containing the detected categories. 


## Submission Format
- Jupyter Notebook showing the code that you used to do transfer learning
-  The notebook needs to contain a function or API to use the AI model (input: png). Please provide a description for how to get it running locally. 

## Instructions
- Fork this repo
- The challenge is on!
- Finish the challenge within 3 working days. 
