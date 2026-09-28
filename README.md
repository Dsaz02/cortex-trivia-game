# Cortex Trivia

Cortex Trivia is a web-based multiplayer STEM trivia game where players create or join shared sessions, answer timed questions, earn points, and compete for the final ranking.

The project was developed collaboratively as a team project and uses a Flask backend, JavaScript frontend, and Upstash Redis for multiplayer session storage.

## Key Features

- Multiplayer session creation and joining
- Host-controlled game flow
- 10 randomized, non-repeating questions per game
- Timed questions with automatic progression
- Time-based scoring that rewards faster correct answers
- Fisher-Yates answer-choice randomization
- Multiple STEM categories:
  - Computer Science
  - Cybersecurity
  - Data Science
  - Information Technology
- Shared question sequence across all players
- Final score and results display
- Redis-backed session and lobby storage

## My Contributions

As part of the development team, my work included:

- Implementing Fisher-Yates answer-choice randomization while preserving correct-answer validation
- Helping implement and integrate time-based scoring
- Contributing to timer behavior and automatic question progression
- Expanding and integrating additional trivia categories
- Testing multiplayer gameplay and feature integration
- Working with Python, Flask, JavaScript, JSON, Git, and GitHub throughout development

## Tech Stack

**Frontend**
- HTML
- CSS
- JavaScript

**Backend**
- Python
- Flask

**Data & Infrastructure**
- Upstash Redis
- JSON question banks
- Vercel
- Git / GitHub

## Architecture

Cortex Trivia uses a client-server architecture:

- The frontend handles the lobby, host interface, quiz gameplay, and results.
- The Flask backend manages sessions, questions, answers, and scoring.
- Upstash Redis stores multiplayer session and lobby data.
- JSON files provide 200 trivia questions across four STEM categories.

Each game selects 10 random, non-repeating questions and distributes the same question sequence to all players.

## Team

Cortex Trivia was developed collaboratively by:

- Diego A. Sanchez
- Jose Carlos Rodriguez
- Daniel Losa
- Renier Herba Borrego
- Deijen Severino
