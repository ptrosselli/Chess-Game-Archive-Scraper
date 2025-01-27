# Chess-Game-Archive-Scraper
Python script to scrape chess.com archives using the official chess.com api. Get the moveset from every game of any player.

1. Download the python script
2. pip install requests
3. python3 scraper.py any_valid_chesscom_username
4. View username_white.txt / _black.txt output files

Note this will not print the fill pgns, but will print the moveset within them, skipping variants of chess of game that were played nonconventional (games begining from a starting position other than the standard).

