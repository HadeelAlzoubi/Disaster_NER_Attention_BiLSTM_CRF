# **Accurate Disaster Entity Recognition Using Contextual Embeddings in Self-Attentive BiLSTM-CRF**

This project presents a novel approach to automatically extract disaster-related named entities from an annotated dataset of 1,000 online news articles. These articles are meticulously labeled with 14 crisis-specific entities derived from relevant ontologies.

Our model combines contextual word embeddings with lexicon features and encodes them using a **contextualized deep Bi-directional LSTM (BiLSTM)** network enhanced by self-attention and conditional random field (CRF) layers. A custom word embedding model, inspired by Word2Vec, is constructed to generate context-sensitive word representations. 

### **Key Highlights**
- The proposed model is extensively compared against existing word embedding approaches, including fine-tuned BERT models.
- Evaluations on an independent test set of 200 articles (with over 80,000 tokens) demonstrate the superiority of the model, achieving:
  - **Precision**: 92%
  - **Recall**: 91%
  - **Accuracy**: 87%
  - **F1-Score**: 92%

These results confirm that the proposed model outperforms general and non-contextual word embeddings, highlighting its effectiveness in disaster-related Named Entity Recognition (NER).

---

## **Project Contents**
- Python scripts implementing the BiLSTM-CRF model with self-attention.
- Annotated dataset of disaster-related news articles with 14 named entity categories.
- Pre-trained contextual word embeddings inspired by Word2Vec.

---

## **To run the model**
use the file BiLSTM_CNN_Disaster_NER.ipynb
