Programming Language: 
Python Version: Python 3.8.5



************************* First Extra Test Case from Piazza***********
It took a while to run, so here's my output. 
dylansuga@DESKTOP-3ACGC81:~/CS411/idastar_puzzle15$ python3 ./idastar.py 5 2 4 8 10 3 11 14 6 0 9 12 13 1 15 7
Enter Heuristic either 'H' or 'M' (H is Hamming and M is Manhattan): M


Found Solution!
Moves: D R R U U L L D R R U U L L D L D R R D L U U L U R R D D R D
Number of Nodes expanded: 83821207
Time Taken: 2438.004
Memory Used: 679288384 kb




Instructions:

In the command line, type: "python3 ./idastar.py 1 3 4 8 5 2 0 6 9 10 7 11 13 14 15 12" where the numbers after ./thesolver.py can be any of the 15 numbers
(But if running in VS code, then it should just be python ./idastar.py ...)

Next user will be prompted with "Enter Heuristic either 'H' or 'M' (H is Hamming and M is Manhattan):" in which entering 'M' will make A* use a Manhattan Heuristic or entering 'H' will make A* use a Hamming Heuristic.

This should give the output of:

Enter Heuristic either 'H' or 'M' (H is Hamming and M is Manhattan): H


Found Solution!
Moves: R U L L D R D R D
Number of Nodes expanded: 516
Time Taken: 0.006
Memory Used: 4264 kb

  ------------OR-----------------------------------------------

Enter Heuristic either 'H' or 'M' (H is Hamming and M is Manhattan): M


Found Solution!
Moves: R U L L D R D R D
Number of Nodes expanded: 877
Time Taken: 0.012
Memory Used: 7976 kb
