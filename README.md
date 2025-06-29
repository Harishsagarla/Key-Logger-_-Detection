#Real-Time Keylogger Detection and Notification System

🔒 A cutting-edge cybersecurity solution blending AI, machine learning, and blockchain to detect and alert users about keylogger threats in real time.
📋 OverviewThe Real-Time Keylogger Detection and Notification System is an advanced, scalable cybersecurity platform that leverages machine learning, deep learning (LSTM), and blockchain technology to identify keylogger activities instantly. It monitors system metrics like CPU load, memory usage, typing speed, and network traffic to detect suspicious behavior.

**Key Components:  **

1.Instant monitoring and alert system  
2.Behavior-driven anomaly detection using AI  
3.Secure, unalterable audit logs via blockchain  
4.Privacy-preserving federated learning

**🌟 Features🧠 AI Algorithms:**
Logistic Regression, Random Forest, LSTM
Federated Learning: Local model training with global aggregation
Blockchain Records: Immutable logging of events using SHA-256 
Instant Detection: Identifies keyloggers through system metrics
Visual Insights: Charts, confusion matrices, and ROC curves
Privacy-First: Keeps sensitive data on local devices  
Technology Stack  


**Component Technology**


1.Programming Language Python
2.ML/DL Frameworks scikit-learn, TensorFlow
3.Data Normalization    MinMaxScaler, StandardScaler
4.Blockchain  Custom private blockchain (Python)
5.Visualization Matplotlib, Seaborn
6.Real-Time Monitoring psutil library


**📊 Model Performance**


 
Model         |    Random Forest         Logistic Regression        LSTM
Accuracy      |     89.8%                       85%                  87.2%
Precision     |     91%                         85%                  88%
Recall        |     90%                         83%                  89%
F1 Score      |     90%                         84%                  88%


📉 Insights: LSTM excels at capturing time-based patterns; Random Forest is the fastest.  
🧩 System Design  
Data Creation  

**Generates synthetic data (CPU, memory, keystrokes, network) **
Labeled using rule-based heuristics

**Preprocessing  **

Applies MinMax scaling  Formats data into 3D arrays for LSTM

Model Training  

Local training on devices via federated learning  
Models evaluated with trust scores based on accuracy

Blockchain Integration  

Logs model updates and detection events in secure blocks  
Ensures tamper-proof records with SHA-256 hashing

Detection & Notifications  

Real-time predictions using LSTM  
Alerts triggered for suspicious patterns

📸 Visual Outputs📈 Model accuracy charts💡 Feature importance (keystroke patterns and network activity lead)🔒 Immutable blockchain logs for auditing📉 ROC Curves: LSTM outperforms RF and LR  
🚀 Future Enhancements  

Extend detection to ransomware and spyware  
Incorporate graph-based threat detection  
Use reinforcement learning for dynamic model updates  
Deploy in enterprise settings

📝 Contributors  

N. Keerthi Shivani  
T. Sai Sathvika  
Sai Chandrasekhar RS  
S. Harish

📜 LicenseThis academic project is licensed under the MIT License for educational use.
