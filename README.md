# Exploring Hybrid Models for American Sign Language to Text Translation

This repository contains the research and implementation of various deep learning architectures aimed at translating American Sign Language (ASL) videos into text. The project evaluates the performance of different hybrid models in handling the spatial and temporal complexities of sign language.

## 📌 Project Overview
Sign language translation is a complex task involving the extraction of spatial features (hand shapes, facial expressions) and temporal dynamics (the movement over time). This project benchmarks several architectures to identify effective strategies for ASL-to-text translation.
<img width="1127" height="416" alt="Screenshot 2024-05-28 111041" src="https://github.com/user-attachments/assets/671baa84-299f-469b-b5b8-7622722840d5" />

### Key Objectives
* **Model Benchmarking**: Comparing different deep learning approaches, including hybrid models.
* **Feature Extraction**: Leveraging spatial and temporal data from video sequences.
* **Performance Analysis**: Evaluating how model complexity and label set size affect translation accuracy and loss stabilization.

## 🛠 Methodology
* **Dataset**: A balanced selection of ASL video data, focusing on words represented by 10 to 20 videos each to ensure consistency.
* **Architectures Explored**:
    * CNN-based models for spatial feature recognition.
    * Recurrent layers (RNN/LSTM/GRU) for capturing temporal sequences.
    * Hybrid architectures combining the above for end-to-end translation.
* **Evaluation**: Analysis of training/validation loss and accuracy across varying numbers of labels (e.g., 20 vs. 50 labels).

## 🚀 Key Results
* **Accuracy**: Achieved a maximum accuracy of 27% on a complex label set.
* **Model Capacity**: The study observed that validation loss often stabilized before 40 epochs, suggesting that performance was limited by model architecture rather than overfitting.
* **Scalability**: Demonstrated the model's potential for handling larger classification tasks even with simplified architectures.

## 👥 Authors
* Agnese Adorante
* Martina Del Gaudio
* Tommaso Giacomello
* Kristian Gjika
* Clara Montemurro
---

### Bibliography
Adorante, A., Del Gaudio, M., Giacomello, T., Gjika, K., & Montemurro, C. (2024). *Exploring Hybrid Models for American Sign Language to Text Translation*. [ML_Group9.ipynb]. Bocconi University.
