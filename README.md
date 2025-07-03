# -AI-Powered-Resume-Matching-Job-Recommendation-System
AI-powered platform that intelligently matches candidate resumes to job roles based on skills, experience, and relevance.
# Career Navigator: AI-Driven Job Application Assistant

Career Navigator is an AI-based system designed to streamline the job application process by automating resume screening and providing personalized job recommendations. This project leverages machine learning and natural language processing (NLP) to intelligently match candidates to the most relevant job categories.

## Overview

The system uses two resume datasets to improve classification accuracy and ensure broader applicability. It analyzes resumes, compares them with job descriptions, and recommends the top job categories using a combination of NLP, machine learning models, and similarity metrics.

## Key Features

- Automated resume categorization using NLP and text classification
- Job recommendation engine based on cosine similarity
- Resume–job description match score for application alignment

## Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn, TensorFlow, Keras  
- NLTK  
  

## Workflow

1. **Data Collection & Cleaning**  
   - Used two datasets: one with 962 entries and one with 29,003 entries  
   - Applied NLP preprocessing: tokenization, stopword removal, lemmatization

2. **Feature Engineering**  
   - Used TF-IDF vectorization to convert text into numerical format

3. **Model Development**  
   - Trained both a Recurrent Neural Network (RNN) and Multinomial Naive Bayes (MNB)  
   - Optimized parameters for accuracy and scalability

4. **Evaluation**  
   - Tested models on holdout data for classification accuracy

5. **Job Recommendation**  
   - Implemented cosine similarity to suggest the top five most suitable job categories

6. **Deployment**  
   - Serialized trained models using Pickle for fast inference

## Future Improvements

- Integration with real-time job listings via APIs  
- Support for multilingual resumes  
- Streamlit-based user interface for interactive usage  
- Feedback-driven improvement based on real-world usage
