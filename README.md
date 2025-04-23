# Deep Learning - Project 2

## Team: Deep Fried Learning
- **Rahil Singhi** (rs9174@nyu.edu)  
- **Alper Mumcular** (am14533@nyu.edu)  
- **Divya Srinivasan** (ds7852@nyu.edu)  

### Institution:  
New York University

---
Note: Jupyter file only exists for models 2, 3, 4, 5, 9 (best model), 13 inside corresponding folder. The other models have only difference what is described in their folder's name. The rest of their code is exactly the similar.

## Project Overview

This is the second project for the Deep Learning course at NYU. The objective of this project was to fine-tune a RoBERTa-base model using LoRA (Low-Rank Adaptation) under a strict constraint of fewer than 1 million trainable parameters.

### Best Scoring Model:
- Our best scoring model achieved an accuracy of **0.87175**.
- The model can be found in the folder `best model - model 9 - 6 rank 6 alpha - 0.87175` with the notebook file located at:  
  `best model - model 9 - 6 rank 6 alpha - 0.87175/0_87175.ipynb`.

---

## Report:
- A detailed report for the project can be accessed in the file:  
  `project_report.pdf`.

---

## Setup & Execution:
1. Clone this repository.
2. Go inside `best model - model 9 - 6 rank 6 alpha - 0.87175` and find notebook file inside the folder
3. Upload the notebook to Google Colab to view and run the best model.
4. Upload `test_unlabelled.pkl` to Google Colab. You may run the whole code. (May ask wandb auth, make sure you authenticate)
