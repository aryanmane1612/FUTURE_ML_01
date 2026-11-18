# Resume Screening & Ranking System

## Project Overview
This project uses Natural Language Processing (NLP) and Machine Learning techniques to automatically screen, score, and rank resumes based on a given job description.

It helps recruiters identify suitable candidates, compare skills, and find missing skills.

## Objectives
- Clean and preprocess resume text.
- Extract relevant skills using NLP techniques.
- Compare resumes with job descriptions.
- Calculate candidate matching scores.
- Rank candidates based on job relevance.
- Identify missing and matched skills.

## Technologies Used
- Python
- Pandas and NumPy
- NLTK
- spaCy
- Scikit-learn
- TF-IDF
- Cosine Similarity
- Matplotlib and Seaborn
- Jupyter Notebook

## Dataset
Resume Dataset from Kaggle:
https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset

The dataset contains 2,484 resumes across different job categories.

## Methodology
1. Dataset loading and exploration.
2. Resume text cleaning and preprocessing.
3. Skill extraction using keyword-based NLP.
4. Job description processing.
5. TF-IDF vectorization.
6. Cosine similarity calculation.
7. Skill matching and gap identification.
8. Candidate ranking and visualization.

## Scoring Method
The final candidate score is calculated using:

- 70% Resume and job description similarity.
- 30% Required skill matching.

Final Score = (0.70 × Similarity Score) + (0.30 × Skill Match Score)

## Output
- Complete candidate ranking.
- Top 10 candidates.
- Matched skills.
- Missing skills.
- Candidate ranking visualization.

## How to Run
1. Clone or download this repository.
2. Install dependencies using:

   pip install -r requirements.txt

3. Open the Jupyter Notebook.
4. Run all cells sequentially.
5. Enter or modify the job description to screen candidates.

## Conclusion
The Resume Screening and Ranking System demonstrates how NLP and Machine Learning techniques can support recruitment by automating resume analysis and candidate comparison.

The system is designed as a decision-support tool. Final recruitment decisions should always involve human evaluation.