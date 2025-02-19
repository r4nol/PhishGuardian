# 🛡️ PhishGuardian: DistilBERT for Email Security 🔥

This repository contains a complete implementation of **Phishing Email Detection** using **DistilBERT**. The model is trained to classify emails as **Phishing** or **Safe** based on their textual content.

## 🚀 Features
- Fine-tuned **DistilBERT** for phishing email classification.
- Fully compatible with **Kaggle**, **Colab** and **GitHub** deployment.
- Lightweight and efficient **email text processing** for better classification results.
- **Pretrained model ready for inference**, no need to train from scratch.  

## 📂 Repository Structure
- `PhishGuardian.ipynb` – Jupyter Notebook with complete training and evaluation pipeline.
- `phishing_model/` – Directory containing the trained model.
- `README.md` – This documentation file.

## 🔥 Usage
### 1. **Clone the repository**  
   ```bash
   git clone https://github.com/r4nol/PhishGuardian.git
   cd PhishGuardian
   ```
### 2. **Open the Jupyter Notebook**  
Open `PhishGuardian.ipynb`

### 3. **Run the Notebook**  
- Execute all cells in sequence.  
- Wait for the training process to complete (this may take some time).  
- Once finished, the trained model will be saved in the **`./phishing_model`** directory.  
- The model can then be used for phishing email classification in a separate script or API.  

## 📜 License
This project is released under the MIT License.
