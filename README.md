# Python-Projects

# Flash Card – Pandas Cleaning + Tkinter UI

A small desktop app that demonstrates **data cleaning/formatting in pandas** wrapped in a **Tkinter UI**.  
It loads `data/french_words.csv`, cleans/normalizes text, and writes progress to `data/words_to_learn.csv`.  
Buttons (✔/✖) mark known words; a timer flips the card to show the translation.

## Quick Start
```bash
python3 -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt  # or: pip install pandas pillow
python main.py
