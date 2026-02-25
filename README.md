# Evaluating Zero-Shot and One-Shot Adaptation of Small Language Models in Leader-Follower Interaction: Official Dataset and Prompt Repository

This repository contains the supplementary materials for the paper **Evaluating Zero-Shot and One-Shot Adaptation of Small Language Models in Leader-Follower Interaction**. It serves as a centralized hub for the datasets generated through data augmentation and the specific prompts utilized throughout our experimental pipeline.

# Supplemental Material: Datasets and Prompts

This repository contains the official datasets and prompts used in the experiments described in the paper: **Evaluating Zero-Shot and One-Shot Adaptation of Small Language Models in Leader-Follower Interaction**.

The goal of this repository is to ensure reproducibility and provide researchers with access to the augmented data and specific prompt templates discussed in our study.

---

## 📂 Repository Structure

The repository is organized into two main directories:

### 1. `/datasets`
This folder contains the three datasets constructed via **data augmentation** and the original phrase datasets used in the **testing phase**. Each dataset was generated using a different Large Language Model (LLM) to ensure diversity and robustness in our experiments:
* **data_aug_gemini.csv:** Data generated/augmented using Google Gemini.
* **data_aug_chatgpt.csv:** Data generated/augmented using OpenAI GPT.
* **data_aug_deepseek.csv:** Data generated/augmented using DeepSeek.
* **test_real_data.csv** Original data used in testing.
* **real_data_for_augmentation.csv** Original data used in augmentation.  

### 2. `/prompts`
This folder contains the core prompt templates used throughout the experimental pipeline:
* **promptengineering_prompt.txt:** The specific prompts used to guide the prompt engineering model 
* **scarecrow_prompt.txt:** The prompt set utilized for the Scarecrow framework 

---
