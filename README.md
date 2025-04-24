# cs234-assignment1-gridworld-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs234-assignment1-gridworld-solved/

Gridworld

Consider the following grid environment. Starting from any unshaded square, you can move up, down, left, or right. Actions are deterministic and always succeed (e.g. going left from state 16 goes to state 15) unless they will cause the agent to run into a wall. The thicker edges indicate walls, and attempting to move in the direction of a wall results in staying in the same square (e.g. going in any direction other than left from state 16 stays in 16). Taking any action from the green target square (no. 12) earns a reward of rg (so r(12,a) = rg ∀a) and ends the episode . Taking any action from the red square of death (no. 5) earns a reward of rr (so r(5,a) = rr ∀a) and ends the episode. Otherwise, from every other square, taking any action is associated with a reward rs ∈ {−1,0,+1}

(even if the action results in the agent staying in the same square). Assume the discount factor γ = 1, rg = +5, and rr = −5 unless otherwise specified.
