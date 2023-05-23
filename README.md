# chess-sleuth
ChatGPT vs. Stockfish in the chess bot battle of the century.

## Requirements
* An OpenAI API Key
* Python 3.10 (may work with other version, but untested)

## Setup
1. Install local Python environment `python3.10 -m venv venv`
2. If you're using an IDE like DataSpell or PyCharm be sure to update your Project's Python interpreter to the local venv.
3. Activate the local Python environment `source venv/bin/activate`
4. Install Required Python Modules `pip install -r requirements.txt`
5. Install the Stockfish engine (on Mac) `brew install stockfish`
6. Make a file called `.env` in the chess-sleuth directory with:
```
OPENAI_API_KEY=sk-whateverYourBigLongKeyIs
```

## Running
Open chess_sleuth.ipynb in Jupyter and run it!
