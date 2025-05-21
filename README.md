# Steamroller

Steamroller is an attempt to perform sentiment analysis on breaking news in sports to identify "steamers", a market with rapidly dropping odds e.g. a team's key player becomes injured / suspended.

This requires two parts, firstly the sentiment analysis needs to scan twitter / other breaking news sites and perform sentiment analysis.

The second part needs to determine whether this breaking news will have a positive / negative effect on the odds of that team and determine whether or not to back lay.

But before any of this, we need to see if it is possible to make a profit doing this.

We have to conistently identify odds that will shorten / lengthen by a significant amount to make profit. If the odds movements are too small, we would have to stake very large amounts for a small reward, and so a false positive becomes extremely risky. We need to factor in exchange commission as well.

The first part of this project will be analysing historical data to determine the correlation between odds movements and team information. We can get historical price data from Betfair. For the sentiment side, we need to find accounts that consistently post reliable news ahead of the rest of the pack. Think 'leakers', but these are consistently unreliable.
