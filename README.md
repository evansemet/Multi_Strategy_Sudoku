# Multi Strategy Sudoku
Explores Different Sudoku Solving Strategies


I used Python to solve a series of different difficulty Sudoku boards. Two strategies were tested and timed.
The two strategies used were standard backtracking and an SAT solver using Microsoft's Z3 library.

To no surprise, the Z3 strategy was significantly faster as a whole than the backtracking algorithm. However, the backtracking algorithm actually performed slightly better on the easiest board tested.

Times (in seconds) for backtracking (on easy, medium, and hard board in that order):
0.4456307888031006
2.991603136062622
6.835436105728149

Times for Z3:
0.5443072319030762
0.6390235424041748
0.9134602546691895
