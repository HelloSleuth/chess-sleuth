# ♔♕♖♗♘♙ chess-sleuth ♚♛♜♝♞♟︎
ChatGPT vs. Stockfish in the chess bot battle of the century from the folks at [Sleuth](https://hellosleuth.com/)!

|   | a | b | c | d | e | f | g | h |
|---|---|---|---|---|---|---|---|---|
| 8 | ♜ | ♞ | ♝ | ♛ | ♚ | ♝ | ♞ | ♜ |
| 7 | ♟ | ♟ | ♟ | ♟ | ♟ | ♟ | ♟ | ♟ |
| 6 |   |   |   |   |   |   |   |   |
| 5 |   |   |   |   |   |   |   |   |
| 4 |   |   |   |   |   |   |   |   |
| 3 |   |   |   |   |   |   |   |   |
| 2 | ♙ | ♙ | ♙ | ♙ | ♙ | ♙ | ♙ | ♙ |
| 1 | ♖ | ♘ | ♗ | ♕ | ♔ | ♗ | ♘ | ♖ |

(ChatGPT drew that chess board!!)

## Requirements
* An [OpenAI account](https://platform.openai.com/signup?launch)
* An [OpenAI API Key](https://platform.openai.com/account/api-keys)
* Python 3.10 (probably works with other versions but we haven't tested it)
* [Homebrew](https://brew.sh/) (assuming you are on a Mac)

## Setup
1. Clone this repository
2. `cd chess-sleuth`
3. Make a local Python virtual environment `python3.10 -m venv venv`
4. If you're using an IDE like DataSpell or PyCharm be sure to update your Project's Python interpreter to the local venv.
5. Activate the Python virtual environment `source venv/bin/activate`
6. Install Required Python Modules `pip install -r requirements.txt`
7. Install the Stockfish engine (on Mac) `brew install stockfish`
8. Make a file called `.env` in the chess-sleuth directory with:
```
OPENAI_API_KEY=sk-whateverYourBigLongKeyIs
```

## Running
1. Open chess_sleuth.ipynb. 
2. Set the correct path to the Stockfish engine in place of "stockfish" for path_to_stockfish. This is something like: "/opt/homebrew/Cellar/stockfish/15.1/bin/stockfish" if you used `brew install stockfish`.
4. Run the notebook!
