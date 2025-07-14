# 🧑‍💻🧠 Mindle – Word Puzzle AI Bot

A smart clone of Wordle built in Python — with a twist: it comes with an **AI bot that plays and solves the game** using intelligent guessing algorithms.  
Designed to demonstrate skills in **algorithmic thinking, data structures, AI reasoning, and interactive UI logic**.

---

## 🎯 Project Purpose

> “From guessing to reasoning — Mindle bridges logic and automation in a fun way.”

Built as part of a personal journey to master Python, algorithm design, and functional problem solving.

---

## 🚀 Features

- 🧠 **AI Solver**: Smart bot that guesses the word with logic (frequency + position elimination).
- 🕹️ **Play Mode**: Human user plays a daily or random puzzle.
- 🤖 **AI Mode**: Watch the bot think and solve the game.
- 🎨 **Terminal-based UI** with colored feedback (or Pygame/Tkinter optional).
- 🌍 **Multilingual Word Support**: English, French, Arabic, etc.
- 📈 **Performance Stats**: Attempts, time, AI efficiency score.
- 🔐 **Daily Challenge Mode** with encoded word-of-the-day.

---

## 🧠 AI Guessing Logic

```python
# Simplified version
guess = get_best_candidate(word_list)
feedback = evaluate_guess(guess, secret_word)
word_list = eliminate_impossible_words(word_list, guess, feedback)

> The bot uses elimination + letter frequency ranking to narrow down its guesses like a real player
```

---

## 🧩 File Structure
```
Mindle/
├── data/
│   └── word_lists/           # Dictionaries for multiple languages
├── src/
│   ├── game.py               # Main game loop
│   ├── ai_solver.py          # AI algorithm logic
│   ├── feedback.py           # Letter position/color logic
│   ├── ui_terminal.py        # Terminal interface (colors, layout)
│   ├── stats.py              # Track and display game stats
│   └── utils.py              # Helpers and common functions
├── daily_mode.py             # Daily encrypted word challenge
├── requirements.txt
└── README.md
```

---


## 🧪 Sample Output

```
MINDLE - Smart Word Puzzle 🎯
Try #1:  SLATE →  ⬛ 🟨 🟩 ⬛ ⬛
Try #2:  TRUCK →  ⬛ 🟩 ⬛ 🟩 ⬛
Try #3:  TRACK →  🟩 🟩 🟩 🟩 🟩 🎉 Solved!
```


---

## 🔧 Tech Stack

Tool	Use

Python	Core language
Pandas	Word list filtering (optional)
colorama	Terminal color feedback
hashlib	Daily word encoding
matplotlib	AI stats graphs (optional)



---

## 🏁 Roadmap

[x] AI solver with elimination logic

[x] Manual play mode

[x] Word list loading and filtering

[x] Feedback color evaluation

[ ] Daily challenge logic

[ ] GUI (Tkinter or Pygame)

[ ] Leaderboard with saveable scores



---

## 👨‍💻 Author

Ayman Bouaziz
🎓 AI & Software Engineering Student – FSTH (Al Hoceima)
🔗 LinkedIn: https://www.linkedin.com/in/ayman-bouaziz-7ab181349

📧 projects.aymanbouaziz@gmail.com


---

## 📜 License

MIT License – For educational and demo use only.
© 2025 Ayman Bouaziz


---

## 💬 Final Thought

> “Mindle is not just a Wordle clone — it’s a personal algorithmic playground where logic becomes intelligent gameplay.”
