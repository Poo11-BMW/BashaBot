# 🤖 BhashaBot – Multilingual Indian Q&A Assistant 🇮🇳

BhashaBot is a Gradio-based Question Answering (QA) assistant that supports **Kannada**, **Hindi**, and **Telugu** using multilingual transformer models. It answers questions based on provided passages or fallback examples from the L3Cube IndicQA dataset.

---

## 🧠 Project Description

**BhashaBot** allows users to:

- Ask questions in Indian languages (Kannada, Hindi, Telugu)
- Provide a custom context passage or use built-in defaults
- Receive answers using a multilingual transformer model
- Run everything locally for free with HuggingFace models

This project uses the `deepset/xlm-roberta-large-squad2` model and supports Indian regional languages with context-based inference powered by HuggingFace Transformers and Gradio.

---

## 💡 Features

- 🌐 Multilingual Support: Kannada, Hindi, Telugu  
- 🔍 Context-Aware Question Answering  
- 🤗 Powered by Transformers from Hugging Face  
- ⚡ Interactive Gradio UI  
- 🆓 100% Free – No API key needed  

---

## 📸 Screenshot

![BhashaBot UI](images/bhasha_ui.png)

---

## 📂 Dataset Used

We use publicly available data from the [L3Cube IndicQuest QA dataset](https://github.com/l3cube-pune/indic-nlp):

| Language | Example Question                          | Context                                                                                      | Answer                      |
|----------|-------------------------------------------|----------------------------------------------------------------------------------------------|-----------------------------|
| Kannada  | ಭಾರತದೆ ಮೊದಲ ಪ್ರಧಾನಿ ಯಾರು?                | ಜವಾಹರಲಾಲ್ ನೆಹರು ಭಾರತದೆ ಮೊದಲ ಪ್ರಧಾನಮಂತ್ರಿಯಾಗಿದ್ದರು.                                        | ಜವಾಹರಲಾಲ್ ನೆಹರು             |
| Hindi    | भारत का पहला राष्ट्रपति कौन था?            | डॉ. राजेंद्र प्रसाद भारत के पहले राष्ट्रपति थे।                                             | डॉ. राजेंद्र प्रसाद         |
| Telugu   | తెలంగాణ రాష్ట్ర రాజధాని ఏది?              | హైదరాబాద్ తెలంగాణ రాష్ట్ర రాజధాని.                                                          | హైదరాబాద్                   |

---

## 🚀 How to Run

### ✅ Requirements

- Python 3.8+
- pip packages:
  ```bash
  pip install gradio transformers pandas
