#  IT Support Ticket Classification using Vertex AI

This project automates the classification of IT support tickets in a university setting using a fine-tuned **Gemini model on Vertex AI**. It takes historical support queries and trains a model to predict categories.

---

##  Overview

Manual classification of support tickets is slow and inconsistent. This project streamlines that process using:
- Google Cloud's **Vertex AI**
- A fine-tuned **Gemini model**
- Training data formatted in `.jsonl`
- Inference tested via Python in Google Colab

---

##  Project Structure

```bash
it-ticket-classifier/
├── data/
│   ├── raw_tickets.csv            # Original data
│   ├── processed_tickets.jsonl    # Transformed data for Vertex AI
│
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── fine_tuning_gemini.ipynb
│   └── inference_tests.ipynb
│
├── README.md
└── requirements.txt
