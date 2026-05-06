# AI Video Transcription and Nutrition Summarizer

An end-to-end AI pipeline that searches YouTube, downloads audio, transcribes speech with Whisper, and summarizes diabetes-friendly cooking content with an LLM.

## Why this project matters
This repository demonstrates practical Generative AI engineering skills that recruiters can review quickly: model integration, agent workflows, prompt engineering, data preprocessing, tool use, and reproducible notebook-based experimentation.

## Skills shown
- YouTube search and audio extraction with yt-dlp
- Speech-to-text transcription with OpenAI Whisper
- Prompt engineering for structured nutrition summaries
- LangChain + OpenAI chat model integration
- End-to-end multimedia AI workflow development

## Project structure
```text
.
├── notebooks/
│   └── ai_video_transcription_and_nutrition_summarizer.ipynb
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

## Setup
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

```
## How to run
1. Open the notebook in Jupyter, VS Code, or Google Colab.
2. Install dependencies from `requirements.txt`.
3. Add required API keys as environment variables, never directly inside the notebook.
4. Run cells from top to bottom.

