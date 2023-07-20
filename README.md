# Chess Elo Analysis
On my last open tournament we were wondering wheter the Elo rating system is fair in the sense that the expected winning probability by rating is actually met.

# Method
I developed a tool to web-scrape chess-results.com (which contains results of most major open tournaments) and compared actual results versus expected results for each rating difference. The absolute rating is not important.

# Preliminary Results
In open tournaments, in the range of 150 to 250 elo rating difference the stronger player performs about 0.1 less than their expectation (yielding -2 elo per game with K=20). The results are obtained on 5,000 games from the Bad Wiesee 2022 and Benasque 2023 tournaments.  
This might be due to the swiss pairing system.

# Further Work
- Develop functionality to generate statistics based on a pgn database. This enables a player to analyse their personal statistics and how well they perform against better/weaker opposition.
- Analyse league games which do not have the swiss pairing system and might yield unbiased pairings
