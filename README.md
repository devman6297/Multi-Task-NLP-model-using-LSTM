# Multi-Task NLP Model Using LSTM

Multi-Task Learning (MTL) is a machine learning approach where a single model is trained simultaneously on multiple related tasks, enabling shared learning and better generalization.

This project implements a Multi-Task NLP model using LSTM to perform multiple text classification tasks within a unified architecture.

---

## Libraries Used

- Pandas  
- NumPy  
- Scikit-learn  
- NLTK  
- TensorFlow  
- Seaborn  
- Matplotlib  

---

## Project Architecture

The following diagram illustrates the architecture of the Multi-Task Learning model:

- Architecture Diagram:  
  https://github.com/user-attachments/assets/597b47c6-33bd-4570-bbf5-894d4346f6b9

---

## Datasets

The model is trained using three different NLP datasets corresponding to three tasks:

1. Emotion Classification Dataset  
   https://www.kaggle.com/datasets/nelgiriyewithana/emotions  

2. Gender-Based Violence Detection Dataset  
   https://www.kaggle.com/datasets/gauravduttakiit/gender-based-violence-tweet-classification?select=Train.csv  

3. Hate Speech and Offensive Language Dataset  
   https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset  

---

## Model Components

### Individual Inputs
- The Multi-Task model accepts separate input text data for each task.

### Individual Outputs
- The model generates separate output layers for each task.

### Shared Core Layers
- Core layers are shared across all tasks to enable multi-task learning:
  - Embedding Layer  
  - LSTM Layer  
  - Pooling Layer  
  - Dropout Layer  

These shared layers allow a single model to learn common linguistic representations while performing multiple related tasks.
