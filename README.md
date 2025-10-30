# 💬 Dark Sentiment Analyzer (with Debug Mode)

An elegant **Sentiment Analysis Web App** built using **PyTorch** and **Gradio**, featuring an **AI-powered text sentiment predictor** with a **modern dark interface** and a **developer-friendly debug panel**.

---

## 🌟 Features

✅ **Deep Learning Model** – Fine-tuned transformer-based sentiment classifier  
✅ **Dark-Themed UI** – Minimal and elegant interface designed for focus and readability  
✅ **Live Inference** – Instantly predicts whether a statement is *Positive* or *Negative*  
✅ **Debug Mode** – See raw logits and probability outputs for deeper understanding  
✅ **Auto Label Correction** – Automatically detects and fixes label flipping in datasets  
✅ **Interactive Web Interface** – Built with [Gradio](https://gradio.app/), deployable instantly  

---


> 🎯 Example inputs and outputs

| Input Sentence | Predicted Sentiment |
|----------------|---------------------|
| The movie was absolutely breathtaking! | Positive |
| The food was cold and tasteless. | Negative |
| Everything worked perfectly, highly recommended! | Positive |
| The app crashes every time I open it. | Negative |
| Battery lasts all day, super satisfied! | Positive |

---

## 🧠 Model Information

- **Model Type:** Transformer-based Text Classifier  
- **Framework:** PyTorch  
- **Training Data:** Custom CSV dataset with "Text" and "Sentiment" columns  
- **Labels:**  
  - `0 → Negative`  
  - `1 → Positive`  

---

## 🛠️ Tech Stack

| Component | Technology |
|------------|-------------|
| Frontend | Gradio (Dark UI) |
| Backend | PyTorch |
| Language | Python 3 |
| Deployment | Gradio Share / Hugging Face Spaces |
| Debugging | Torch + Softmax Logits Visualization |

---

## 🧩 Installation & Setup

```bash
# 1️⃣ Clone the repository
git clone https://github.com/yourusername/dark-sentiment-analyzer.git
cd bert-sentiment-analyzer

🧠 Usage

Type or paste a sentence into the textbox.

Click “🔍 Analyze Sentiment” to predict if it's positive or negative.

Optionally, click “🐞 Debug” to view raw logits and probability distribution.

🕶️ Dark Theme Design

The UI is fully dark-mode, featuring:

Teal & charcoal gradient palette

Rounded cards and hover animations

Accessible typography for low-light environments

🧰 Example Debug Output
🐞 Debug Mode:
Raw logits: [-1.372, 3.284]
Probabilities: [0.038, 0.962]


Indicates the model is 96.2% confident the text is Positive.

📈 Future Enhancements

 Add neutral sentiment classification

 Integrate multilingual support

 Enable fine-tuning directly from interface

 Host demo on Hugging Face Spaces

🧑‍💻 Author

👤 Umaim Tahir
AI & NLP Enthusiast | Python Developer | ML Engineer
📧 umaimtahir1@gmail.com


📜 License

This project is licensed under the MIT License – feel free to modify and build upon it.
