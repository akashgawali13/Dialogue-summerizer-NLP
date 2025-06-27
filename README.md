# Dialogue-summerizer-NLP
Automatically summarize multi-turn conversations into bullet points, action items, and entities

# Features
- Multi-speaker conversation summarization
- Speaker attribution preserved
- Configurable summary length
- Action item extraction
- Named entity recognition
- Redundancy removal
- Export to PDF/Markdown
- Streamlit-based Web UI

# Models Used
- `facebook/bart-large-cnn` for summarization
- `all-MiniLM-L6-v2` for semantic similarity
- `spaCy en_core_web_sm` for NER

# Setup Instructions
```bash
pip install -r requirements.txt
python -m nltk.downloader punkt
python -m spacy download en_core_web_sm
streamlit run app.py
