This README explains how to run our programs for Project 2.
Note: We had to run our armadillo programs using these extra commands:
-larmadillo -llapack -lblas
Not sure why this is the case, but I'm guessing it's related to us using windows.


PROBLEM 2
To compile and run our program to.cpp, we used this command:

g++ to.cpp -o to.exe -O2 -larmadillo -llapack -lblas && ./to.exe


PROBLEM 3
To compile and run our program offdiag.cpp, we used this command:

g++ offdiag.cpp -o offdiag.exe -O2 -larmadillo -llapack -lblas && ./offdiag.exe


PROBLEM 4
To compile and run our program fire.cpp, we used this command:

g++ fire.cpp -o fire.exe -O2 -larmadillo -llapack -lblas && ./fire.exe


PROBLEM 5
To compile and run our program fem.cpp, we used this command with an int as argument at the end describing our N:

g++ fem.cpp -o fem.exe -O2 -larmadillo -llapack -lblas && ./fem.exe "number of N here"


PROBLEM 6
To compile and run our program seks.cpp, we used this command with an int as argument at the end describing our N, as well as changing the name of our 
.txt file to "xhat_eigenvectors(insert N here).txt":

g++ seks.cpp -o seks.exe -O2 -larmadillo -llapack -lblas && ./seks.exe "number of N here"


For the python file that plots our numbers we'll run it with the following command:

python3 plotoppg6.py


Hope this works out okay!
