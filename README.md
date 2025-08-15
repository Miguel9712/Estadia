
# LLM FINETUNE AND ENTERPRISE TOOLKIT INTERSHIP

This repository contains the work developed during my internship project **"LLM Finetune and Enterprise Toolkit"**.  
The project focuses on fine-tuning Large Language Models (LLMs) for enterprise-oriented applications, showcasing two specialized models:

1. **OCR Model** – An optimized revision of a publicly released model by [Salesforce AI Research](https://huggingface.co/Salesforce) for improved Optical Character Recognition (OCR) performance.
2. **Medical Q&A Model** – A domain-specific Question Answering model trained on the public dataset [HPAI-BSC/CareQA](https://huggingface.co/datasets/HPAI-BSC/CareQA) for healthcare-related inquiries.



## ⚠️ Disclaimer

The **Medical Q&A model** is intended for research and demonstration purposes only.  
It should **not** be used as a substitute for professional medical advice, diagnosis, or treatment.

## Project Overview

The repository is organized into multiple branches to separate different parts of the project:

- **`main`** – This branch (you are here) contains the main README and project documentation.
- **`showcase`** – Demonstrations, example runs, and showcases of both models.
- **`model-tests`** – Experiments, evaluation scripts, and test results.
- **`ocr-model`** – Complete codebase for the OCR fine-tuned model.
- **`medical-qa`** – Complete codebase for the Medical Q&A model.
## 📄 License

The repository contains code and models that use publicly available datasets and pre-trained models.
Check each branch for specific licenses and usage terms.
## Models in Detail

### 1. OCR Model
- **Base Model:** Originally developed by Salesforce AI Research, available on Hugging Face.
- **Enhancements:**  
  - Adapted and fine-tuned for improved image-to-text OCR tasks.
  - Optimization steps to increase accuracy and robustness.
- **Use Case:** Extracting textual information from images for enterprise document processing and digitization pipelines.

### 2. Medical Q&A Model
- **Dataset:** [HPAI-BSC/CareQA](https://huggingface.co/datasets/HPAI-BSC/CareQA) (publicly available medical Q&A dataset).
- **Training Stack:** [Unsloth](https://github.com/unslothai/unsloth) + [PyTorch](https://pytorch.org/).
- **Capabilities:**  
  - Handles domain-specific healthcare questions.
  - Designed for informational purposes — not for real-world medical decision-making.## Authors

**Original OCR Model:** [blip-image-captioning-large](https://huggingface.co/Salesforce/blip-image-captioning-large)  
Developed by Salesforce AI Research, publicly released on Hugging Face.

**Modified OCR Version:** Adaptation and fine-tuning for enhanced OCR capabilities by Miguel Ángel Sánchez Piña.  

**Datasets**: Training and fine-tuning leveraged publicly available datasets for OCR and image understanding tasks.

**Medical Q&A Model:** Trained by Miguel Ángel Sánchez Piña using the public dataset [HPAI-BSC/CareQA](https://huggingface.co/datasets/HPAI-BSC/CareQA) for healthcare-related question answering.  
Built with Unsloth and PyTorch for domain-specific fine-tuning.


## Acknowledgements

Special thanks to the Hugging Face community and Salesforce AI Research for their open-source contributions, my teachers and friends which made this work possible.
