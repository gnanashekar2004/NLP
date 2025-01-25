# Text Summarization using Recurrent Neural Networks (RNNs)  

## **Overview**  
This project involves implementing a Seq2Seq model using Recurrent Neural Networks (RNNs) to perform text summarization on two datasets: the **CNN/Daily Mail** dataset and the **Wikipedia Summary** dataset. The goal is to build, train, and evaluate a text summarization model and perform qualitative analysis of its performance on unseen data.  

## **Objectives**  
- Explore the **CNN/Daily Mail** dataset to understand its structure.  
- Build and train a Seq2Seq model for text summarization using RNNs (or LSTMs).  
- Test the trained model on a new dataset (**Wikipedia Summary**) and evaluate its performance.  
- Perform a qualitative analysis of the results and provide insights.  

---

## **Tasks**  

### **Part 1: Data Exploration and Model Building **  

#### **Task 1: Data Exploration with CNN/Daily Mail Dataset**  
- **Description**:  
  - Performed exploratory data analysis on the **CNN/Daily Mail** dataset to understand its structure.  
  - Inspected the data structure, including headlines and stories.  
  - Explored most frequent words and sentence lengths.  
  - Cleaned the text by lowercasing, tokenization, and removing special characters.  
  - Provided visualizations of word frequency distributions and sentence lengths.  

#### **Task 2: Build and Train Seq2Seq Model for Text Summarization**  
- **Steps**:  
  1. **Preprocess the Text**:  
     - Tokenized, padded, and created a vocabulary.  
  2. **Build the Seq2Seq Architecture**:  
     - Implemented an encoder-decoder architecture with optional attention mechanism.  
     - Experimented with hyperparameters to optimize performance.  
  3. **Train the Model**:  
     - Trained on the **CNN/Daily Mail** dataset (train split).  
     - Evaluated on the test split using ROUGE scores (**Rouge-2 and Rouge-L**).  
  - **Expected Outcome**: The model summarizes unseen articles with reasonable accuracy.  

---

### **Part 2: Applying the Model to New Data**  

#### **Task 3: Test the Model on Wikipedia Summary Data**  
- **Description**:  
  - Tested the trained Seq2Seq model on the **Wikipedia Summary** dataset (first 10k rows).  
  - Preprocessed the data and reported evaluation results.  

---

## **Environment**  
- **Platform**: Kaggle Notebooks.  
- Ensure all cells are executed sequentially for smooth execution.  
- Install the required datasets and libraries as outlined in the notebook.