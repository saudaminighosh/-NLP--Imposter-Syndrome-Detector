Imposter Syndrome Detector
A machine learning and NLP-based project that analyzes Reddit posts to identify text patterns associated with **imposter syndrome**. The project uses Reddit data collection, natural language processing, TF-IDF feature extraction, and a Scikit-learn classification model.

Project Overview:
The goal of this project is to explore whether machine learning can identify linguistic patterns associated with imposter syndrome from user-generated Reddit content.


Technologies Used:
* **Python**
* **Reddit API / PRAW**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **TF-IDF**
* **Natural Language Processing (NLP)**
* **Matplotlib**

Key Features :

* Collected user-generated Reddit posts using the **Reddit API**.
* Processed and prepared textual data for machine learning.
* Applied **TF-IDF (Term Frequency–Inverse Document Frequency)** for text feature extraction.
* Developed a **Scikit-learn classification model** to classify text based on imposter-syndrome-related patterns.
* Evaluated the classification performance and achieved approximately **95% classification accuracy** on the available dataset.

Workflow :

### 1. Data Collection

Reddit posts are collected using the Reddit API and prepared for further processing.

### 2. Text Preprocessing

The collected text is cleaned and transformed into a format suitable for NLP analysis.

### 3. Feature Extraction

TF-IDF is used to convert textual information into numerical feature vectors.

### 4. Model Training

A supervised machine learning classifier from Scikit-learn is trained using the extracted text features.

### 5. Evaluation

The trained model is evaluated using classification performance metrics, achieving approximately **95% accuracy** on the available dataset.

Results :

The classification model achieved approximately:

**Accuracy: 95%**


Installation:

Clone the repository:
git clone https://github.com/saudaminighosh/-NLP--Imposter-Syndrome-Detector.git
cd -NLP--Imposter-Syndrome-Detector

Install the required Python packages:
pip install pandas numpy scikit-learn praw matplotlib

Usage:
Run the main Python script:
python Imposter_syndrome_detector_Basic.py

If the project uses Reddit API credentials, configure the required Reddit API credentials before running the data collection component.

Author:
**Saudamini Ghosh**

* GitHub: https://github.com/saudaminighosh
* LinkedIn: https://linkedin.com/in/saudaminighosh
