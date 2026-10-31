# AI-Task6: E-Commerce Order Validator (Pydantic v2)

JSON orders ko Pydantic se validate karna, saari ghaltiyan jama karna (crash nahi), sahi orders `model_dump_json()` se save karna aur ghalat orders ki report banana.

- **File:** `AI_Task6_Order_Validator.ipynb` (Google Colab notebook), `requirements.txt`

## Google Colab mein chalana
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaweriamushtaq41-coder/Smart_District_2/blob/main/AI-Task6/AI_Task6_Order_Validator.ipynb)

1. `AI_Task6_Order_Validator.ipynb` Colab mein kholo (upar button, repo GitHub par push hone ke baad). Ya colab.research.google.com par *Upload* karo.
2. Is task ko key ki zaroorat nahi.
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
Phir `AI_Task6_Order_Validator.ipynb` kholo. (Mac / Linux par: `source venv/bin/activate`.)

## Dhyan do
- Is task ko API key ya internet nahi chahiye.
- `.env` GitHub par push nahi hoti, sirf `.env.example` hoti hai.
