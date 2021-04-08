+++
author = "Jeff Dunham"
title = "SI Baseball"
date = "2021-04-08"
description = "Sports Illustrated Baseball"
tags = [
    "fun",
    "baseball",
    "math",
]
+++

My friend Erik introduced me to a game last night [Sports Illustrated Baseball](https://boardgamegeek.com/boardgame/4642/sports-illustrated-baseball).  It's a table top game where you draft baseball players for a team, roll dice for both pitching and batting.  Certain players can pitch or hit with better probability based on statistics from their best 5 year stretches as players.  Players also have statistics like, speed, fielding, and bunt ability to give you as manager options to decide to steal, bunt, squeeze, and even have injuries on dice rolls.

While playing the game I thought hey, we could just add players as we want and give them stats.  Boy was I apparently wrong.  Erik believes the formula for generating the players are too nuanced and impossible to create with any degree of certainty.  I don't believe this to be true.  In the following posts I'll attempt to not use an email to any creator or sleuth around on forums with others who are attempting to do the same.  Instead I will attempt to figure out some sort of way to generate new players that feel like old players.  The hope by the end of this is to:

1) Add new players as we see fit.
2) Be able to look at 5 year careers for the overall best players for tabletop games.

My approach will be the following:
1) Get probability for dice rolls.
2) Attempt to figure out batting roles
   1) How does batting average factor in to probability of getting a hit vs not.
   2) How does slugging or doubles/triples/HRs factor into probability in the game vs. real 5 year career.
   3) How does flyballs, strikeouts, walks, errors, sac flies, groundouts factor in.
3) Attempt to figure out pitching roles
   1) How do strikeouts, walks factor in
   2) How do we do HR+ and HR-
   3) How do automatic outs for pitchers factor in
4) Player stats
   1) How do defensive stats work, what's good vs. bad
   2) How does speed work?