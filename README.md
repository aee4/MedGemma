"# MedGemma" 
📘 Overview

This repository contains my ongoing research work as a Research Intern at Data Intelligen and Swarm Analytics Laboratory, focused on fine-tuning multimodal models for dermatological condition classification, specifically eczema.

The goal is to evaluate and adapt the MedGemma model, a multimodal foundation model for medical image and text understanding to improve performance in identifying eczema-related descriptions and visuals.

🧩 Project Summary
✅ Current Achievements

Text Classification Performance

Achieved 80% accuracy on eczema-related text classification using an initial dataset.

Fine-tuned MedGemma with 300 synthetic text samples, improving accuracy to 100% on evaluation tests.

Deployed the fine-tuned model to Hugging Face for public access.
🔗 Check the model here

Image Dataset Preparation

Collected and preprocessed 466 eczema images for model evaluation.

Uploaded dataset for easy access and testing:
🔗 View the preprocessed dataset

Initial Model Evaluation

Tested model on 5 eczema images — predictions correctly mentioned eczema-related terms in all cases, indicating promising multimodal understanding.

Plan to expand evaluation with more images and re-fine-tune by Monday for improved performance and robustness.

Learning & Growth

Currently taking specialized courses recommended by Mr. Leonard to deepen understanding of model optimization and multimodal AI research.

🧠 Research Focus

The project explores how LoRA-based fine-tuning can enhance MedGemma’s ability to:

Recognize eczema-related features from text and images.

Align visual cues with textual understanding for dermatological diagnostics.

Adapt large-scale medical models to smaller, domain-specific datasets effectively.

🧰 Tech Stack

Model: MedGemma (Google)

Fine-tuning: LoRA adapters

Frameworks: PyTorch, Transformers

Dataset Type: Text + Image (Eczema-focused)

Deployment: Hugging Face Hub

Environment: Google Colab / Kaggle
