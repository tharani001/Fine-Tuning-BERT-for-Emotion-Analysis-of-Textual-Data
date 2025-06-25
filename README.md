# 🤖 BERT Fine-Tuning for Emotion Classification

### Overview  
This project fine-tunes a pre-trained **BERT base** model to:

- Tokenize and preprocess emotional text data using transformer-compatible format  
- Add a classification head for 6-class multiclass emotion prediction  
- Fine-tune using Hugging Face's `Trainer` API with custom training arguments and metrics  
- Evaluate model on test data and deploy for real-time emotion detection from raw text  

---

### 🧩 Key Features  
🧠 Efficient tokenization producing `input_ids`, `attention_mask`, and labels  
🛠️ Custom classification head for emotion-specific sequence classification  
📊 Evaluation with precision, recall, F1-score, and accuracy via scikit-learn  
🚀 Inference-ready pipeline with saved fine-tuned model  

---

### 🛠️ Tech Stack  
**Model**: BERT base (uncased) with custom classification head  
**Frameworks**: Hugging Face Transformers, PyTorch, scikit-learn  
**Dataset**: Emotion-labeled text (custom or public datasets like GoEmotions)  
**Training**: Hugging Face `Trainer` API with custom metrics and hyperparameters  
