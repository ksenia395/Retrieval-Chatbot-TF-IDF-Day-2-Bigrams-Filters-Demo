
# Retrieval Chatbot (Cornell Movie Dialogs) — 2-day build

A simple retrieval-based chatbot built in 2 days.
It finds the most similar line in a movie-dialog corpus (TF‑IDF + cosine similarity)
and returns the paired reply.

## Day 1 (Baseline)
- Build (query → reply) pairs
- TF‑IDF (unigrams) over queries
- Return reply of the closest match

## Day 2 (Improvements)
- Word n-grams (1,2) to capture common phrases
- Top‑K retrieval + response filters:
  - length constraints
  - stop-reply blacklist
  - similarity threshold + fallback
- Demo: 5–10 scripted conversations

## Demo
(Insert output screenshots or paste a few short dialogues here.)

## Limitations
- Retrieval only (no generation)
- Weak multi-turn consistency
- Corpus contains noisy / mature language

## Dataset
This repo contains code only. Dataset is provided separately via Kaggle:
- cornell-movie-dialogs-corpus (formatted_movie_lines.txt)

## License
MIT (code). Dataset license/terms belong to dataset authors/providers.

The full implementation and experiments are available on Kaggle:

👉 View the Kaggle Notebook
https://www.kaggle.com/code/ksenia395/retrieval-chatbot-tf-idf-day-2-bigrams-fil/
