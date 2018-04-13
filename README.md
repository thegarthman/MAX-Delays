# MAX-Delays
Experimenting with Twitter API, text searching, and Python Scikit-Learn to predict probability of a MAX delay.

Covariates: Line, day of week, month

Steps:
1. Queried data from Trimet's Twitter
2. Flagged tweets by line and date
3. Used logistic regression (80% train, 20% test)
4. Cross validated, accuracy around 70%

Future improvements:
Different model type. Potentially a decision tree.
Set up an update to Twitter with a format such as:
  Probability of MAX delay on [DATE]
  Blue:   X1%
  Red:    X2% 
  Yellow: X3%
  Orange: X4%
  Green:  X5%
