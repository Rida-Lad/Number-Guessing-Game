# 🔢 Number Guessing Game

A terminal-based guessing game with PostgreSQL integration that tracks player statistics, created for freeCodeCamp's Relational Database certification.

## 🎮 Game Features
- Guess a number between 1-1000
- Tracks your best score (fewest guesses)
- Stores player history in PostgreSQL
- Compares your performance against others

## 📂 Project Files
| File | Purpose |
|------|---------|
| `number_guess.sql` | Database schema and user data |
| `number_guess.sh` | Main game script |

## 🚀 Quick Start
```bash
# 1. Clone the repository
git clone https://github.com/Rida-Lad/number-guessing-game.git
cd number-guessing-game

# 2. Import the database
psql -U postgres -f number_guess.sql

# 3. Make the game executable
chmod +x number_guess.sh

# 4. Play the game!
./number_guess.sh
```
## 📜 Certification
Part of freeCodeCamp's Relational Database Course
