# Baltiword

**Play it:** [baltiword.netlify.app](https://baltiword.netlify.app)

A daily six-letter word game where every answer is Baltimore: neighborhoods, landmarks, food, sports and the rest of the city's proper nouns. Think Wordle, if Wordle had been raised on Old Bay.

## How it plays

- Six letters, one puzzle a day, the same puzzle for everyone.
- Guesses are checked against a 19,000-word dictionary, so real words count even when they aren't the answer.
- Answers come from a hand-built pool of Baltimore proper nouns.
- A flavor line after each puzzle explains what the answer is and why it matters to the city.
- Hints are there for anyone who needs a nudge.
- Colorblind mode swaps the green and yellow tiles for a high-contrast palette.

## Under the hood

- React + Vite, deployed on Netlify.
- Deterministic daily seeding: the date picks the puzzle, so there's no server and no database. Everyone gets the same word because the math says so.
- Supported by a tip jar instead of ads.

## About this repo

This repo holds the production build that Netlify serves. Source code is coming soon.
