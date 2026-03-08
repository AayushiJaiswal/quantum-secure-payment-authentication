# quantum-secure-payment-authentication
Quantum Secure Payment Authentication using BB84 and Fraud Detection
# Quantum Secure Payment Authentication using BB84 + Fraud Detection

## Overview
This project demonstrates a **secure digital payment authentication system** by combining **Quantum Cryptography (BB84 Quantum Key Distribution)** and **Machine Learning–based Fraud Detection**.  
The system simulates a payment workflow where each transaction is validated through a fraud detection model and secured using quantum key generation.

The project was developed and executed in **Google Colab** and integrates multiple quantum frameworks along with classical machine learning techniques.

---

## Problem Statement
Digital payment systems are vulnerable to fraud and interception. Traditional encryption methods may become less secure with the advancement of quantum computing.  

This project explores a **hybrid approach** where:
- Fraudulent transactions are detected using **Machine Learning / Quantum Machine Learning**
- Secure communication keys are generated using **Quantum Cryptography (BB84 protocol)**

---

## Objectives
- Simulate a **secure payment authentication pipeline**
- Detect fraudulent transactions using ML and QML
- Generate secure cryptographic keys using **BB84 Quantum Key Distribution**
- Demonstrate the integration of **quantum computing and cybersecurity**

---

## Technologies and Tools Used

### Programming Language
- Python

### Quantum Computing Frameworks
- PennyLane – Quantum Machine Learning
- Qiskit – Quantum circuit simulation and BB84 protocol implementation
- Cirq – Quantum circuit experimentation
- QNiverse – Quantum simulation support

### Machine Learning Libraries
- Scikit-learn
- Pandas
- NumPy

### Visualization
- Matplotlib
- Plotly

### Interface / Backend
- Gradio / Streamlit (interactive UI)
- Flask / FastAPI (backend simulation)

### Development Environment
- Google Colab

---

## Dataset
The project uses the **Credit Card Fraud Detection dataset**, which contains anonymized transaction features and labels indicating fraudulent or legitimate transactions.

Data preprocessing steps:
- Data cleaning
- Feature normalization
- Train-test split
- Handling class imbalance

---

## System Architecture

User Transaction  
↓  
Fraud Detection Model  
↓  
Quantum Key Generation (BB84 Protocol)  
↓  
Secure Authentication  
↓  
Transaction Decision (Approved / Blocked)

---

## Fraud Detection Models

### Classical Machine Learning Models
- Logistic Regression
- Random Forest

These models are used to establish a baseline performance for fraud detection.

### Quantum Machine Learning Model
Using **PennyLane**, a **Variational Quantum Classifier (VQC)** was implemented.  
Features were encoded into quantum states and processed through parameterized quantum circuits.

---

## Quantum Cryptography Implementation

The **BB84 Quantum Key Distribution protocol** was implemented using Qiskit.

Steps involved:
1. Alice generates random bits
2. Alice selects random bases for encoding
3. Qubits are transmitted
4. Bob measures qubits with random bases
5. Basis comparison between Alice and Bob
6. Secure key extraction
7. Eavesdropping detection through error rate analysis

If interception occurs, the system detects increased error rates.

---

## Payment Authentication Workflow

1. User enters transaction details
2. Fraud detection model calculates fraud probability
3. BB84 protocol generates a secure encryption key
4. Transaction security is evaluated
5. Final decision is displayed:
   - Approved
   - Blocked

---

## Features
- Fraud detection using ML and Quantum ML
- Secure key generation via BB84 protocol
- Quantum circuit simulation
- Transaction security evaluation
- Interactive user interface for payment simulation

---

## Results
The project demonstrates:
- Effective fraud probability prediction
- Secure key generation through quantum cryptography
- Integration of classical ML and quantum computing techniques

The system successfully simulates a **secure payment authentication environment**.

---

## Key Learnings
Through this project, the following concepts were explored:

- Quantum computing fundamentals
- Quantum cryptography (BB84 protocol)
- Quantum machine learning models
- Secure payment architecture
- Integration of classical and quantum systems

---

## How to Run the Project

1. Open the Google Colab notebook.
2. Install required dependencies.
3. Run all notebook cells sequentially.
4. Launch the interface to simulate a payment transaction.

---

## Future Improvements
- Integration with real quantum hardware
- Advanced quantum machine learning models
- Real payment gateway simulation
- Improved fraud detection accuracy

---

## Author
Aayushi Jaiswal  
B.Tech – Information Science and Engineering  
JSS Academy of Technical Education, Bengaluru
