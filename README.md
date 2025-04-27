# cmpsc442-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [CMPSC442 Homework 2 Solved](https://www.ankitcodinghub.com/product/cmpsc-442-homework-2-100-points-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123469&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPSC442 Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
TO PREPARE AND SUBMIT HOMEWORK

Follow these steps exactly, so the Gradescope autgrader can grade your homework. Failure to do so will result in a zero grade:

1. You *must* download the homework template file homework1_cmpsc442.py from Canvas. Each template file is a python file that gives you a headstart in creating your homework python script with the correct function names for autograding.

2. You *must* download the code for the GUI homework2_lights_out_gui.py from Canvas. You will use this to interactively play the Lights Out puzzle.

3. You *must* rename the file by replacing cmpsc442 with your PSU id from your official PSU. For example, if your PSU email id is abcd1234, you would rename your file as

homework1_abcd1234.py to submit to Canvas, and to Gradescope.

5. Make sure your file can import before you submit; the autograder imports your file. If it won’t import, you will get a zero.

Instructions

In this assignment, you will explore three classic puzzles from the perspective of uninformed search.

A skeleton file homework2_cmpsc442.py containing empty definitions for each question has been provided. Since portions of this assignment will be graded automatically, none of the names or function signatures in this file should be modified. However, you are free to introduce additional variables or functions if needed.

You will find that in addition to a problem specification, most programming questions also include a pair of examples from the Python interpreter. These are meant to illustrate typical use cases to clarify the assignment, and are not comprehensive test suites. In addition to performing your own testing, you are strongly encouraged to verify that your code gives the expected output for these examples before submitting.

You are strongly encouraged to follow the Python style guidelines set forth in PEP 8, which was written in part by the creator of Python. However, your code will not be graded for style.

1. N-Queens [25 points]

In this section, you will develop a solver for the n-queens problem, wherein n queens are to be placed on an n x n chessboard so that no pair of queens can attack each other. Recall that in chess, a queen can attack any piece that lies in the same row, column, or diagonal as itself.

1. [5 points] Rather than performing a search over all possible placements of queens on the board, it is sufficient to consider only those configurations for which each row contains exactly one queen. Without taking any of the chess-specific constraints between queens into account, implement the pair of functions num_placements_all(n) and

num_placements_one_per_row(n) that return the number of possible placements of n queens

on an n x n board without or with this additional restriction. Think carefully about why this restriction is valid, and note the extent to which it reduces the size of the search space. You should assume that all queens are indistinguishable for the purposes of your calculations.

2. [5 points] With the answer to the previous question in mind, a sensible representation for a board configuration is a list of numbers between 0 and n – 1, where the ith number designates the column of the queen in row i for 0 ≤ i &lt; n. A complete configuration is then specified by a list containing n numbers, and a partial configuration is specified by a list containing fewer than n numbers. Write a function n_queens_valid(board) that accepts such a list and returns True if no queen can attack another, or False otherwise. Note that the board size need not be included as an additional argument to decide whether a particular list is valid.

Though our discussion of search in class has primarily covered algorithms that return just a single solution, the extension to a generator which yields all solutions is relatively simple. Rather than using a return statement when a solution is encountered, yield that solution instead, and then continue the search.

&gt;&gt;&gt; solutions = n_queens_solutions(4) &gt;&gt;&gt; list(n_queens_solutions(6))

&gt;&gt;&gt; next(solutions) [[1, 3, 5, 0, 2, 4], [2, 5, 1, 4, 0, 3],

[1, 3, 0, 2] [3, 0, 4, 1, 5, 2], [4, 2, 0, 5, 3, 1]]

&gt;&gt;&gt; next(solutions) &gt;&gt;&gt; len(list(n_queens_solutions(8)))

[2, 0, 3, 1] 92

2. Lights Out [40 points]

The Lights Out puzzle consists of an m x n grid of lights, each of which has two states: on and off. The goal of the puzzle is to turn all the lights off, with the caveat that whenever a light is toggled, its neighbors above, below, to the left, and to the right will be toggled as well. If a light along the edge of the board is toggled, then fewer than four other lights will be affected, as the missing neighbors will be ignored.

In this section, you will investigate the behavior of Lights Out puzzles of various sizes by implementing a LightsOutPuzzle class. Once you have completed the problems in this section, you can test your code in an interactive setting using the provided GUI. See the end of the section for more details.

1. [2 points] A natural representation for this puzzle is a two-dimensional list of Boolean values, where True corresponds to the on state and False corresponds to the off state. In the

&gt;&gt;&gt; b = [[True, False], [False, True]] &gt;&gt;&gt; b = [[True, True], [True, True]]

&gt;&gt;&gt; p = LightsOutPuzzle(b) &gt;&gt;&gt; p = LightsOutPuzzle(b)

&gt;&gt;&gt; p.get_board() &gt;&gt;&gt; p.get_board()

[[True, False], [False, True]] [[True, True], [True, True]]

2. [3 points] Write a top-level function create_puzzle(rows, cols) that returns a new LightsOutPuzzle of the specified dimensions with all lights initialized to the off state.

&gt;&gt;&gt; p = create_puzzle(2, 2) &gt;&gt;&gt; p = create_puzzle(2, 3)

&gt;&gt;&gt; p.get_board() &gt;&gt;&gt; p.get_board()

[[False, False], [False, False]] [[False, False, False],

[False, False, False]] 3. [5 points] In the LightsOutPuzzle class, write a method perform_move(self, row, col) that toggles the light located at the given row and column, as well as the appropriate neighbors.

&gt;&gt;&gt; p = create_puzzle(3, 3) &gt;&gt;&gt; p = create_puzzle(3, 3)

&gt;&gt;&gt; p.perform_move(1, 1) &gt;&gt;&gt; p.perform_move(0, 0) &gt;&gt;&gt; p.get_board() &gt;&gt;&gt; p.get_board()

[[False, True, False], [[True, True, False],

[True, True, True ], [True, False, False],

[False, True, False]] [False, False, False]]

5. [2 points] In the LightsOutPuzzle class, write a method is_solved(self) that returns whether all lights on the board are off.

&gt;&gt;&gt; b = [[True, False], [False, True]] &gt;&gt;&gt; b = [[False, False], [False, False]]

&gt;&gt;&gt; p = LightsOutPuzzle(b) &gt;&gt;&gt; p = LightsOutPuzzle(b)

&gt;&gt;&gt; p.is_solved() &gt;&gt;&gt; p.is_solved()

False True

6. [3 points] In the LightsOutPuzzle class, write a method copy(self) that returns a new LightsOutPuzzle object initialized with a deep copy of the current board. Changes made to the original puzzle should not be reflected in the copy, and vice versa.

&gt;&gt;&gt; p = create_puzzle(3, 3) &gt;&gt;&gt; p = create_puzzle(3, 3)

&gt;&gt;&gt; p2 = p.copy() &gt;&gt;&gt; p2 = p.copy()

&gt;&gt;&gt; p.get_board() == p2.get_board() &gt;&gt;&gt; p.perform_move(1, 1)

True &gt;&gt;&gt; p.get_board() == p2.get_board()

False

&gt;&gt;&gt; p = create_puzzle(2, 2) &gt;&gt;&gt; for i in range(2, 6):

&gt;&gt;&gt; for move, new_p in p.successors(): … p = create_puzzle(i, i + 1) … print(move, new_p.get_board()) … print(len(list(p.successors())))

… …

(0, 0) [[True, True], [True, False]] 6

(0, 1) [[True, True], [False, True]] 12

(1, 0) [[True, False], [True, True]] 20

(1, 1) [[False, True], [True, True]] 30

representations. You will then be able to use the built-in set data type to check for the presence or absence of a particular state in near-constant time.

&gt;&gt;&gt; p = create_puzzle(2, 3) &gt;&gt;&gt; b = [[False, False, False], &gt;&gt;&gt; for row in range(2): … [False, False, False]]

… for col in range(3): &gt;&gt;&gt; b[0][0] = True

… p.perform_move(row, col) &gt;&gt;&gt; p = LightsOutPuzzle(b)

… &gt;&gt;&gt; p.find_solution() is None

&gt;&gt;&gt; p.find_solution() True

[(0, 0), (0, 2)]

Once you have implemented the functions and methods described in this section, you can play with an interactive version of the Lights Out puzzle using the provided GUI by running the following command:

The arguments rows and cols are positive integers designating the size of the puzzle.

3. Linear Disk Movement [30 points]

In this section, you will investigate the movement of disks on a linear grid.

The starting configuration of this puzzle is a row of L cells, with disks located on cells 0 through n – 1. The goal is to move the disks to the end of the row using a constrained set of actions. At each step, a disk can only be moved to an adjacent empty cell, or to an empty cell two spaces away, provided another disk is located on the intervening cell. Given these restrictions, it can be seen that in many cases, no movements will be possible for the majority of the disks. For example, from the starting position, the only two options are to move the last disk from cell n – 1 to cell n, or to move the secondto-last disk from cell n – 2 to cell n.

1. [15 points] Write a function solve_identical_disks(length, n) that returns an optimal solution to the above problem as a list of moves, where length is the number of cells in the row and n is the number of disks. Each move in the solution should be a two-element tuple of the form (from, to) indicating a disk movement from the first cell to the second. As suggested by its name, this function should treat all disks as being identical.

Your solver for this problem should be implemented using a breadth-first graph search. The exact solution produced is not important, as long as it is of minimal length.

&gt;&gt;&gt; solve_identical_disks(4, 2) &gt;&gt;&gt; solve_identical_disks(4, 3)

[(0, 2), (1, 3)] [(1, 3), (0, 1)]

&gt;&gt;&gt; solve_identical_disks(5, 2) &gt;&gt;&gt; solve_identical_disks(5, 3)

[(0, 2), (1, 3), (2, 4)] [(1, 3), (0, 1), (2, 4), (1, 2)]

2. [15 points] Write a function solve_distinct_disks(length, n) that returns an optimal solution to the same problem with a small modification: in addition to moving the disks to the end of the row, their final order must be the reverse of their initial order. More concretely, if we abbreviate length as L, then a desired solution moves the first disk from cell 0 to cell L – 1, the second disk from cell 1 to cell L – 2, . . . , and the last disk from cell n – 1 to cell L – n.

Your solver for this problem should again be implemented using a breadth-first graph search. As before, the exact solution produced is not important, as long as it is of minimal length.

&gt;&gt;&gt; solve_distinct_disks(4, 2) &gt;&gt;&gt; solve_distinct_disks(4, 3)

[(0, 2), (2, 3), (1, 2)] [(1, 3), (0, 1), (2, 0), (3, 2), (1, 3),

&gt;&gt;&gt; solve_distinct_disks(5, 2) (0, 1)]

[(0, 2), (1, 3), (2, 4)] &gt;&gt;&gt; solve_distinct_disks(5, 3)

[(1, 3), (2, 1), (0, 2), (2, 4), (1, 2)]

4. Feedback [5 points]

1. [1 point] Approximately how long did you spend on this assignment?

2. [2 points] Which aspects of this assignment did you find most challenging? Were there any significant stumbling blocks?

3. [2 points] Which aspects of this assignment did you like? Is there anything you would have changed?
