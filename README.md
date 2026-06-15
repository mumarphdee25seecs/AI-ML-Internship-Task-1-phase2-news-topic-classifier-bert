# News Topic Classifier Using BERT

## Objective
The objective of this task is to fine-tune BERT to classify news headlines into topic categories.

## Dataset
AG News Dataset from Hugging Face.

## Classes
- World
- Sports
- Business
- Sci/Tech

## Methodology
1. Loaded AG News dataset.
2. Tokenized news text using bert-base-uncased tokenizer.
3. Fine-tuned BERT for 4-class news classification.
4. Evaluated the model using accuracy and weighted F1-score.
5. Created a Gradio app for live prediction.

## Technologies Used
- Python
- Google Colab
- Hugging Face Transformers
- Hugging Face Datasets
- PyTorch
- Scikit-learn
- Gradio

## Results
The model was evaluated using accuracy and weighted F1-score.

Example prediction:

Input:
Apple launches new artificial intelligence features for iPhone users

Output:
Sci/Tech

## Deployment
A Gradio interface was created to test the model with live news headlines.

## Final Summary
This project demonstrates how a pre-trained BERT model can be fine-tuned for news topic classification using transfer learning.
