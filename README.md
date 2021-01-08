# Reinforcment-Learning-NIM-Game-Python-Basic-

NIM GAME
- Series of stems
- Each player has to divide one of item groups into 2 groups those have not different number of members for the group, and have not empty number of members for one of them

Value function
- Uses Temporal Difference Learning
	  V(s) = V(s) + α [ V’(s) – V(s)
- Initialization
	  – Computer wins : V(s)  1
	  – Computer loses : V(s)  0
	  – Other states: V(s)  0.5
	  – Learning rate  α = 0.1

Exploratory move
- Greedy movement
	  – Select highest V’(s)
- ԑ-greedy movement
	  – Tends to select highest V’(s)
	  – But there is possibility to select V’(s) randomly
    
    
