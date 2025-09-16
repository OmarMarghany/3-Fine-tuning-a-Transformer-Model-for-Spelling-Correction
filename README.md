# ✍️ Spelling Error Detection & Correction

## 📌 Project Overview
This project implements an **automatic English spelling error detection and correction system** using a **Transformer-based sequence-to-sequence model**.  
A **BART Transformer** was fine-tuned on synthetically noised **WikiSplit data**, with custom data augmentation to simulate realistic typos.  
The system demonstrates strong performance in correcting spelling mistakes, making it useful for text preprocessing, writing assistants, and NLP pipelines.  

---

## 🚀 Key Features
- **Transformer-based Correction**  
  Fine-tuned **BART Transformer** for sequence-to-sequence spelling correction.  

- **Data Augmentation**  
  Generated realistic typos using custom augmentation methods to improve model robustness.  

- **High Accuracy**  
  - **WER (Word Error Rate): 3.17%**  
  - **CER (Character Error Rate): 2.46%**  
  - **Average Levenshtein Distance: 4.49**  

- **Hugging Face Integration**  
  Leveraged **Hugging Face Transformers** for model training and inference.  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Frameworks & Libraries:** PyTorch, Hugging Face Transformers, Datasets, NumPy, Pandas  
- **Model:** BART Transformer (fine-tuned)  
- **Dataset:** Synthetic **WikiSplit-based noisy dataset**  

---

## 📂 Project Structure
