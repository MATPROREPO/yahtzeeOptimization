# yahtzeeOptimization
Construction of yahtzee agents in Python for strategy optimization

#TBD:
Construct player agents
Construct die roll routine
Construct scoring routine
Construct state assessment matrix
  Input current die state
  Assess current score
  Assess score potential of current dice set
    Example: holding {2,3,4,5,5} might elect to try for large straight instead of 5s
    Strategy here is likely best not programmed for and instead solved using a neural net (Q-Learning?)
