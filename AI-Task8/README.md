# AI-Task8: Research Report Generator (LCEL)

Topic -> key-facts aur counterarguments `RunnableParallel` se ek saath -> `RunnableLambda` se jodna -> final prompt jo balanced report likhta hai -> `.txt` file.

- **File:** `AI_Task8_Research_Report_Generator.ipynb` (Google Colab notebook), `requirements.txt`, `.env.example`

## Google Colab mein chalana
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaweriamushtaq41-coder/Smart_District_2/blob/main/AI-Task8/AI_Task8_Research_Report_Generator.ipynb)

1. `AI_Task8_Research_Report_Generator.ipynb` Colab mein kholo (upar button, repo GitHub par push hone ke baad). Ya colab.research.google.com par *Upload* karo.
2. Keys ho to Colab ke left side ke **Secrets** (chaabi ka icon) mein daalo: `GROQ_API_KEY`, `OPENAI_API_KEY`, `ANTHROPIC_API_KEY`, `GOOGLE_API_KEY` (jo hon), **Notebook access** ON. Ya apni `.env` file **Files** panel mein drag-drop kar do. Key na ho to demo mode chalta hai.
3. *Runtime > Run all*.
4. Notebook mein saved output demo mode ka hai. Asli key se dobara chalao to output asli ho jayega.

## Apne computer par (Jupyter)
```
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
pip install notebook
jupyter notebook
```
Phir `AI_Task8_Research_Report_Generator.ipynb` kholo. (Mac / Linux par: `source venv/bin/activate`.)

## Dhyan do
- Notebook ke markdown cells mein har step samjhaya gaya hai.
- `.env` GitHub par push nahi hoti, sirf `.env.example` hoti hai.
