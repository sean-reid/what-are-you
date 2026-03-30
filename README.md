# What ____ Are You?

A personality quiz that tells you what Wikipedia article you are.

Pick a category (Animals, Countries, Foods, etc.), answer 10 absurd multiple-choice questions, and get matched to a real Wikipedia article based on your answers. The Jeopardy theme plays in the background and speeds up as you progress.

## How it works

1. Categories are fetched dynamically from Wikipedia's API and singularized for display
2. You pick one, then answer 10 questions from a pool of 500
3. Your answers are hashed and mapped to a Wikipedia category member
4. The result page shows the article's image, summary, and a link to read more

## Running

Open `index.html` in a browser. No build step, no dependencies, no server required.

## Tech

- Vanilla HTML/CSS/JS (single file)
- Wikipedia API for categories and article data
- Web Audio API for gapless Jeopardy theme playback
