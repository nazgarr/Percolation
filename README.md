# Percolation

Percolation is a little pet project assignment thingy if you want to call it that. 

Princeston has a course on Coursera dubbed 'Algorithms part 1,' by Sedgewick and Wayne. [Link to assignment here.](https://coursera.cs.princeton.edu/algs4/assignments/percolation/specification.php)

What lies in this repository is the completed first assignment, percolation.java and percolationstats.java. 



# The Monte Carlo Simulation 

This repository holds two things, the actual implementation to create the simulation using int arrays and weighted quick union data structures
(percolation.java), and the simulation (percolationstats.java) that uses the implementation to retrieve the computational
threshold it takes for the top to have a clear path to the bottom (more lower), something not yet fetchable in current
mathematical theory. Only in computational theory. 

In layman's terms, the assignment wants you to do this: open boxes at random in an x by x square. Once the top can find a clear path to the bottom, retrieve the amount of boxes opened. Run the simulation a gazillion times, and you will find that the computational threshold converges at 59.3%.
That is, open 59.3% of total boxes, and the percolation probability shoots up to 100%. 

# Significance

Fill an aggregate with conductive material. Once you fill it past 59.3% of its capacity, chances are the aggregate is now a conductor. The Percolation model is everywhere. 
