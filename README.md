


STUDENT NAME: RITESH SHAH 
INSTRUCTOR’S NAME: PROF. BROOKE M.S.

SOUTHERN NEW HAMPSHIRE UNIVERSITY 


DATE OF SUBMISSION: 25/03/2022 
MODULE FOUR

 

 

Category Two: Algorithms and Data Structures
Checkers game.
The following enhancements have been completed:
•Identified the game winning handle and added a memoization variable to enable the game to store series of winning moves. This will shorten the steps taken to win if a move is identified as being in the wining moves series.
•Implementation of a depth first search algorithm (min-max) when identifying the next move to make. This will help reduce the time it takes to get a suitable move from the current time which uses a breadth first search algorithm.
The skills illustrated here are in the use of algorithms and data structures to solve improve performance and reduce the number of steps required to reach a desired solution. When using algorithms we are trying to optimize a solution. The solution could be found in many different ways but we find the most efficient way such that we can save on time of execution and the resources that would be required to complete the task. Data structures are ways of storing data so that it can be manipulated in a desired manner e.g. you can use a queue to implement a first in first out operation on a set of variables or a stack for a last in first out operation. This structures are very important when dealing with arrays of data.

The checkers game



Add three new lists

Append moves made by each player to their respective lists

Append the winning series of moves to the winning series list


When making a move check if the move exists in a winning list containing the series of moves that lead to a win and select the next move from there


Implement a depth first search to reduce the implementation time for the move selection process. Current implementation is breadth first search wich has high space and time complexity.

Iterative depth first search (IDFS) implementation 


Running the game

Playing the game




As shown above, the planned enhancements have been done. This artefact has demonstrated various skills that are relevant to my ePortfolio. These include:
•Working with data structures.
•Using algorithms to make processes efficient in time and computing resources.
•Good coding practices and standards.
The artefact has now reduced the time it takes to select a next move by using the memoization technique to store winning moves. When calculating a next move, we have substituted the breadth first search algorithm that was in use for an iterative depth first search algorithm that has reduces the space and time complexity of the algorithm thus making it more efficient.
The process taught me how to practice good coding standards and well commented code. I also learnt the importance of selecting a good algorithm to implement for any given task since they perform differently under different circumstances.
