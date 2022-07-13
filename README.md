### Capstone Project ATP Tennis Match

Predict the winner of a professional men's tennis match based on ATP matches data from 2018. This could increase the odds of someone betting on the winner of a tennis match.

I will use the data curated by Jeff Sackman derived from Association of Tennis Professionals (ATP) data.
See https://github.com/JeffSackmann/tennis_atp/blob/master/atp_matches_2018.csv

The data consists of the 2889 observations with the following features.

Some of the interesting columns are listed below:

| Variable| Description |
|---------|----------------|
|winner_seed| winner's seeding within tournament |
|winner_entry| 'WC' = wild card, 'Q' = qualifier, 'LL' = lucky loser, 'PR' = protected ranking, 'ITF' = ITF entry, and there are a few others that are occasionally used |
|winner_name| winner's name |
|winner_hand| R = right, L = left, U = unknown. For ambidextrous players, this is their serving hand |
|winner_ht| height in centimeters, where available |
|winner_ioc| three-character country code |
|winner_age| age, in years, as of the tourney_date |
|w_ace| winner's number of aces |
|w_df| winner's number of doubles faults|
|w_svpt| winner's number of serve points|
|w_1stIn| winner's number of first serves made|
|w_1stWon| winner's number of first-serve points won|
|w_2ndWon| winner's number of second-serve points won|
|w_SvGms| winner's number of serve games|
|w_bpSaved| winner's number of break points saved|
|w_bpFaced| winner's number of break points faced|

This will be a supervised classification problem. I will decide which algorithm to use later in the course.