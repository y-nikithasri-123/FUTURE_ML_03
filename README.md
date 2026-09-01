# Resume / Candidate Screening System

## Internship

Future Interns - Machine Learning Internship

## Objective

The objective of this project is to build a machine learning based resume screening system that compares candidate resumes with a given job description.

## Project Overview

The system performs:

- Resume text preprocessing
- Resume text cleaning
- Job description processing
- Skill extraction
- Required skill matching
- Resume-to-job similarity scoring
- Candidate scoring
- Candidate ranking
- Missing skill identification
- Business insights

## Methodology

The project uses TF-IDF vectorization to convert resume and job description text into numerical features.

Cosine similarity is then used to calculate the similarity between each resume and the job description.

A final candidate score is calculated using skill matching and similarity scoring.

## Candidate Ranking

Candidates are ranked according to their overall fit for the selected Machine Learning Engineer role.

## Skill Gap Analysis

The system identifies required skills that are missing from each candidate's resume.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- TF-IDF
- Cosine Similarity
- Google Colab

## Key Features

### Resume Processing
Cleans and prepares resume text for analysis.

### Skill Extraction
Identifies required skills present in candidate resumes.

### Similarity Scoring
Measures the similarity between a resume and the job description.

### Candidate Ranking
Ranks candidates based on their overall job-role fit.

### Skill Gap Identification
Highlights required skills that are missing from each candidate's resume.

## Business Benefits

The system can help recruiters reduce the time required for initial resume screening and compare candidates using a consistent scoring approach.

It can also help identify candidate strengths and skill gaps.

## Important Note

This system is intended to support the recruitment screening process. Final hiring decisions should involve human review and evaluation of candidate qualifications and experience.

## Files

- `Resume_Candidate_Screening.ipynb` - Complete Google Colab notebook containing the implementation, candidate scoring, ranking and skill-gap analysis.
