
**🧠 Introduction**

An AI-powered email phishing detector developed using Python and machine learning as part of the Digisuraksha Internship Program 2025. This tool analyzes the textual content of emails to classify them as phishing or legitimate, using a Random Forest classifier with TF-IDF vectorization. It features both a Command-Line Interface (CLI) for fast testing and a Graphical User Interface (GUI) for ease of use. Lightweight, fast, and effective, this project serves as an educational or prototype-level solution for detecting phishing threats.

**🚨 Problem Statement**

Phishing emails are crafted to trick users into revealing sensitive information such as passwords, bank details, or login credentials. As attackers grow more sophisticated, traditional email filters often fail to detect these threats.
This project aims to build an AI-based email phishing detector that classifies emails as phishing or legitimate based on their content using machine learning. The tool enhances digital safety by providing instant feedback on email authenticity.

**🧰 Features**
- **Text Preprocessing**: Cleans and prepares email content for analysis.
- **Feature Extraction**: Utilizes techniques like TF-IDF to extract meaningful features.
- **Model Training**: Implements ML algorithms such as Logistic Regression and Random Forest.
- **Prediction**: Classifies emails as 'Phishing' or 'Legitimate'.
- **Evaluation**: Assesses model performance using metrics like accuracy and F1-score.

📈 **Workflow Diagram**

Email Content -> TF-IDF Vectorization -> Random Forest Classifier -> Prediction: Phishing / Legitimate

**⚙️ Setup Instructions**
✅ Prerequisites

- Python 3.7 or higher
- Internet connection to install packages
- Tkinter (for GUI; comes pre-installed on Windows/macOS)
    - On Linux: run `sudo apt install python3-tk`📦 Step-by-Step Installation

1. **Clone the Repository**
   🔗 [GitHub Repository](https://github.com/Priyali-0508/phishing-email-detector.git)
```bash
git clone
[GitHub Repository](https://github.com/Priyali-0508/phishing-email-detector.git)
cd phishing-detector/tool/source_code
```
2. **Install Dependencies**
 ```
pip install -r ../requirements.txt
 ```
3. **Train the Model**
 ```
python train_model.py
This will save the model to 'model/phishing_model.pkl.'
 ```
4.**Run the CLI Tool**
```
python phishing_detector.py
```
5. **Run the GUI Tool**
```
python index.py
```
**Screenshot**
 1. Train model
    ![train model](https://github.com/user-attachments/assets/f14d6fd3-897b-4ab4-a888-0b4b1f99110a)

2. phishing_detector
![phising dtector(1)](https://github.com/user-attachments/assets/9898b6e8-ba6a-4848-8322-9b4101d4f281)
![phising dtector(2)](https://github.com/user-attachments/assets/1affe4e5-466c-49a9-9bf5-476af2fd5428)

3.GUI 
![GUI (1)](https://github.com/user-attachments/assets/5fb20677-0b92-434a-91be-bd41033a33e9)
![GUI(3)](https://github.com/user-attachments/assets/16573076-405d-4328-97a1-98e2aaed21ab)
![GUI(4)](https://github.com/user-attachments/assets/b9397966-d90e-4072-b9d4-beb9c18e0b6d)
![GUI(5)](https://github.com/user-attachments/assets/d1537778-5e2d-4389-8d0a-4b6cf9e20a2f)

**👤 Developed By**

**Priyali Poojari**

**Digisuraksha Internship Program**

Date: 12-May-2025

**License & Disclaimer**

This project is released under the MIT License. See the LICENSE file for details.

**Disclaimer:**

This phishing detection tool is intended for educational and research purposes only. It does not guarantee 100% accuracy. Users should exercise caution and complement it with other security measures when handling suspicious emails.





