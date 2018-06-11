# N-Queens
Artificial Intelligence class Project , ECE,TUC

Simple implementation for N-Queens Problem in Python

Use python2.7, plus check for Tkinteger lib in python. 

We have build two algorithms for solving N-queens problem and We compares the results.

The Two Algoriths are:
+a) Simulated Annealing --> as a local search algorithm.
+b) Min Conflicts --> CSP algorithm (Constraint Satisfaction Problem).



To compare our methods we run the program 10 times for each input and took the average values for time,conflicts

*conflicts: number of queens who are in danger from others

#Input:
------------

run python2.7 app.py -N -algorith_type

args: \\
+N: the size of problem (NxN board), N-queens

+algorithm_type: choode -SA, or -MC for (Simulated annealing or Min conflicts)

#Output:
----------

Execution time
Number of Conflicts if there are any
Board with Queens as array in terminal
+ Create Images with queens on the board

#Parameterization(check each algorithm's script):
-------------------------------------------------
Change max iterations variable for each algorith and see the results.
+ For Simulated Annealing you can change T (temprature variable) also.
