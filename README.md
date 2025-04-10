# 🚀 AutoGluon and Phi-2 Powered Risk Scoring and Fraud Detection

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
This project uses AutoGluon for risk classification and Phi-2 for explainability in fraud detection. It automates risk assessment based on financial metrics, transaction behaviors, and anomalies, predicting risk levels (Low, Medium, High) while providing AI-driven explanations for transparency.

## 🎥 Demo
📹 [Video Demo](https://drive.google.com/file/d/1uVtJ9kL1aUr2wH6f77PlQ7GiWZn1UBHq/view?usp=sharing) (if applicable)  

🖼️ Screenshots:
![WhatsApp Image 2025-03-26 at 7 40 53 PM](https://github.com/user-attachments/assets/dfce44d0-cba9-47cc-a5d8-18d464859720)
![WhatsApp Image 2025-03-26 at 7 41 14 PM](https://github.com/user-attachments/assets/45363822-2550-4e52-bec8-1f1343a64e9d)
![WhatsApp Image 2025-03-26 at 7 54 13 PM](https://github.com/user-attachments/assets/23b1ee01-68b6-4f60-8781-19168bbf95d0)

## 💡 Inspiration
The project was inspired by the need for automated, transparent risk assessment in financial fraud detection. Traditional methods struggle with scalability and interpretability, making it difficult to identify high-risk entities effectively. By leveraging AutoGluon for classification and Phi-2 for explainability, this system enhances fraud detection by providing both accurate risk predictions and clear, AI-generated reasoning.

## ⚙️ What It Does
This project automates risk assessment by:
- Predicting risk levels using AutoGluon on financial and transactional data.
- Computing a risk score based on multiple factors like jurisdiction, anomalies, and transaction behaviors.
- Generating AI-driven explanations with Phi-2 to provide reasoning for the risk classification.

## 🛠️ How We Built It
- AutoGluon was used to train a risk classification model on financial and transactional data.
- A risk scoring algorithm was designed, incorporating jurisdiction, anomalies, and transaction behaviors.
- Phi-2 LLM generates explanations for the predicted risk levels.
- User inputs are processed, risk scores are calculated, and predictions are made in real-time.

## 🚧 Challenges We Faced
- Handling inconsistencies, missing values, and discrepancies between different data sources, which can impact model performance.
- Managing the increased computational cost and complexity of risk analysis while ensuring scalability.
- Defining an effective risk scoring methodology that balances multiple risk factors, including financial metrics, transaction behaviors, jurisdictional risks, and anomalies.
- Ensuring the accuracy and reliability of risk classification models to minimize false positives and false negatives.
- Generating reliable explanations using LLMs while avoiding hallucinations and ensuring interpretability in high-stakes fraud detection.

## 🏃 How to Run
1. Clone the repository  
   ```sh
   https://github.com/ewfx/aidel-ai-avengers.git
   ```
2. Install dependencies  
   ```sh
   npm install  # or pip install -r requirements.txt (for Python)
   ```
3. Set Up Hugging Face API Key
   - Create an account on Hugging Face.
   - Generate an API key from your account settings.
   - Run the following command to authenticate
   ```sh
   from huggingface_hub import login
   login(token="your_api_key_here")
   ```
4. Open and Run the Notebook
- Machine Learning: AutoGluon for tabular risk classification
- Large Language Model: Phi-2 for explanation generation
- Backend: FastAPI / Flask (if applicable)
- Database: MongoDB / PostgreSQL (if storing data)
- Other: Hugging Face API for LLM integration

## 👥 Team
- **Tejasree M S** - [GitHub](https://github.com/tejasree1505) | [LinkedIn](#)
- **Shyamala R B** - [GitHub](https://github.com/rbshyamala) | [LinkedIn](#)
- **Sengamali K N** - [GitHub](https://github.com/) | [LinkedIn](#)
- **Vihit Naga Venkat Arekatla** - [GitHub](https://github.com/) | [LinkedIn](#)
- **Maheshwara G Yaddanapudi** - [GitHub](https://github.com/) | [LinkedIn](#)
