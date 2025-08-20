# LoRA-Enhanced PEFT Fine-Tuning of Gemma

This project demonstrates **Parameter-Efficient Fine-Tuning (PEFT)** using **LoRA** on the **Gemma LLM** to enable domain-specific adaptation with minimal computational cost. Instead of updating all model parameters, only low-rank adapter weights are trained, making the process efficient and scalable.

---
## ✨ Features
- Fine-tuned **Gemma LLM** with **LoRA adapters** for parameter-efficient training.  
- Leveraged **Hugging Face PEFT** and **Transformers** for seamless integration.  
- Achieved optimized performance with reduced GPU memory consumption.  
- Adaptable pipeline for domain-specific text generation or classification tasks.  


## 🚀 Project Overview
- Fine-tuned **Gemma** LLM with **LoRA-based PEFT**  
- Task: Domain-specific text continuation & author attribution  
- Approach: Trainable adapter layers added while freezing the base model  
- Benefit: Efficient adaptation with reduced compute & memory usage  

---

## 🛠 Tech Stack  
- **Python**  
- **Hugging Face Transformers**  
- **PEFT**  
- **LoRA**  
- **PyTorch**  
- **Gemma LLM**  
- **Jupyter Notebook / Google Colab** 
---


## ⚡ Installation
```bash
git clone https://github.com/shruti-shreya01/LoRA-Enhanced-PEFT-Fine-Tuning-of-Gemma.git
cd LoRA-Enhanced-PEFT-Fine-Tuning-of-Gemma
pip install -r requirements.txt
```
## 🚀 How It Works

1. **Load Base Model**  
   - Import **Gemma** from Hugging Face Transformers as the foundation model.

2. **Apply PEFT with LoRA**  
   - Integrate **Parameter-Efficient Fine-Tuning (PEFT)** using **LoRA** adapters.  
   - Adapter weights are injected into the model’s target layers.

3. **Fine-Tuning**  
   - Train **only the adapter weights**, keeping the original Gemma model frozen.  
   - This reduces compute & memory usage while retaining model performance.

4. **Evaluation**  
   - Validate the fine-tuned model on a **domain-specific dataset**.  
   - Assess performance on **text continuation & attribution tasks**.

## 📊 Results
- ✅ Achieved **efficient fine-tuning** with significantly reduced GPU memory usage.  
- ✅ Demonstrated **strong performance** in domain-specific text generation tasks.  




