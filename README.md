# Masar – AI Career Path Recommendation System

An AI-powered career guidance system that helps students discover the most suitable technology career paths based on their skills, quiz responses, or uploaded resumes.

The system uses Natural Language Processing (NLP) and Machine Learning models to analyze user profiles and recommend the top three matching tech fields along with personalized insights and certification suggestions.

---

## Project Overview

Choosing the right technology career path can be difficult due to the large number of specializations such as:

- Artificial Intelligence
- Cybersecurity
- Data Science
- Cloud Computing
- UX/UI Design
- Software Engineering

Masar addresses this challenge by providing intelligent and personalized career recommendations using AI techniques and machine learning classification models.

---

## Features

- AI-powered career path recommendations
- Resume upload and analysis
- Quiz-based skill assessment
- Top 3 recommended career paths with matching scores
- NLP-based skill extraction
- Certification recommendations
- Interactive and user-friendly interface
- Multiple ML model comparison and evaluation

---

## Technologies Used

### Frontend
- React
- Tailwind CSS

### Backend
- Python
- FastAPI

### Machine Learning & NLP
- Scikit-learn
- XGBoost
- LightGBM
- Sentence-BERT
- TF-IDF
- MultiLabelBinarizer

### Models Used
- Decision Tree
- Random Forest
- XGBoost
- SVM
- LightGBM
- Ensemble Voting Classifier

---

## Dataset

The project uses the following dataset from Kaggle:

**Career Path Dataset for Advanced Tech Jobs**

Dataset Link:  
https://www.kaggle.com/datasets/solimanbarakat/career-path-dataset-for-advanced-tech-jobs

The dataset was enriched with professional certifications from:
- AWS
- Microsoft
- Google
- Cisco
- CompTIA

---

## System Workflow

1. Data preprocessing and cleaning
2. NLP feature extraction
3. Feature engineering
4. Model training and evaluation
5. Resume/quiz processing
6. Career recommendation generation

---

## Machine Learning Pipeline

- Text Cleaning & Normalization
- TF-IDF Vectorization
- Sentence-BERT Embeddings
- MultiLabel Encoding
- RandomOverSampler
- Cross Validation
- Ensemble Soft Voting

---

## Model Performance

| Model | Test Accuracy |
|------|------|
| Decision Tree | 97.62% |
| Random Forest | 98.98% |
| XGBoost | 99.15% |
| LightGBM | 98.81% |
| SVM | **99.32%** |
| Ensemble | 99.15% |

The SVM model achieved the highest overall accuracy and was selected as the final production model.

---

## User Interface

The system provides two input methods:

### 1. Quiz-Based Recommendation
Users answer a set of skill-based questions to receive personalized recommendations.

### 2. Resume Upload
Users can upload their resume in PDF format, and the system extracts:
- Skills
- Tools
- Certifications
- Educational background

Then predicts the most suitable career paths.

---

# Demo Video

Add your demo video here:

[Watch Demo Video](

https://github.com/user-attachments/assets/6ef18656-3207-4a14-a070-fe6b925c48b6

)

Code Reference: 
https://drive.google.com/file/d/1NG7ppyk8kODtyEYvREd5j15Y-ULNveUx/view?usp=drive_link


Future Improvements

Adaptive quiz system
Real-time learning roadmaps
Larger datasets integration
Internship/job recommendation support
Arabic language support
Improved explainability for predictions


License

This project was developed as part of the Samsung Innovation Campus AI Course Capstone Project.

© 2025 Group-9: Masar
