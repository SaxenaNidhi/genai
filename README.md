# Use Case : Fine-Tune a Text Classifier for Prompt Guardrails
This code repo contains generative AI use case solutions.
Run this cide with 3.11 version. 
This solution contains-
o	Public Dataset: Use the Jigsaw Toxic Comment Classification dataset (or any similar publicly available toxicity/hate speech dataset) available via Hugging Face Datasets.
o	Task Framing: Map toxicity/hate speech annotations to a binary label: “safe” (non-toxic) and “unsafe” (toxic or harmful). You may need to define a threshold on toxicity scores or use provided binary labels if available.
o	Base Model: bert-base-uncased, for sequence classification
o	Preprocessing: Tokenize the dataset’s text prompts, ensuring proper handling of sequence length, truncation, and padding.
o	Training: Fine-tune the model with one epoch. 
o	Evaluation: Training evaluation.


