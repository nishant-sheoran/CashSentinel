# CashSentinel
## Overview
Welcome to **CashSentinel** – the future of ATM security! 🏦💡 This innovative project integrates **Deep Learning** into our existing Java-based **ATM Simulator System** to detect **fake banknotes in real-time**! No more counterfeit cash ruining your financial security. Say hello to **Smart ATMs** powered by AI! 
## Why This Project?
Counterfeit currency is a **serious global issue** affecting financial institutions and economies. Traditional ATMs accept deposits without verifying the authenticity of banknotes. What if **ATMs could detect fake notes before processing transactions?**  That’s exactly what **ATM-SecureML** does – a cutting-edge integration of **Artificial Neural Networks (ANN)** with ATMs to **fight fraud like a pro**!
## Key Features
![Github - visual selection](https://github.com/user-attachments/assets/a5b7a25a-3458-4e61-8b29-13bbff19a973)


## How It Works
![Github - visualization](https://github.com/user-attachments/assets/4eb78fd2-9946-42aa-b52d-ce4835c5c3af)


## 🔗 Project Integration: CashSentinel  
**CashSentinel** is a fusion of two projects, bringing together ATM functionalities and AI-powered counterfeit detection:  

1. **[Trinity Rich Bank](https://github.com/nishant-sheoran/Trinity-Rich-Bank)** – A Java-based ATM Simulator that supports essential banking operations like account management, deposits, withdrawals, and PIN changes.  
2. **[NoteIntel](https://github.com/nishant-sheoran/NoteIntel)** – A Deep Learning-powered Fake Banknote Detection System using an ANN to classify genuine and counterfeit currency.  

By integrating these, **CashSentinel** ensures both seamless transactions and real-time banknote authentication, enhancing security in ATM operations.  


## 💻 Tech Stack
| Component           | Technology        |
|--------------------|-----------------|
| **Frontend**      | Java Swing (GUI) |
| **Backend**       | Java (Core) & JDBC |
| **Database**      | MySQL            |
| **ML Model**      | TensorFlow/Keras |
| **API**           | Flask/FastAPI    |
| **Integration**   | REST API (Java ↔ Python) |

## 🤖 Traditional ATM vs. Deep Learning Integration

| **Aspect**                | **Traditional ATM Detection**                         | **Deep Learning Integration**                               |
|---------------------------|--------------------------------------------------------|------------------------------------------------------------|
| **Detection Mechanisms**   | Optical, magnetic, size, shape, microprinting          | Multi-feature analysis using AI (texture, shape, color, etc.)|
| **Adaptability**           | Fixed sensor-based checks                             | Continuously improves and adapts from new data              |
| **Accuracy**               | Limited to predefined security features                | More accurate with the ability to detect subtle counterfeits |
| **Detection Method**       | Relies on individual sensors for specific features     | Holistic, simultaneous analysis of multiple features        |
| **Real-Time Learning**     | Static system with predefined rules                    | AI-driven, real-time learning and adaptation                |
| **User Interaction**       | Rejects fake notes or stores them for further checks   | Intelligent alerts, feedback, and improved transaction logs  |

By integrating deep learning, **ATM-SecureML** enhances the traditional ATM security systems, providing a smarter, more adaptive solution to counterfeit note detection.

## Installation & Setup
### Clone the Repository
```bash
 git clone https://github.com/your-username/CashSentinel.git
 cd CashSentinel
```



### Setting Up the ATM System (Java)
1. Open the Java project in **NetBeans/IntelliJ**.
2. Set up MySQL database and update `Conn.java`.
3. Run `ATM.java` to start the system.


### Setting Up the ML Model (Python)
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


## Future Enhancements
![Github - visual selection (1)](https://github.com/user-attachments/assets/251e76cd-d1b3-47e9-9ecf-f45fcc7985a6)

## 📜 License
This project is open-source and available under the **MIT License**.

---
💡 *"Making ATMs smarter, one fake note at a time!"* 🚀

