## 🔍 Fake Product Review Identification System

An AI-powered natural language processing application built to combat deceptive opinion spam using state-of-the-art Transformer models. 

## 🚀 Performance Overview
I evaluated two deep-learning architectures via Transfer Learning on the Cornell *Deceptive Opinion Spam Corpus* (1,600 hotel reviews):

-->BERT (Base Uncased): Achieved 88% accuracy  with balanced precision and recall.
--> RoBERTa (Robustly Optimized BERT): Achieved 90% accuracy, pushing the Fake-Review Recall rate to 97%.

## 🛠️ Tech Stack & Architecture
Language: Python
Frameworks: PyTorch, Hugging Face (Transformers, Trainer)
Visualizations: Matplotlib, Seaborn
Frontend UI: Gradio 
Infrastructure: Google Colab (T4 GPU Environment)

## 📦 How to Run the App
Click the "Open in Colab" badge at the top of the notebook file inside this repository, run all the cells to train/load the models, and enter your custom text reviews directly into the live Gradio interface to see dynamic prediction confidence scores.
