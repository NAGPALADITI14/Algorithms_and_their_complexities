Tower of Hanoi 

Overview  : 

The Tower of Hanoi is a classic problem in computer science and mathematics that involves moving a stack of discs from one rod to another, subject to the following constraints:

1) Only one disc can be moved at a time.

2) Each move consists of taking the upper disc from one of the stacks and placing it on top of another stack or on an empty rod.

3) No disc may be placed on top of a smaller disc.


Problem Statement  :

Given three rods and a number of discs of different sizes, the task is to move all the discs from one rod to another rod, following the rules mentioned above.

Algorithm  :

The Tower of Hanoi problem can be solved using a recursive algorithm. The key insight is to break down the problem into smaller subproblems.

1) Base Case: If there is only one disc, move it from the source rod to the destination rod.

2) Recursive Step: Move n-1 discs from the source rod to the auxiliary rod, then move the remaining disc from the source rod to the destination rod.

3) Repeat: Recursively apply the algorithm to the subproblems until all discs are moved to the destination rod.


Time Complexity  :

The time complexity of the Tower of Hanoi algorithm is O(2^n), where n is the number of discs. This is an exponential time complexity, and the number of moves required doubles with each additional disc.

<img width="497" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/c6a4d98a-722c-4217-b30c-a448abc2da3a">

Usage  :

The Tower of Hanoi problem is often used to demonstrate the principles of recursion and algorithmic design. It also has applications in algorithm analysis and teaching computational thinking.

Implementation Tips  :

1) Ensure that the moveDisc function is implemented according to the specific requirements of the application (e.g., printing the move or updating a graphical representation).

2) Validate inputs to the towerOfHanoi function to avoid errors or unexpected behavior.
