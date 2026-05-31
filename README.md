<div align="center">
  <img src="favicon.svg" width="90" height="90" alt="Tiao logo" />
  <h1>Tiao</h1>
  <p><strong>Mandarin learning, powered by the content you already watch.</strong></p>

  <a href="#">
    <img src="https://img.shields.io/badge/Try%20Tiao-Coming%20Soon-f97316?style=for-the-badge&logoColor=white" alt="Try Tiao" />
  </a>

  <br/><br/>

  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
</div>

---

Tiao turns any Chinese YouTube video into a personalized Mandarin flashcard deck. It extracts vocabulary, translates it, and schedules reviews using spaced repetition — skipping words you already know. Practice speaking with AI conversation scenarios, hear pronunciation on every card, and import existing Anki decks.

---

## Features

- **Video → Flashcards** — paste a YouTube URL and Tiao extracts and translates every vocab word from the transcript
- **Spaced Repetition (SRS)** — cards are scheduled at the optimal interval for long-term retention
- **Pronunciation** — Chinese is read aloud automatically when you flip a card
- **AI Scenarios** — practice real conversations based on video content or a custom topic
- **Smart Filtering** — skips words already in your deck and basic HSK vocabulary
- **Anki Import** — bring your existing decks with you

---

## Tech Stack

| Layer | Technology |
|---|---|
| Backend | FastAPI, SQLAlchemy, Celery, PostgreSQL |
| Frontend | React, Vite |
| NLP | Jieba, pypinyin, deep-translator |
| Auth | JWT |

---

<div align="center">
  <sub>© 2026 Jonathan Dool. All rights reserved.</sub>
</div>
# tiao_public
