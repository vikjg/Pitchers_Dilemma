# Pitchers_Dilemma

Applying different two-player zero-sum game solving algorithms, Fictitious-Play, CFR, etc to investigate Nash equilibia of pitching circumstances (if they exist). 
Idea inspired by Dylan Drummey's article at https://www.pitcherlist.com/the-pitchers-dilemma-applying-game-theory-to-pitching-decisions/

Current idea: Investigating notions of choosing pitch type and pitch location for a 'general batter' vs a 'general pitcher' using league averages.
- A batter has a fixed strategy, assume they will always put their best swing on the ball, so their historic wOBA for a certain count, pitch type, and location will serve as their strategy.
- A pitcher has more strategic choice, their strategy can vary to minimize batter wOBA, or to maximize their historic opposing wOBA for said pitch.

Still have yet to hypothesize a payoff matrix for these scenarios, lots of work to come and lots of adaptations to be made. 
