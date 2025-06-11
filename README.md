
# 📰 Somali News Classification (Individual Project – MDS231)

## 📚 Project Overview

**Title:** Automatic Classification of Somali News Texts as Political or Non-Political  
**Author:** Mohamed Nure Warsame  
**Course:** MDS231 – Data Mining (Individual Project)  
**Date:** May 20, 2025

This project was submitted as part of the **Master of Data Science program (MDS231)** under the **Data Mining** course. The objective was to build a system that automatically classifies Somali news articles into two categories:

- **Political**
- **Non-Political**

It aims to address the challenge of working with **Somali as a low-resource language** and demonstrates how modern NLP techniques can be applied to such languages.

---

## 📝 Summary of Results

A comparative analysis was done across various models:

| Model Type                          | Best Performing Variant            | F1-Score  | Accuracy |
|-------------------------------------|------------------------------------|-----------|----------|
| ✅ Traditional (MLP, LightGBM)      | LightGBM + TF-IDF                  | **98.34%**| ~98.3%   |
| ✅ CNN/RNN (no embeddings)         | CNN + BoW                          | 96.52%    | 96.51%   |
| ✅ CNN/RNN + Word2Vec              | RNN + Word2Vec                     | 93.22%    | 93.19%   |
| ✅ LLMs (SomBERTa, mBERT, SomaliLLM)| **SomBERTa** (pretrained for Somali) | **97.15%**| 96.56%   |

---

## 🧪 Key Techniques

- **Data Preprocessing:** Emoji removal, token filtering, Somali stopword removal.
- **Feature Engineering:** BoW, TF-IDF, Word2Vec embeddings.
- **Model Training:** Traditional ML (LightGBM, MLP), Deep Learning (CNN, RNN), and Transformer-based LLMs (mBERT, SomBERTa).
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score.

---

## 📊 Dataset

- **Total Articles:** 3,316 collected  
- **After cleaning:** 3,008 unique articles  
- **Label Distribution:** Political (1), Non-Political (0)  
- **Sources:** BBC Somali, SNTV, and various Somali websites

---

## 🧠 Final Insight

> **SomBERTa** was the top-performing model with the highest F1-Score and overall classification power. However, **CNN + BoW** and **LightGBM + TF-IDF** were strong alternatives, especially when computational resources were limited.

---

## 🔗 Additional Resources

For further information, detailed reports, datasets, and model outputs related to this project, please visit the following Google Drive folder:

🔗 [Project Resources on Google Drive](https://drive.google.com/drive/folders/1D1jLZ6geD24eXvQhMWtKdjVorvLDCsNS)

This includes:
- Full project PDF report
- Cleaned dataset
- Trained model files
- Charts and evaluation visuals

## 📂 Additional Resources

If you are interested in exploring the full code, models, or results in more detail, visit the following Drive folder:

🔗 [Click here for additional resources and project files](https://drive.google.com/drive/folders/1D1jLZ6geD24eXvQhMWtKdjVorvLDCsNS)

---

For questions, feedback, or collaboration inquiries, feel free to contact the project author.
