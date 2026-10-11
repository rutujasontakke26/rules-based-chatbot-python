# Rule-Based Chatbot in python 🤖
It is a simple command-line chatbot built with Python using 'if-elif' logic. It was made as a mini project for my internship to practice conditional statements, loops, and string handling. No machine learning is used to make this.

## Features of the Chatbot
- Responds to greetings like hi, hello, hey
- Answers basic questions like "how are you" and "your name"
- Tells the current **time** and **date** using Python's 'datetime' module
- Handles uppercase, lowercase and extra spaces in input
- Replies with a fallback message when it doesn't understand
- Exits when user types 'bye' or exit'

## Sample Chat
```
Chatbot started! Type 'bye' to exit.

you: hi
Bot: Hello! Welcome.
you: what is your name?
Bot: Myself Bot!, nice to meet you
you: what time is it right now?
Bot: It's 08:28 PM.
you: and what date is it today?
Bot: Today is 11 October 2026.
you: okay, bye
Bot: Goodbye! See you next time.
```

## How to Run

1. Install Python 3 and Jupyter Notebook (or JupyterLab).
2. Download `rule-based-chatbot.ipynb` from this repository.
3. Open it in Jupyter and run the cell.
4. Type your messages next to the `you:` prompt.

## What I Learned

- How `while` loops keep a program running until the user exits
- How `if-elif-else` chains control a conversation
- Cleaning user input with `.lower()` and `.strip()`
- Why exact matching is fragile, and how keyword matching helps

## Limitations

The bot only understands the phrases I coded. It can't learn or handle sentences it hasn't been given rules for.

## Future Improvements

- Add more topics and replies
- Store rules in a dictionary to keep the code cleaner
- Remember the user's name during the chat
- Try an NLP library for smarter responses

## Tech Stack

Python 3, Jupyter Notebook

## Author

Made by Rutuja Sontakke
