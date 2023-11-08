# TentsAndTrees
Project for Data Structures course by using Queue data structure
-----
-----
Warning: I had a problem while running this program when number of trees more than 6 or 7. It is because of that possible number of tents increase when trees increase,
when trees increase, possible solutions increases exponentially due to queue structure. For a limitless hardware this code can work perfectly, but for a limited hardwares.
It also has a limit for an input.
-----
-----


This is a solution while using queue of array implementation by following this deadline: 
Project Description:
The Tents and Trees Puzzle is a logic puzzle that involves placing tents in a grid filled with trees,
following specific rules. The objective of the puzzle is to place tents in the grid so that each
tree has precisely one tent adjacent to it, either horizontally or vertically. The tents
cannot be placed diagonally.
The puzzle usually comes in a grid with several trees marked on it. The objective is to place a
tent next to each tree so that no tree is left without a tent and no two tents are placed adjacent.
The puzzle rules are simple:
1. Each tree should have precisely one tent next to it, either horizontally or vertically.
2. Tents cannot be placed adjacent, horizontally, vertically, or diagonally.
3. The grid can contain pre-placed tents that must be considered when solving the puzzle.
Your code should automatically validate if tent placement is valid by the rules.
For example, a solution to such a game is below:
You don’t need to implement the game itself, you just need to find a solution to a given initial set
of trees and tents that is generated according to the rules of the game.
The input must consist of a nxn matrix with “T” denoting a tree, and a “X” denoting a tent. For
instance, the case above should be input as:
0 0 0 T 0 T 0 0
0 0 T 0 0 0 T 0
T 0 0 0 0 0 0 0
0 0 T 0 0 0 0 0
T 0 0 0 0 0 T 0
0 0 0 0 T 0 0 T
0 0 T 0 0 0 0 0
The output should be a nxn square matrix in the terminal that shows the tent and the tree
placements with the corresponding letters:
0 0 X T X T 0 0
X 0 T 0 0 0 T X
T 0 X 0 0 0 0 0
0 0 T X 0 0 0 0
T X 0 0 0 X T 0
0 0 0 X T 0 0 T
0 X T 0 0 0 0 X
Project Structure:
● You will use the Java programming language in this project.
● Each one of you must accept the Github Classroom assignment 0. The assignment 0 is
intended to teach you the Github processes. Do not commit anything to it.
● You must use the following GitHub assignment, and create a repository through it for this
project: https://classroom.github.com/a/3DtaIfHo
Your project consists of 2 parts:
1. Part 1 (Project Design): In the first week, you will give us a prototype of your project
design, including only the required method signatures (method name, parameters
without body) with clear Javadoc written for each of the methods and attributes you
will
implement. You should commit all of the changes you made in the first week.
2. Part 2 (Project Implementation): In the remaining time, you will implement the project.
You MUST use Queue data structure. Array-based implementation is prohibited.
External library usage is also forbidden.
IMPORTANT NOTES:
● You MUST accept the Github assignment with your name only. Those that can not
be verified will receive 0.
● Your commit frequency and the content will be graded.
● If you don’t submit the first part of the project, you cannot submit the second part.
● If you submit/commit an implementation in the first part of the project containing
any piece of code other than the method signatures, attributes, and Javadoc, you
will get 0 in this project.
