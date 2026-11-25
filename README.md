# Bangla Flashcard Maker

A warm, paper-and-ink flashcard study app — make decks, flip cards, and keep
practising the ones you don't know yet. Everything is saved in your browser
(localStorage); no account, no server.

## What it does

- **Decks** — create, rename and delete decks; each deck has its own cards.
- **Cards** — front + back, Bangla or English. Add, edit and delete individual cards.
- **Study mode** — cards are shuffled; click/tap a card to flip it with a real
  3D flip animation, then mark **জানি** (know) or **জানি না** (don't know).
  Cards marked wrong **come back again in the same session** until you mark
  them known.
- **Progress** — per-deck mastery % with a progress bar, plus a bar chart of
  mastery across all decks.
- **Session summary** — after a quiz: correct, wrong and accuracy %, with a
  short note on how you did.
- **Import / Export** — export any deck as JSON, or import a deck JSON file.
- **Starter deck** — "C Programming (Bangla)" with 8 real cards (pointer,
  array, printf, `&`, `*p`, string, for loop, malloc).

## How to use

1. Open `index.html` in any browser (or host it on GitHub Pages).
2. Type a deck name and click **+ ডেক বানাও**.
3. Click **কার্ড দেখো** on a deck to add cards (front = question, back = answer).
4. Click **পড়া শুরু করো** to study: flip the card, answer honestly, and keep
   going until the summary appears.
5. Your decks, cards and mastery are saved automatically in localStorage
   (keys start with `fcmk_`).

## Files

- `index.html` — the whole app (HTML + CSS + JS in one file)

Built by Nafiz Bin Azad
