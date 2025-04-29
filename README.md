# AI-powered-resume-parser

Project Description

This project is an NLP-based resume parser that extracts skills and work experience information from resumes using AI techniques. The system combines:
SpaCy's transformer-based NER model (en_core_web_trf) for named entity recognition
HuggingFace Transformers (BERT model fine-tuned on CoNLL-03) for more advanced entity extraction
Keyword matching for identifying specific technical skills

Key features:
Extracts text from PDF resumes
Identifies skills through both keyword matching and NLP techniques
Detects work experience by recognizing organization names
Handles both text input and PDF uploads
Designed to run in Google Colab with GPU support

The project demonstrates practical application of NLP for HR/recruitment automation, showing how AI can parse unstructured resume data into structured information about candidates' qualifications.
The implementation includes compatibility fixes for CUDA and PyTorch versions, making it ready to run in Colab environments with GPU acceleration.

