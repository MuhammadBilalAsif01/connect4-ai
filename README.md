# Connect 4 — AI vs Human

A fully playable Connect 4 game with an AI opponent built from scratch using the **Minimax algorithm with Alpha-Beta pruning**.

Built for **CSE307 — Introduction to Artificial Intelligence** at IBA Karachi.

🎮 **[Play the live demo here](https://MUHAMMADBILALASIF01.github.io/connect4-ai)**

---

## Group Members

| Name | ERP |
|---|---|
| Muhammad Bilal Asif | 30627 |
| Moiz Lotia | 31584 |
| Mujtaba Khan | 31575 |

---

## How to Run

No install needed. Just download `index.html` and open it in any browser.

---

## How the AI Works

The AI is built on two core concepts from Unit 8 of the course:

**Minimax** — The AI recursively explores all possible future game states up to a set depth, assuming both players always play optimally. It picks the move that leads to the best guaranteed outcome.

**Alpha-Beta Pruning** — An optimization on top of Minimax that cuts branches which cannot affect the final decision. This reduces nodes evaluated by up to 90% without changing the result, allowing the AI to search deeper in the same time.

**Heuristic Scoring** — For non-terminal board states at the depth limit, a scoring function evaluates the position based on center column control, connected piece patterns, and opponent threat blocking.

### Difficulty Levels

| Level | Search Depth | Behavior |
|---|---|---|
| Easy | 2 | Makes basic moves, beatable |
| Medium | 5 | Plays well, blocks threats |
| Hard | 8 | Very strong, hard to beat |

---

## Features

- Minimax + Alpha-Beta pruning implemented from scratch
- Three difficulty levels
- Live stats: nodes evaluated, search depth, AI think time
- Animated piece drops and win highlight
- Scoreboard tracking wins across multiple games
- Single HTML file — no frameworks, no libraries, no install

---

## Course Relevance

| Concept | Unit |
|---|---|
| Minimax Algorithm | Unit 8 — Adversarial Search |
| Alpha-Beta Pruning | Unit 8 — Adversarial Search |
| Game Tree Search | Unit 8 — Adversarial Search |
| Heuristic Evaluation | Unit 6/7 — Informed Search |
