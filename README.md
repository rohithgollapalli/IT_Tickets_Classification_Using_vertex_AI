#  IT Support Ticket Classification using Vertex AI

This project automates the classification of IT support tickets in a university setting using a fine-tuned **Gemini model on Vertex AI**. It takes historical support queries and trains a model to predict categories.

---
##  What It Does

- Installs and configures Google Cloud SDK in Colab
- Authenticates both Google Cloud and Colab
- Creates a GCS bucket dynamically
- Uploads a local `input.csv` file
- Converts CSV → JSONL format
- Fine-tunes a Gemini model using Vertex AI
- Lists training jobs and tests the model with prompts
  
##  Requirements

- Google Cloud project with billing enabled
- Vertex AI and GCS APIs enabled
  
---

## Project Structure

```bash
it-ticket-classifier/
├── README.md                             # Project instructions
├── Text_Classification_using_Vertex_AI.ipynb   # Main Colab notebook
├── sample_input.csv                      # Example file for new users





