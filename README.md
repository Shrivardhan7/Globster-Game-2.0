# Globster-Game-2.0
🌍 A browser-based geography guessing game. Identify mystery countries from progressive clues — continent, geography, climate, capital, and population. 4 attempts per round, 10 rounds per game.

# 🌍 Globster

A geography guessing game where you identify mystery countries from progressive clues.

## How to Play

- Each round presents a mystery country
- You get **4 attempts** to guess correctly
- Each wrong guess reveals a new clue in this order:
1. Continent
1. Geography
1. Climate
1. Capital
1. Population
- Use the **HINT** button to reveal the next clue without guessing
- Type a country name — autocomplete will help you

## Scoring

|Attempt|Points|
|-------|------|
|1st try|100   |
|2nd try|70    |
|3rd try|40    |
|4th try|20    |
|Missed |0     |

## Game Structure

- 10 rounds per game
- 15 countries in the pool, shuffled each playthrough
- Score and streak tracked throughout
- Full results summary at the end

## Running the Game

Just open `globster.html` in any modern browser — no server or dependencies needed.

```bash
open globster.html
```

## Tech Stack

- Vanilla HTML, CSS, JavaScript
- No frameworks or dependencies
- Single-file — everything in `globster.html`                        
