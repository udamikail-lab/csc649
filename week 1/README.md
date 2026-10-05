# CSC649 Setup: Sentence Counter

**Student:** Uda Mikail  
**Student ID:** 2024234664

This program asks for a sentence and displays its word count and character count. Character count includes spaces. If the input is empty or contains only spaces, it displays a helpful message.

## Requirements

- Python 3.12 (tested with Python 3.12.10)

## Run

Open the project in PyCharm and select the project's `.venv` interpreter, or run from a terminal:

```powershell
python main.py
```

Enter a sentence when prompted. The project environment can be created with:

```powershell
py -3.12 -m venv .venv
```

## Test results

- `Hello world` → 2 words, 11 characters (including the space)
- Empty input → `You did not enter a sentence.`
- `  Hello   world  ` → 2 words; character count includes all leading, repeated, and trailing spaces

## Limitation

The character count includes whitespace, so it does not report the number of letters alone.
