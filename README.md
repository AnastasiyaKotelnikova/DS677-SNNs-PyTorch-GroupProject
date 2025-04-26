# Spiking Neural Networks with PyTorch & Norse

This repository contains the implementation of **Spiking Neural Networks (SNNs)** using **PyTorch** and the **Norse** library.  
This project was **researched, proposed, and led by Anastasiya Kotelnikova and Mehrvish Mirza** as part of the **DS677 Deep Learning** course at NJIT.  
It explores **neuromorphic computing** by implementing biologically inspired models and comparing SNNs to traditional Artificial Neural Networks (ANNs).

---

## Project Overview

Spiking Neural Networks (SNNs) are a biologically inspired class of neural networks that simulate neuron behavior using discrete spikes for energy-efficient and event-driven processing.

This project focuses on building and evaluating SNNs using time-based datasets and benchmarking them against standard deep learning models.

---

## Objectives

-  Implement an **SNN model** using PyTorch and Norse  
-  Preprocess and use neuromorphic dataset: **SHD**
-  Compare performance of **SNNs vs. traditional ANNs**  
-  Optimize SNN hyperparameters for improved training accuracy and efficiency  
-  Document results and provide research insights into neuromorphic computing  

---

## Repository Structure

```plaintext
data/            
models/          
notebooks/       # Colab notebooks for experimentation and prototyping
reports/         # Milestones, Reports, Saved checkpoints and trained models, Datasets used for training and testing
src/             
results/         

---

## Tools & Libraries

- Python 3.10  
- PyTorch  
- Norse ([github.com/norse/norse](https://github.com/norse/norse))  
- NumPy, Matplotlib, Seaborn  
- Google Colab (for experimentation)

---

## Sample Results

|   Dataset  |   Model  |   Accuracy  |    Notes               |
|------------|----------|-------------|------------------------|
| SHD        | SNN      | 84%         | LIFCell-based SNN      |
| N-MNIST    | SNN      | 92%         | Spike-trained SNN      |
| MNIST      | ANN      | 98%         | CNN baseline           |

 Additional outputs and performance logs are available in the `results/` folder.

---

## Key Concepts

-  **Neuromorphic Computing**: Simulating brain-like neural behavior using spikes  
-  **LIF Neurons**: Biologically inspired neurons with leak-integrate-fire dynamics  
-  **SNN vs ANN**: Compared accuracy, latency, and training performance  
-  **Spike Encoding**: Converting continuous input into time-based spikes  
-  **Backpropagation Through Time (BPTT)**: Used to train spike-based models

---

## Contributors

### Anastasiya Kotelnikova  
Master’s Student in Data Science at NJIT  
anastasiya.kotelnikova21@gmail.com  

### Mehrvish Mirza  
AI Certificate Student at NJIT | Analyst with a background in Finance & IT  
Currently enrolled in DS677 – Deep Learning (Spring 2025) alongside the author

---

## Course Info  
**Course**: DS677 – Deep Learning  
**Institution**: New Jersey Institute of Technology  
**Semester**: Spring 2025  

---

## 🛡 License  
📎 This project is for academic and educational use only.  
© 2025 Anastasiya Kotelnikova & Mehrvish Mirza
Email: [anastasiyakotelnikova21@gmail.com](mailto:anastasiyakotelnikova21@gmail.com)  
[GitHub Profile](https://github.com/AnastasiyaKotelnikova) • [Portfolio Website](https://anastasiyakotelnikova.github.io/Portfolio/) • [LinkedIn](https://www.linkedin.com/in/anastasiyakotelnikova/)
