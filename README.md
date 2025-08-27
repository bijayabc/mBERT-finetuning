# mBERT Fine-Tuning Experiments on Nepali sentiment analysis

This repository contains Google Colab notebooks exploring different fine-tuning strategies for multilingual BERT (mBERT) on Nepali, a low-resource language on sentiment analysis data with 52k training samples. The goal is to investigate which strategies (full fine-tuning, partial layer fine-tuning, or adapter-based methods) perform best in terms of efficiency and accuracy.


## 📝 Notebooks Overview

### 1️⃣ Last Two Layers Fine-Tuning
- **Description:** Fine-tuning only the last two layers of mBERT to reduce computation while adapting to Nepali.
- **Key Features:** Partial parameter updates, faster training, lower GPU memory usage.
- **Link to Colab:** [Open in Colab](https://colab.research.google.com/drive/1hyHSGzVjzgfm9C9Nohr-9yhPTscdmuZS)

### 2️⃣ All Layers Fine-Tuning
- **Description:** Full fine-tuning of all mBERT parameters on Nepali text.
- **Key Features:** Highest model flexibility, longer training times, higher memory usage.
- **Link to Colab:** [Open in Colab](https://colab.research.google.com/drive/1N6XsmF8gCImKL6KKsgMFLrdGSARve_sJ)

### 3️⃣ Adapter-Based Fine-Tuning
- **Description:** Using adapter modules for parameter-efficient fine-tuning.
- **Key Features:** Small trainable parameters, modular adapters, competitive performance with less computation.
- **Link to Colab:** [Open in Colab](https://colab.research.google.com/drive/1uQBWz9KNq7dlr3Sb2N0hxvVmYhjxwNnt)

### 4️⃣ All Layers + Adapters
- **Description:** Combining full fine-tuning with adapter-based modules for maximum flexibility and performance.
- **Key Features:** Fine-tune all weights while leveraging adapters for parameter efficiency.
- **Link to Colab:** [Open in Colab](https://colab.research.google.com/drive/1m8Z8wj7HzEe_fzCtqDlk0BIYUC28OgbN)


