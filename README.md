# emotion-classifier-xlnet

A compact project showing how I fine tuned XLNet for emotion classification (fear, joy, anger, sadness).  
This repo focuses on data cleaning, balancing, and a reproducible pipeline for training and inference.

## What this repo contains
- Data cleaning & preprocessing scripts  
- Dataset balancing utilities (oversample / undersample)  
- Training script using Hugging Face `Trainer`  
- Simple inference pipeline script using Hugging Face `pipeline`  
- Example config and requirements

- Problem: messy text & imbalanced labels cause poor results  
- Approach: clean → balance → fine-tune → use pipeline for predictions  
- Result: stable accuracy after ~3 epochs (on my dataset)

