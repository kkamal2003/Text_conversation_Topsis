# Text_conversion_Topsis

This repository contains code to evaluate the performance of several conversational AI models in generating responses to prompts related to music preferences and habits. The evaluation is based on metrics such as BLEU score, ROUGE scores, and response length.  

## Dependencies  
**transformers**: Used to load and interact with pretrained conversational AI models.  
**nltk**: Required for computing BLEU scores.  
**rouge_score**: Required for computing ROUGE scores.  
**torch**: PyTorch library for deep learning.  
**numpy**: Fundamental package for array computing.  

## Steps
  1. Used 5 Pre-trained model for text conversion available on huggingface.co
  2. Generated text for certain prompts.
  3. calculated Average Evaluation Score using metrics such as BLEU, ROUGE, response length.
  4. Applied Topsis on Evaluation Scores to select best model.

![image](https://github.com/kkamal2003/Text_conversation_Topsis/assets/126082752/de943e6c-9d7a-44ce-95a6-54021ff7443f)
