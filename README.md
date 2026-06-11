# Transformer-based Sentiment Analysis of Romanized Bengali-English Code-Mixed Social Media Text

## 📌 Project Overview
This research project focuses on sentiment analysis of code-mixed social media posts (Bengali and English). A significant challenge in this domain is the use of **Romanized Bangla** (writing Bengali using the Latin alphabet), which often suffers from high spelling variation (e.g., "onek" written as "onk" or "onkkk"). 

The core objective of this project is to investigate whether **text normalization** (converting noisy Romanized text into a standardized form) can improve the performance of Transformer-based models in sentiment classification.

## 🎯 Research Goals
- Collect a benchmark dataset of Bengali-English code-mixed social media comments.
- Build a **Normalization Lexicon** to handle spelling variations in Romanized Bangla.
- Compare the performance of Transformer models (like mBERT, BanglaBERT, and XLM-R) on raw vs. normalized text.
- Perform error analysis to identify challenges like sarcasm and slang.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-learn, PyTorch/TensorFlow, Hugging Face Transformers
- **Environment:** Google Colab (GPU)
- **Version Control:** GitHub

## 📊 Dataset Structure
The dataset is stored in CSV format with the following columns:
- `id`: Unique identifier for each comment.
- `text_raw`: Original code-mixed comment.
- `category`: Topic of the comment (e.g., Sports, Politics, Tech).
- `label`: Sentiment label (Positive, Negative, Neutral).
- `notes`: Additional info (e.g., Sarcasm, Slang).

## 🚀 Roadmap
- [ ] Data Collection & Manual Labeling 📅
- [ ] Building Normalization Lexicon ⏳
- [ ] Baseline Model Implementation ⏳
- [ ] Transformer Model Fine-tuning (mBERT, BanglaBERT) ⏳
- [ ] Comparative Analysis & Error Analysis ⏳
- [ ] Research Paper Writing ⏳
