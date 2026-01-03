# 🎙️ Voice Gender Prediction: Statistical Voice Analysis
### Project Overview
This project focuses on identifying a speaker's gender (Male/Female) by analyzing acoustic properties and statistical voice features. The goal is to develop an efficient classification system that balances high accuracy with low computational complexity.

### 🔬 Feature Engineering & Analysis
The model utilizes a dataset consisting of 26 distinct acoustic features. These statistical measures extracted from voice signals include:

* **Fundamental Frequency:** Measures the mean, minimum, and maximum pitch of the voice.
* **Spectral Parameters:** Frequency quartiles, interquartile ranges, and spectral entropy.
* **Statistical Distributions:** Skewness and kurtosis of the voice signal.

### 🛠️ Methodology & Model Selection
To find the optimal balance between cost and complexity, four different classification algorithms were implemented and benchmarked:

* **Support Vector Machine (SVM-Kernel):** Tested for high-dimensional feature separation.

### 💻 Implementation (Google Colab)

* **💻 Colab NoteBooks (Support Vecotr Machine(SVM) Google Colab):** [SVM-Kernel](https://colab.research.google.com/drive/10fJcw7sVng6WV9bbqK_dRhBNoIsJu2O-?usp=sharing)

###  📊Dataset
* **📊 Dataset Source:** [Gender Recognition by Voice Dataset - Kaggle](https://www.kaggle.com/datasets/primaryobjects/voicegender)
* **Dataset Note:**  It contains information about whether a person's voice belongs to a man or a woman, using statistical data contained in the voice.csv dataset.
