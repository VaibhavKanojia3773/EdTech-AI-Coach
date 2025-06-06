# AI-Powered Student Performance Feedback System

## Objective
Build an AI-driven system that:  
- Analyzes test data (JSON).  
- Generates personalized, motivating, and insightful feedback using LLM APIs (OpenAI/Gemini/Claude).  
- Creates a styled, human-readable PDF report.  
- Demonstrates prompt engineering, data interpretation, and automation skills.

## Tech Stack
- Python 3.x  
- Streamlit (UI)  
- Matplotlib (charts)  
- Gemini API (LLM)  
- PDF generation libraries (ReportLab/FPDF)  
- JSON parsing

## Features
- Parses JSON data, extracting subject- and chapter-level accuracy, time, and difficulty.  
- Generates AI feedback with:  
  - Personalized intro  
  - Performance breakdown  
  - Time vs Accuracy insights (forced to avoid “N/A”)  
  - Actionable suggestions  
- Displays charts in Streamlit UI.  
- Generates downloadable PDF reports with all feedback and visuals.

## Prompt Engineering
- Uses structured prompts with examples to ensure human-like, personalized, and motivating feedback.  
- Emphasizes avoiding empty insights by forcing time-vs-accuracy analysis.

## Running the App
1. Install dependencies: `pip install -r requirements.txt`  
2. Set API keys for LLM access in 'generate_feedback.py'  
3. Run: `streamlit run app.py`  
4. Upload/select JSON test data and generate feedback.  
5. View AI feedback, charts, and download PDF report.

---


Thank you!
