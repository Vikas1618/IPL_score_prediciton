# IPL_score_prediciton
this project predicts the ipl score based on the current score of team batting only constraint is that minimum 5 overs should have been played by the batting team.
The dataset contains the ball by ball score of ipl matches from first season of IPL 2008 till 10th season 2017.
the model uses the following details from:
venue,	batting_team,	bowling_team,	over_running, runs_scored_in_last_5_overs,	wickets_fall_in_last_5_overs
I have used ridge regression for the score prediciton with hyperparameter tuning for better score prediciton
the model gives scores for:
mae :  20.626397051303154
mse :  726.6110167074808
rmse :  26.955723264410487

