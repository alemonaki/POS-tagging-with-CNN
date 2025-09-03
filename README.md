# POS Tagging with Convolutional Neural Networks (CNN)

**Author:** Alkistis Lemonaki  
**Goal:** Implement a Convolutional Neural Network (CNN) for the task of Part-of-Speech (POS) tagging.  
**Dataset:** Universal Dependencies — English EWT (`en_ewt`).  

## Project Overview
This project demonstrates the use of **CNNs for sequence labeling**, applied to POS tagging.  
The notebook covers:
- Data preprocessing: tokenization, vocabulary building, padding sequences.  
- Embedding and CNN-based architecture for sequence classification.  
- Training with cross-entropy loss and optimization via Adam.  
- Evaluation using **accuracy** and **F1-score**.  

## Results
- The CNN successfully captures local n-gram patterns for POS tagging.  
- Performance results (accuracy and F1) are documented in the notebook outputs.  

## Tools
- Python, PyTorch  
- Hugging Face Datasets (`universal_dependencies`)  
- NumPy, Pandas, Matplotlib/Seaborn  

## How to Run
1. Install dependencies:
   ```bash
   pip install torch torchvision torchaudio datasets pandas numpy matplotlib seaborn
