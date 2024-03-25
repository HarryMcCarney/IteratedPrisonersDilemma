This is an f# implementation of RObert Axelrod's classic Prisoner's dilemma tournament held in 1984. 
It successfully reproduces the results described in his book [The Evolution of Cooperation](https://en.wikipedia.org/wiki/The_Evolution_of_Cooperation) 
and includes the most interesting strategies including Tit For Tat, Grudger, Tit for Two Tats, and Tester.

The code is entirely immutable and uses recursion to spawn new generations of successful strategies. 
New strategies can be defined in the Strategies module. 

An interesting adaptation of the game could include variable payoffs depending on depletion/regeneration of a shared environment. 
Perhaps this could explore optimal strategies in non zero sum games that must react to changing payoffs while anticipating the strategies of others.
The maximum score achievable for a sustainable strategy, given a tournament with specific other strategies, may not be the leading strategy overall.
