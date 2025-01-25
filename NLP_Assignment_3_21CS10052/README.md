# Instruction-Tuned Classification using Flan-T5  

## **Overview**  
This project explores instruction-tuned models, specifically **Flan-T5 (small and base)**, to perform **zero-shot and few-shot classification**. The goal is to classify problematic statements posted online (from platforms like Reddit and Twitter) into three categories:  
- **Normal**: Statements that don’t incite hate or offense.  
- **Hatespeech**: Statements provoking hatred or harm towards specific groups based on factors like religion, caste, or sexual orientation.  
- **Offensive**: Statements that may demean certain groups without necessarily being hateful or inciting violence.  

---

## **Objectives**  
- Understand the **Transformer architecture** and its role in modern NLP applications.  
- Experiment with **zero-shot** and **few-shot prompting** using Flan-T5 models for classification tasks.  
- Explore the impact of prompt engineering and example selection on task performance.  

---

## **Tasks**  

### **Task: Zero-shot and Few-shot Classification (100 Marks)**  

#### **Dataset**  
The dataset contains problematic statements from social media platforms like Reddit and Twitter. Statements must be classified into one of the following categories: **Normal**, **Hatespeech**, or **Offensive**. The dataset provides a detailed description of each category.  

#### **Steps**  

1. **Download Model Checkpoints**:  
   - Download Flan-T5 (small and base) checkpoints from [Huggingface](https://huggingface.co).  

2. **Zero-shot Classification**:  
   - Write a well-formatted prompt to describe the task in natural language.  
   - Append a query test sentence to the prompt.  
   - Pass it to the model for inference and process the output to classify the statement.  

3. **Few-shot Classification**:  
   - Provide the model with a few examples (input-output pairs) to describe the task better.  
   - Append the query test sentence and pass it to the model for inference.  
   - Process the output to classify the statement.  

4. **Prompt Engineering**:  
   - Experiment with different task descriptions for better performance in zero-shot settings.  
   - In the few-shot case, experiment with task descriptions and the selection of examples provided to the model.  

---

## **Environment**  
- **Platform**: Kaggle Notebooks or any Python environment supporting Huggingface.  
- **Dependencies**:  
  - Install `transformers` and `torch` libraries.  

