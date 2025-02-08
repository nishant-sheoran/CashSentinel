# CashSentinel

## 🔥 Overview
Welcome to **ATM-SecureML** – the future of ATM security! 🏦💡 This innovative project integrates **Deep Learning** into our existing Java-based **ATM Simulator System** to detect **fake banknotes in real-time**! No more counterfeit cash ruining your financial security. Say hello to **Smart ATMs** powered by AI! 🤖💰

## 🎯 Why This Project?
Counterfeit currency is a **serious global issue** affecting financial institutions and economies. Traditional ATMs accept deposits without verifying the authenticity of banknotes. What if **ATMs could detect fake notes before processing transactions?** 🤯 That’s exactly what **ATM-SecureML** does – a cutting-edge integration of **Artificial Neural Networks (ANN)** with ATMs to **fight fraud like a pro**! 🏆

## 🛠 Key Features
- **Banknote Authentication System** 🧐 – Detects **fake vs. real** notes when users deposit money.
- **Seamless Java-Python Integration** 🔄 – ATM software talks to a **REST API** for real-time verification.
- **AI-Powered Fraud Detection** ⚡ – Uses **TensorFlow/Keras ANN** trained on the **Banknote Authentication Dataset**.
- **User Alerts & Logging** 📜 – If a fake note is detected, the system alerts the user & logs the transaction.
- **Secure & Scalable** 🔒 – Built with robust **Java, Flask, and MySQL** for performance and security.

## 🚧 How It Works
1️⃣ **User Deposits Cash** 🏧💵  
2️⃣ **System Captures Banknote Features** 🖼️✨  
3️⃣ **Java Sends Data to Python API** 🔗  
4️⃣ **AI Model Predicts Real or Fake** 🧠✅❌  
5️⃣ **Response Sent Back to ATM System** 🚀  
6️⃣ **Genuine? Deposit Success! 🎉 | Fake? User Alert! 🚨**  

## 🔬 Deep Learning Model Details
- **Dataset:** Banknote Authentication Dataset (Wavelet Transformed Image Features)
- **Features Used:**
  - Variance (VWTI)
  - Skewness (SWTI)
  - Curtosis (CWTI)
  - Entropy (EI)
- **Model:** Multi-layer **Artificial Neural Network (ANN)** built with **TensorFlow & Keras**.
- **Training:** Optimized with **Adam optimizer**, **ReLU activation**, and **Softmax classification**.

## 💻 Tech Stack
| Component           | Technology        |
|--------------------|-----------------|
| **Frontend**      | Java Swing (GUI) |
| **Backend**       | Java (Core) & JDBC |
| **Database**      | MySQL            |
| **ML Model**      | TensorFlow/Keras |
| **API**           | Flask/FastAPI    |
| **Integration**   | REST API (Java ↔ Python) |

## 🏗 Installation & Setup
### Clone the Repository
```bash
 git clone https://github.com/your-username/ATM-SecureML.git
 cd ATM-SecureML
```

### 🏦 Setting Up the ATM System (Java)
1. Open the Java project in **NetBeans/IntelliJ**.
2. Set up MySQL database and update `Conn.java`.
3. Run `ATM.java` to start the system.

### 🧠 Setting Up the ML Model (Python)
1. Install dependencies:
   ```bash
   pip install tensorflow flask numpy pandas scikit-learn
   ```
2. Train the model and save it:
   ```python
   python train_model.py
   ```
3. Start the Flask API:
   ```bash
   python app.py
   ```

## 🌟 Future Enhancements
- **Real-time Image Processing** 📷 – Scan physical banknotes instead of feature-based analysis.
- **Biometric Integration** 🔐 – Face & fingerprint authentication for even stronger security.
- **Blockchain for Transaction Logging** ⛓️ – Immutable records for fraud tracking.

## 📜 License
This project is open-source and available under the **MIT License**.

---
💡 *"Making ATMs smarter, one fake note at a time!"* 🚀

