# Assingment 3
This code is a divide and concquer solution that solves the Warehouse Crate Stacking Problem. This is solved using a Divide and Conquer approach where the main problem of moving num crates is broken into smaller subproblems which are moving num-1 crates to the auxiliary rack and then moving num-1 crates from the auxiliary rack to the destination rack. The results are combined recursively and reach the base case where num = 1 where it is moved directly from the source rack to the destination rack.

How To Run:
Put the main c++ source file in your main directory. To compile run the command from your windows terminal:
g++ -o a a3.cpp
Then to run the executable run:
.\a.exe
You can also just run the source file from an IDE like clion.
Everything should print to the console and you should put in an input when prompted. Note that it may take a while for higher values such as 15-20 up to 500 seconds.
