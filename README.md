# Movie Recommendation System

A content-based filtering system that recommends movies based on 
user input, deployed as a live web app on Hugging Face Spaces.

## Business Problem
Streaming platforms lose users when discovery fails. 
This system improves content discoverability using similarity matching.

## Tools Used
- Python (pandas, scikit-learn)
- Streamlit
- Hugging Face Spaces (deployment)

## How It Works
1. User enters a movie name
2. System computes cosine similarity across movie metadata
3. Returns top 5 similar movies instantly

## Live Demo
(https://huggingface.co/spaces/Rahul9971/Streamlit-app)
## How to Run Locally
pip install -r requirements.txt
streamlit run app.py
