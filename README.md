# NEW_WORD_PREDICTION

# 🔮 Next Word Prediction using LSTM

## 📌 Project Overview

This project predicts the next word in a sentence using a Deep Learning model built with **Long Short-Term Memory (LSTM)** networks. The model is trained on a text corpus, learns contextual relationships between words, and predicts the most probable next word based on the input sequence.

The project demonstrates Natural Language Processing (NLP), sequence modeling, text preprocessing, tokenization, and neural network training using TensorFlow/Keras.

---

## 🚀 Features

- Text preprocessing and cleaning
- Tokenization using Keras Tokenizer
- Sequence generation for language modeling
- LSTM-based Deep Learning architecture
- Next word prediction from user input
- Trained model saved for future inference
- Interactive prediction interface

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Pickle
- Jupyter Notebook

---

## 📂 Project Structure

```
NEW_WORD_PREDICTION/
│
├── dataset/
│   └── text_dataset.txt
│
├── model/
│   ├── next_word_model.keras
│   ├── tokenizer.pkl
│
├── notebooks/
│   └── Next_Word_Prediction.ipynb
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Workflow

1. Collect text dataset
2. Clean and preprocess text
3. Tokenize sentences
4. Generate input sequences
5. Pad sequences
6. Build LSTM model
7. Train the model
8. Save trained model and tokenizer
9. Predict the next word for new input

---

## 🧠 Model Architecture

- Embedding Layer
- LSTM Layer
- Dense Layer (ReLU)
- Output Layer (Softmax)

Loss Function:
- Categorical Crossentropy

Optimizer:
- Adam

Evaluation Metric:
- Accuracy

---

## 📊 Data Preprocessing

The preprocessing pipeline includes:

- Lowercase conversion
- Tokenization
- Sequence generation
- Padding sequences
- One-hot encoding of labels

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/ayush-kumarsinha/NEW_WORD_PREDICTION.git
```

Move into the project directory

```bash
cd NEW_WORD_PREDICTION
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

---

## 💡 Example

**Input**

```
Machine learning is
```

**Predicted Output**

```
awesome
```

*(Prediction depends on the training dataset.)*

---

## 📈 Future Improvements

- Train on larger datasets
- Use Bidirectional LSTM
- Implement GRU architecture
- Integrate Transformer models
- Add Beam Search prediction
- Deploy using Streamlit
- Deploy on Render or Hugging Face Spaces

---

## 🎯 Applications

- Smart Text Completion
- AI Writing Assistant
- Chatbots
- Email Auto-completion
- Content Generation
- Educational NLP Applications

---

## 📚 Skills Demonstrated

- Deep Learning
- Natural Language Processing (NLP)
- LSTM Networks
- TensorFlow/Keras
- Sequence Modeling
- Text Preprocessing
- Model Training
- Machine Learning Deployment

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Push the branch
6. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Ayush Kumar**

- GitHub: https://github.com/ayush-kumarsinha
- LinkedIn: https://www.linkedin.com/in/ayush-kumar-a7468827b

---

⭐ If you found this project useful, don't forget to **Star** the repository.
