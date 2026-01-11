# SpeechActNLI

###
Name  : 
        Awol          
        Tsion Bizuayehu  GSR/9235/17
A two-stage pragmatic analysis pipeline:
1. Speech Act Classification (statement, question, directive)
2. Natural Language Inference (ENTAILMENT, CONTRADICTION, NEUTRAL)

## Structure
- `src/` : source code modules
- `data/` : datasets (Switchboard subset, KB facts)
- `notebooks/` : Jupyter experiments
- `tests/` : unit tests

## Setup
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
