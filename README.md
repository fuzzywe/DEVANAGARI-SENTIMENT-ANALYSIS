Certainly! Here’s the modified format that looks more streamlined and professional:

---

# **Devanagari-Sentiment-Analysis**

The **Devanagari script** is an ancient writing system that originated in India and is used for many languages in South Asia, including **Hindi**, **Sanskrit**, **Marathi**, and **Nepali**. It is an **abugida**, which means it is based on syllables, with each letter representing a consonant-vowel combination. Key characteristics of Devanagari include:

1. **Structure**: Each character has a top horizontal line, called the "Shirorekha" (शीर्षरेखा), that connects letters in a word. This line is a distinctive feature of Devanagari and helps identify words.
   
2. **Consonants and Vowels**: The script contains separate letters for consonants and vowels. Vowels can be written as independent letters or as diacritic marks attached to consonants.

3. **Diacritical Marks**: These marks are used to change the inherent "a" sound of a consonant. For example, the consonant "क" is pronounced as "ka" by default, but when a diacritical mark for "i" is added, it changes to "कि" ("ki").

4. **Complex Ligatures**: Certain consonant combinations form **ligatures** or compound letters, creating a unique character rather than two separate letters. For example, "क" (ka) and "ष" (sha) combine into the ligature "क्ष" (ksha).

5. **Nasalization and Aspiration**: Marks are used for nasal sounds, such as the "anusvara" (ं) and the "candrabindu" (ँ), as well as aspirated sounds.

### Example
Here's how the word "नमस्ते" ("Namaste") looks in Devanagari. Each character is carefully crafted to represent the phonetic aspects of the syllables in the word.

Devanagari script has deep historical roots and continues to be a primary script for major Indian languages, preserving linguistic heritage and connecting modern languages to classical texts.

"Devanagari Sentiment Analysis" is a project dedicated to analyzing sentiments in text data written in the Devanagari script, which is widely used for languages like Hindi, Marathi, Punjabi, and Gujarati. This project includes tools for:
- Preprocessing Devanagari text
- Training machine learning models for sentiment classification
- Visualizing sentiment distributions through word clouds and sentiment scores  

The analysis provides insights into the emotional content of Devanagari text, aiding in understanding public opinion, sentiment trends, and user feedback in Devanagari languages.

## **Overview**
The Devanagari Sentiment Analysis project encompasses essential components for sentiment analysis, including:
- Data preprocessing
- Feature engineering
- Model training and evaluation
- Sentiment visualization

## **Description**
This project focuses on developing machine learning models that classify text in Devanagari languages (e.g., Hindi, Marathi, Punjabi, Gujarati) into positive, negative, or neutral sentiments.

## **Dataset Source**
Datasets are curated from various sources such as social media, news articles, and online platforms. These datasets are preprocessed and labeled specifically for sentiment analysis tasks.

## **Project Approach**
The sentiment analysis is approached as a supervised learning problem. Machine learning algorithms, particularly **Random Forest**, are employed to train models on preprocessed text data to predict sentiment labels. Essential preprocessing steps, such as tokenization, stemming, and vectorization, convert raw text into numerical features fit for model training.

## **Why Random Forest?**
1. **Robustness**: It performs well across diverse datasets without excessive hyperparameter tuning, handling various languages effectively.
2. **Ensemble Learning**: Combines multiple decision trees, capturing complex relationships and improving predictive accuracy.
3. **Feature Importance**: Provides insights into which features influence sentiment prediction, aiding in feature selection.
4. **Handling Imbalanced Data**: Effectively manages skewed distributions in sentiment labels.
5. **Scalability**: Efficiently handles large datasets, making it ideal for scaling up analysis on larger text corpora.

## **Evaluation**
The model performance is assessed through standard evaluation metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**

Confusion matrices and classification reports are also generated for detailed analysis across sentiment categories.

## **Visualization**
Word clouds and other visualization tools highlight common words and sentiment trends in the data, offering a deeper understanding of both the dataset and model behavior.

## **Features**
- Preprocessing of Devanagari text data
- TF-IDF vectorization for feature extraction
- Training and evaluation of machine learning models
- Visualization of evaluation metrics and sentiment analysis results

## **Datasets**
- Hindi Sentiment Analysis Dataset
- Punjabi Sentiment Lexicon
- Gujarati Sentiment Analysis Dataset
- Marathi Sentiment Analysis Dataset

## **Installation**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/devanagari-sentiment-analysis.git
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## **Usage**
1. Explore the notebooks in the `notebooks` directory for comprehensive analysis and execution.
2. Execute scripts in the `scripts` directory for tasks like data preprocessing, model training, and evaluation.
3. Customize the code to apply to your specific datasets or to experiment with different model architectures.

## **Contributors**
- ruthika
- janani



--- 

This format makes the document easy to navigate and covers all the key points concisely.
