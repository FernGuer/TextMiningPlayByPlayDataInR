# TextMiningPlayByPlayDataInR
Preliminary effort to conduct performance attribution analysis on NFL play-by-play data.

Function descriptions and objectives are described in Code. Data cleaning, player identification, and subsetting for use toward primary objectives is complete.

Preliminary objective: To identify the unique contribution to PASS completions of players participating in a play.
Since QB and WR are attributed statistics in each case, determining whether QBWR combination is attributable to WR or QB is of tantamount importance when evaluating player performance.

Secondary objective: To identify Poisson distributions for different players by region on the field. RUSH contains 7 possible directions, PASS contains 6. Determining frequentist probabilities for Rushers, Passers, Receivers, and Tacklers can help identify where players (and team) strengths lie.

Tertiary objective (optional): To use a mixed effects model to determine the contribution of each player (QBWR) towards conversion or failure to convert on PASS.
