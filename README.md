Emotion Classification Using XLNet

=>Overview:
This project fine tunes the XLNet transformer model to classify human emotions (anger, fear, joy, sadness) from text data. It demonstrates the power of transfer learning for nuanced emotion detection.

=>Key Features:

Cleaned and balanced emotion labeled datasets.

Tokenized data with XLNetTokenizer and fine tuned XLNetForSequenceClassification.

Trained using the HuggingFace Trainer API for efficient experimentation.

Evaluated model performance using accuracy and F1-score.

Integrated inference pipeline for predicting emotions in new text samples.

=>Tech Stack:
Python, PyTorch, Transformers, HuggingFace Datasets, Scikit learn

=>Results:
Fine tuned XLNet achieved robust multi class emotion classification performance, showing strong generalization across unseen tex
