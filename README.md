# Shakespearean-Text-Generation-Analysis

### Overview
This project implements a chaacter-level Recurrent Neural Network (RNN) using PyTorch to generate text in the style of William Shakespeare. The model is trained on the *Tiny Shakespeare* dataset and learns to predict the next charcter in a sequence. 

### Objectives
- Build a simple RNN using PyTorch
- Train the model on Shakespeare text data
- Implement one-hot encoding for input sequences and targets
- Generate 100 words of text based on a seed input
- Evaluate model performance using training loss

### Dataset
- Language: English
- Type: Character-level text data

### Model

- Input: One-hot encoded charcters
- Model: *nn.RNN*
- Output: Next character prediction

### How to Run
1. Clone the repository
2. Install dependencies:
  pip install torch numpy requests
3. Run the notebook 
4. Train the model (10 epochs)
5. Generate text from a seed input
  
### Conclusion
This project demonstrates how a simple RNN can learn patterns in text data and generate new sequences. While the generated text is not perfect, it reflects the model's ability to capture underlying character-level structures in Shakespearean language.



