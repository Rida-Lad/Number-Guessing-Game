# Database Setup
Run the following commands in psql:
CREATE DATABASE number_guess;
\c number_guess
CREATE TABLE users (user_id SERIAL PRIMARY KEY, username VARCHAR(22) UNIQUE NOT NULL, games_played INT DEFAULT 0, best_game INT);
   