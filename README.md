# Detecting-Fake-Social-Media-Profiles-Based-on-Visible-Features

**Introduction**

Social media platforms are increasingly being targeted by fake profiles. These profiles are often created to manipulate public opinion, spread spam, or scam users. Traditional manual methods of detecting such profiles are time-consuming and prone to errors. This project proposes an automated solution to detect fake social media profiles using machine learning algorithms.

**Objectives**

- **Analyze visible profile features**: Profile picture, username, bio, number of posts, followers, following, and engagement metrics.
- **Build a predictive model**: Use supervised learning techniques to classify profiles as real or fake.
- **Evaluate the model's performance**: Use appropriate metrics such as accuracy, precision, recall, and F1-score.

**Features**

The project focuses on extracting and utilizing the following visible features to detect fake social media profiles:

- **Profile Picture**: Absence, quality, or generic stock images.
- **Username**: Pattern analysis, such as the use of random strings or repeated characters.
- **Bio Description**: Length, keyword analysis, presence of URLs, or suspicious phrases.
- **Number of Friends/Followers**: Extremely high or low count, followers-to-following ratio.
- **Post Frequency**: Irregularities in posting patterns.
- **Engagement Metrics**: Average likes, comments, and shares per post.
- **Account Age**: Time since account creation.
- **Language and Content Analysis**: Use of language, common phrases in fake profiles, etc.

**Datasets**

To train and test the model, a dataset containing both fake and real social media profiles is required. The dataset can be obtained from:

- Publicly available datasets on Kaggle, GitHub, etc.
- Web scraping (ensure compliance with platform terms of service).
- Third-party data providers.

**Preprocessing**

Data preprocessing involves cleaning and transforming raw data to make it suitable for model training. The steps include:

1. **Handling Missing Values**: Impute or remove records with missing data.
1. **Encoding Categorical Data**: Convert categorical features (e.g., profile picture presence) into numerical format.
1. **Feature Engineering**: Create new features such as engagement rate and normalize/scale numerical features.
1. **Text Processing**: Use natural language processing (NLP) techniques for bio descriptions and content analysis, such as tokenization, stopword removal, stemming, and vectorization.
1. **Splitting Dataset**: Divide the dataset into training, validation, and test sets.

**Model Training**

This project utilizes a supervised learning approach to classify profiles. The following models are experimented with:

- **Logistic Regression**
- **Support Vector Machines (SVM)**
- **Random Forest Classifier**
- **Gradient Boosting Classifier**
- **Neural Networks (Deep Learning)**
