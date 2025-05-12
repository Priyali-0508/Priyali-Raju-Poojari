## 🛡️ Project Summary

**Title:** AI-Powered Phishing Email Detector

**Objective:** Detect phishing emails using machine learning and natural language processing techniques.

---

### ✅ Project Highlights

* **Model:** TF-IDF + Random Forest
* **Dataset:** 32 manually labeled emails (16 phishing, 16 legitimate)
* **Tools:**

  * `train_model.py`: Trains and saves the phishing detection model.
  * `phishing_detector.py`: CLI tool for predicting email legitimacy.
  * `index.py`: GUI tool using Tkinter for user-friendly interaction.

---

---

### 🧪 Dependencies

```txt
pandas==2.2.3
scikit-learn==1.6.1
joblib==1.4.2
tk
```

---

### 🎯 Deliverables

* ✔️ Research Paper: `research_paper.pdf`
* ✔️ Presentation: `presentation.pptx`
* 🔗 Demo Video: YouTube link in `demo_video_link.txt`
* ✔️ Source Code: In `phishing_detector/`
* ✔️ README.md: Setup, usage, links

---

### 📦 How to Run

```bash
pip install -r requirements.txt
cd phishing_detector
python train_model.py         # Train model
python phishing_detector.py  # CLI detector
python index.py              # GUI app
```

---
