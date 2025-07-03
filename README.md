# genAI-proj

1. Introduction
The Hotel Review Sentiment Analyzer project is a Gen AI-based solution to analyze customer feedback collected from hotel guests. The model extracts sentiments related to specific aspects such as food quality, room service, cleanliness, etc., to help hotels improve service quality. It uses multi-label classification with Foundation Models to tag sentiments for multiple service aspects in a single review.
2. Objective
- Classify each hotel review into multiple aspects and sentiments (positive/negative).
- Provide summarized feedback for hotel service teams.
- Identify specific strengths and pain points in hotel services.
3. Tools & Technologies Used
- Foundation Models (facebook/bart-large-mnli)
- Excel – for input and output files
- Google Colab / Jupyter Notebook
- Hugging Face Transformers
- Python Libraries: pandas, sklearn, spacy
4. Methodology / Working
Step-by-step workflow:
1. Data Collection: 1000 Hotel reviews in CSV format with raw text generated using AI (Chat GPT)
2. Prompt Engineering: Applied zero-shot multi-label classification prompts.
3. Sentiment & Aspect Extraction: Model extracts aspect (e.g., room, food) and its sentiment.
4. Output Formatting: Results exported into CSV with labeled aspects and sentiments.
