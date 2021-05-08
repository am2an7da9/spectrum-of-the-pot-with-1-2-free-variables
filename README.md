# spectrum-of-the-pot-with-1-2-free-variables
This Maple program is designed  to  find  all  possible  orders  of  graphs  that  a  given  pot  will realize in Scenario 2 in the case where there are free variables in the solution set of the construction matrix.  More details about this program can be found in the paper, "Computational complexity and pragmatic solutions for flexible tile based DNA self-assembly" written by Leyda Almodovar, Jo Ellis-Monaghan, Amanda Harsy, Cory Johnson, and Jessica Sorrells.

To use the program, one must input an augmented matrix (the construction matrix of a pot) and an integer, m (the order of the target graph). 

If the number of degrees of freedom of $M(P)$ is 0, then the output is the tile distribution for the pot and corresponding order of a graph realized by the pot for the construction matrix and the smallest positive integer n less than or equal to the order of the target graph.

If the number of degrees of freedom of the construction matrix is 1 or 2, then the output is all tile distributions for the pot and corresponding order of a graph realized by the pot and corresponding positive integers less than or equal to the order of the target graph. 

If the number of degrees of freedom of the construction matrix is 3 or more, then a message is displayed stating as much.
