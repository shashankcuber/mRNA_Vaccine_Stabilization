# mRNA Vaccine Degradation Prediction & RNA Secondary Structure Stabilization

This repository contains code and resources for predicting **mRNA vaccine degradation** and finding **stable RNA secondary structures**.  

📌 Accepted as a **poster paper at [ICCABS 2023](https://iccabs.org/)** 🎉  
📄 [Read the Paper (PDF)](ICCABS_2023_paper_31.pdf)

---

## 🚀 Getting Started

### 1. Dataset
Download and copy the dataset to your own Google Drive:  
👉 [Dataset Link](https://drive.google.com/drive/folders/1QrWTHn2ykLCfl6BapbO7BWvMi1soxlnJ?usp=share_link)

---

### 2. Setup Weights & Biases (wandb)
To log experiments with **wandb**, create an account and get your API key by following:  
👉 [Wandb Quickstart Guide](https://docs.wandb.ai/quickstart)

---

### 3. Running the Notebook
The main workflow is provided in the Jupyter notebook:  
**`mRNA_vaccine_stabilizer.ipynb`**

You can run it directly on **Google Colab**.

- **Training:** If you want to train from scratch, run the *Training bi-GRU* section.  
- **Inference only:** If you don’t want to train, skip training and load the pre-trained model (`bi-gru.pt`) as shown in the *Inference* section.

---

## ⚙️ Configuration Notes

If you make changes to dataset or package paths, update the following files accordingly:

1. **install.sh** → [Download](https://drive.google.com/file/d/1upYrTLzoIC4EbpWEYeW1cdnNK4pCMCT9/view?usp=share_link)  
2. **make_arnie_conf.sh** → [Download](https://drive.google.com/file/d/1upYrTLzoIC4EbpWEYeW1cdnNK4pCMCT9/view?usp=share_link)  

---

## 📌 Summary
- Predicts **mRNA degradation sites** using a **bi-GRU model**.  
- Identifies **stable RNA secondary structures** to aid vaccine design.  
- Ready-to-run pipeline with both **training and inference modes**.  
---
