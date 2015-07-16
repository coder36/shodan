Bowling Scores
==============

The aim of this paired programming exercise is to model a game of bowling. Given a series of input the program should output the players final score.

Each game, or line of bowling, includes ten turns, or frames for the bowler.

In each frame, the bowler gets up to two tries to knock down all the pins.

If in two tries, he fails to knock them all down, his score for that frame is the total number of pins knocked down in his two tries.

If on his first try in the frame he knocks down all the pins, this is called a strike. His turn is over, and his score for the frame is ten plus the simple total of the pins knocked down in his next two rolls.

If he gets a spare or strike in the last (tenth) frame, the bowler gets to throw one or two more bonus balls, respectively. These bonus throws are taken as part of the same turn. If the bonus throws knock down all the pins, the process does not repeat: the bonus throws are only used to calculate the score of the final frame.

The game score is the total of all frame scores.



		Example 1: Gutter games (all zeros)
		[0,0],[0,0],[0,0],[0,0],[0,0],[0,0],[0,0],[0,0],[0,0],[0,0]
		-> 0

		Example 2: All ones
		[1,1],[1,1],[1,1],[1,1],[1,1],[1,1],[1,1],[1,1],[1,1],[1,1], 
		-> 20

		Example 3: Strike, followed by a 3, followed by a 4
		[10,0],[3,0],[4,0],[0,0],[0,0],[0,0],[0,0],[0,0],[0,0],[0,0]
		-> 24

		Example 4: Perfect Game
		[10,0],[10,0],[10,0],[10,0],[10,0],[10,0],[10,0],[10,0],[10,0],[10,10,10]
		-> 300

The program does not need to:

* Check for valid Rolls
* Check for correct number of rolls and frames
* Provide scores for intermediate frames


Objectives
----------

In your pair, use TDD to drive out a solution.  Keep your code clean and simple.

