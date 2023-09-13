# **:NLP-powered Ham/Spam Message Detection:**
Using advanced methods in Natural Language Processing (NLP), created a strong model that can accurately tell apart spam and ham messages. The dataset has two main parts: one is "Target," which is marked as Ham (1) and Spam (0), and the other is the "Message" part of the text.

### NLP:
NLP stands for Natural Language Processing, which is a part of Computer Science, Human language, and Artificial Intelligence. It is the technology that is used by machines to understand, analyze, manipulate, and interpret human language.

<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/NLP-Project/assets/112754746/86798e87-6af9-4786-ada7-7c0df1ab59a9"  height="350" width="800"/>
</div>

### Spam:
Spam is any kind of unwanted, unsolicited digital communication that gets sent out in bulk. Often spam is sent via email, but it can also be distributed via text messages, phone calls, or social media.

### Ham:
Ham email refers to an email that is wanted by the recipient and is not considered spam.

<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/NLP-Project/assets/112754746/97add112-77fb-427c-b420-fa80ea8468f5"  height="350" width="800"/>
</div>

##  <img src="https://github.com/yasmeenustad/Placements-Data-Analysis-Excel-Project/assets/112754746/030e1f21-e04f-4cbd-b301-3576c8c1acc3"  width="48" height="48"> Aim:
Aim of the project is to utilize advanced Natural Language Processing (NLP) techniques to effectively distinguish between "Ham" messages and "Spam" messages. The core goal is to engineer high-accuracy models for this classification task, thereby elevating communication security and quality through data-driven NLP methodologies.

## Python Libraries Used:
- **Pandas** simplifies data manipulation with versatile structures like DataFrames, essential for tasks from loading to preprocessing in data analysis.

- **Seaborn, Matplotlib** visualization libraries empower users to create insightful plots, enhancing data exploration.

- **Sklearn** provides a comprehensive toolkit for building and evaluating machine learning models.

##  <img src="https://github.com/yasmeenustad/Placements-Data-Analysis-Excel-Project/assets/112754746/057551de-877a-4a41-916c-d47e81053404"  width="48" height="48"> Objectives:

- **Data Preprocessing:-**
    - Prepare the dataset for analysis by cleaning and organizing the data.
      
- **Data Cleaning:-**
    - Remove irrelevant or noisy data, such as HTML tags, special characters, and punctuation marks.
      
- **Stopword Removal:-**
    - Eliminate common words that do not contribute much to the meaning of the text (e.g., "the," "is," "and").
      
- **Word Stemming:-**
    - Reduce words to their base or root form to remove variations (e.g., "running" to "run," "walked" to "walk").
      
- **Lemmatization:-**
    - Transform words to their canonical form (lemma) to maintain the context and meaning of the words accurately.
      
- **Count vectorization:-**
    - Transforming text documents into numerical representation based on word occurrence frequencies

## Exploring Model Diversity:
- **Logistic Regression:**
    - Logistic regression is a statistical model used for binary classification tasks. It predicts the probability that an input belongs to one of two possible classes. It's simple, interpretable, and widely used in 
        various fields.

- **Decision Tree Classifier:**
    - A decision tree is a tree-like structure used for classification and regression tasks. It recursively splits data based on features to make decisions. It's intuitive, interpretable, and can handle both categorical         and numerical data.

- **Random Forest Classifier:**
    - Random Forest Classifier: A random forest classifier is an ensemble learning method that combines multiple decision trees to improve predictive accuracy and reduce overfitting. It's robust, handles complex data,           and is effective in various machine learning applications.
      
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/NLP-Project/assets/112754746/4f91ca9d-040b-422a-ad49-9d1c843836dc"  height="350" width="800"/>
</div>

### Model Accuracy Achieved:
**1. Logistic Regression Model (98%)**
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/NLP-Project/assets/112754746/6fe3ef0a-e181-4a63-9684-22831a3efe1b"  height="400" width="500"/>
</div>

**3. Decision Tree Classifier Model (95%)**
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/NLP-Project/assets/112754746/3ddeb83f-2499-4076-a138-1c2e749e085c"  height="400" width="500"/>
</div>

**4. Random Forest Classifier Model (97%)**
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/NLP-Project/assets/112754746/ec985854-6eb4-4605-9967-c5cec64ccc31"  height="400" width="500"/>
</div>

## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/603ad77e-2212-4b07-a75a-ffcabb0538f4" width="70" height="50"> Challenges:

- **Data Quality and Noise Reduction:**
    - Cleaning and organizing the data can be challenging, particularly when dealing with large datasets. Ensuring data quality by identifying and removing irrelevant or noisy data, such as HTML tags and special 
      characters, requires careful inspection and sometimes complex text processing algorithms.

- **Stopword Removal Accuracy:**
    - While removing stopwords can improve the efficiency of text analysis, the challenge lies in determining which words to consider as stopwords for a specific analysis. Choosing an appropriate list of stopwords and 
      avoiding the unintentional removal of contextually important words can be tricky.

- **Word Stemming and Lemmatization Precision:**
    - Word stemming and lemmatization are essential for text normalization, but they may not always provide accurate results. Deciding between stemming and lemmatization and ensuring that the transformed words maintain 
      their intended meaning and context can be challenging, especially in languages with complex inflections and variations.

## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/2e256cec-1421-4c5f-9913-052a53dc470f" width="70" height="50"> Learnings:

- **Data Preparation and Cleaning:**
    - Effective NLP and ML projects start with thorough data preparation. Cleaning and preprocessing text data, handling missing values, and addressing imbalances are crucial steps to ensure data quality and model              performance.

- **NLP Libraries and Tools:**
    - Proficiency in popular NLP libraries like NLTK, spaCy, or TensorFlow for deep learning models is essential. Familiarity with tools like scikit-learn for ML pipelines is also valuable.

- **Model Selection and Tuning:** 
    - Careful selection of appropriate NLP and ML algorithms is fundamental. Learning how to choose the right model architecture and optimizing hyperparameters through techniques like grid search or random search can 
      enhance model performance.

