# Final Project for COMSCI450.1 - Using NFL Analytics to Contextualize Player Performance & Predict Playoff Probability
Hypothetical Scenario:  You are the GM of the 2021 Carolina Panthers.  Your club has just finished 5-12 & in last place in the NFC South & 4 wins short of the playoffs.  Your club is 31st/32 in Weighted DVOA, 32nd/32 in EPA per Play on Offense, but ranked 7th/32 in Defensive EPA per Play.

The owner of the club has informed you that while the upcoming season schedule looks a little more favorable than the previous year you must make the playoffs this year or else you will be fired. You have $45M  you can free up in Salary Cap (minus dead money) to spend on Free Agent signings & you have a handful of picks to use in the the ‘22 draft to select players to add value to the club.  Your coach, playcallers and scheme design are above average and considered for this exercise to be stable & competent. 

Hypothesis:  The recipe for earning the playoff berth is one that prioritizes:

1. Top 8 QB play *(Using PFF's QB Power Rating Metric)*
2. Shifting resources to having a Top 12 Passing Defense *(measured by Defensive Dropback EPA, data from NflFast)*
3. Maintaining a roughly league-average total Defense *(measured by Football Outsider's Defensive DVOA metric)*
4. Taking into account Strength of Schedule *(measured by PFF)*
5. Maintain a below-league average team variance *(measured by Football Outsider's variance metric which looks at a team's consistency ratings in their DVOA measure* and can also be extrapolated as the value added by above average coaching or scheme).

Housekeeping Note:  The pdf version of this presentation has been compressed to be compliant with Github file sizes and has depreciated the quality of the graphics.  I recommend viewing and executing this file in R Markdown and just running each code chunk.
All of the data set files are included in the zip.  The Finaldive2.csv can be read in at the very beginning of the code if you don't want to go through all of the data cleaning / merging / transformation aspect of it and want to go right to analysis, plots and models.
[Finaldive2.csv](https://github.com/JL-Doge/COMSCI450.1/files/8375696/Finaldive2.csv)
