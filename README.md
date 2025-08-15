# Medical Q&A Model (CareQA)

This Medical Q&A model is built upon a Large Language Model fine-tuned for domain-specific healthcare question answering.  
It was trained using the publicly available [HPAI-BSC/CareQA](https://huggingface.co/datasets/HPAI-BSC/CareQA) dataset, which contains diverse medical questions and expert-curated answers.

The primary objective of this model is to provide accurate and context-aware responses to medical-related queries in a research or demonstration setting.  
It is **not** intended to replace professional medical advice, diagnosis, or treatment.

---

## Features

- **Domain-Specific Understanding** – Fine-tuned exclusively on healthcare-related Q&A data, enabling it to answer medical questions with improved relevance and accuracy compared to general-purpose LLMs.
  
- **CareQA Dataset Training** – Leveraged the CareQA dataset, which contains carefully curated medical inquiries and answers for high-quality domain adaptation.
  
- **Context-Aware Responses** – Capable of providing multi-sentence, coherent answers that consider the context of the question.
  
- **Powered by Modern LLM Training Tools** – Developed using [Unsloth](https://github.com/unslothai/unsloth) and [PyTorch](https://pytorch.org/) for efficient fine-tuning and deployment.

---

## Authors

**Medical Q&A Model:** Fine-tuned and adapted by **Miguel Ángel Sánchez Piña**.  
**Dataset:** Publicly available [HPAI-BSC/CareQA](https://huggingface.co/datasets/HPAI-BSC/CareQA) dataset for healthcare-related question answering.  
**Frameworks:** Built using Unsloth and PyTorch.

---

## Disclaimer

This model is intended **solely for research and demonstration purposes**.  
It should **not** be used as a substitute for professional medical advice, diagnosis, or treatment.  
Always consult a qualified healthcare provider for medical concerns.
