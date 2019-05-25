# similarityScores
RData files for F and D similarity scores after the 1819 NHL season. 

Originally intended as a player projection model, similarities are only calculated for player ages of the same season. For example, Artemi Panarin's 18-19 season, 27 years old, would be compared to all other age 27 player seasons since 2007-2008.

File Information:
- EvaluatedPlayer is the player of question 
- 'Player' is the player related to the similarity score which includes all future seasons of this player to get an idea of how 
their career progressed. 
- Named MILLER because I could never figure out what kind of player JT Miller was. It doesn't stand for anything.

Data used to build these files is via Corsica.Hockey, Hockey-Reference (ages of players). 
Similarity Score is based off gorilla math.
