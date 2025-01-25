# POS Tagging and Emotion Recognition  

## **Overview**  
This project focuses on implementing Natural Language Processing (NLP) techniques, specifically Part-of-Speech (POS) tagging and Emotion Recognition. The goal is to enhance understanding and application of these tasks, culminating in the creation of a custom pipeline to integrate POS tagging features into emotion classification models.  

## **Objectives**  
- Implement a POS Tagger from scratch using the Viterbi Algorithm.  
- Build and evaluate an emotion recognizer using TF-IDF sentence embeddings.  
- Enhance the emotion recognizer by integrating POS tagging features.  
- Analyze and compare the performance of models with and without POS tagging features.  

## **Tasks**  

### **1. POS Tagger Implementation**  
- **Dataset**: Treebank corpus (from NLTK).  
- **Methodology**:  
  - Implemented the Viterbi Algorithm (dynamic programming) for POS tagging without using any in-built library.  
  - Calculated transition and emission probabilities for POS tagging.  

---

### **2. Vanilla Emotion Recognizer **  
- **Dataset**: Twitter Messages corpus (available via Hugging Face).  
- **Methodology**:  
  - Preprocessed text and created sentence embeddings using TF-IDF.  
  - Trained a classical classifier (Naive Bayes or SVM) to classify emotions into six categories: **joy, sadness, anger, fear, love, and surprise**.  

---

### **3. Improved Emotion Recognizer**  
- **Enhancements**:  
  - Used the custom POS tagger to tag the dataset.  
  - Integrated POS tag features with sentence embeddings in a custom pipeline.  
  - Trained the same classifier with the new features.  

---

### **4. Report **  
- Documented observations and compared the performance of the POS-tag-enhanced model with the baseline model.  
- Included classification reports and confusion matrices for the test split.  
- Highlighted advanced modifications and insights.  

---

## **Environment**  
- **Platform**: Kaggle Notebooks.  
- Ensure all cells are executed sequentially for smooth execution.  
- Install the required datasets and libraries as outlined in the notebook.  

---