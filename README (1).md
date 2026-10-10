<h1 align="center">🛡️ Hate Speech Detection using NLP</h1>

<p align="center">
  Using Natural Language Processing and machine learning to automatically detect hateful and offensive language in text.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/NLP-Text%20Classification-green" alt="NLP">
  <img src="https://img.shields.io/badge/Machine%20Learning-scikit--learn-F7931E" alt="Machine Learning">
</p>

---

## 🔎 Overview

Social media platforms produce far more content than human moderators can review. This project applies **Natural Language Processing (NLP)** and machine learning to classify text and flag hate speech automatically, as a step toward safer online spaces.

## 📁 Repository Contents

| Folder | Description |
|--------|-------------|
| [`Hate speech detection uing NLP`](Hate%20speech%20detection%20uing%20NLP) | Code and files for the hate speech detection project |

Open the folder to see the notebook, data and outputs.

## 🧭 General Approach

```
Raw text → Cleaning → Tokenization → Feature extraction → Model training → Evaluation
```

1. **Text preprocessing:** clean the text (case, punctuation, links, stopwords) and tokenize it
2. **Feature extraction:** convert text into numerical features a model can learn from
3. **Model training:** train a classifier to separate hateful or offensive text from neutral text
4. **Evaluation:** measure performance with accuracy, precision, recall and F1-score, which matter more than accuracy alone when classes are imbalanced

## ⚠️ Limitations

- Sarcasm, context, slang and code-mixed language (such as Hinglish) are hard for text classifiers to handle
- Hate speech labels are subjective and reflect the opinions of the people who annotated the data
- Datasets are often imbalanced, so a model can look accurate while missing hateful content
- Results on one dataset may not carry over to other platforms or languages

## 🤝 Ethical Considerations

Hate speech detection models can wrongly flag certain dialects, reclaimed language, or discussions *about* hate speech, and can reflect biases in their training data. This project is for **learning and research**. It should not be used for automated moderation without human review.

## 🚀 Future Work

- [ ] Fine-tune a transformer model (BERT / DistilBERT) and compare it with classical models
- [ ] Add explainability (such as LIME or SHAP) to show why text is flagged
- [ ] Extend to Hindi and Hinglish text
- [ ] Build a simple web demo for live predictions

## 🛠️ Tech Stack

Python · Pandas · NumPy · scikit-learn · NLTK · Matplotlib · Seaborn

## 👩‍💻 Author

**Janvi Malve** | [GitHub](https://github.com/janvi-malve02) | [LinkedIn](https://www.linkedin.com/in/janvi-malve) | janvimalve12@gmail.com
