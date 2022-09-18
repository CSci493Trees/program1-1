# Program 1.1:  Newick Format


### Learning Objective: to use basic tree I/O methods from the biopython libraries. 
### Available Libraries: Biopython and core Python 3.7+.

### Description: read in tree in Newick format and print out the same tree.

To get started, install Biopython in your IDE and read through the Phylo wiki on reading, writing, and drawing trees in Newick format. Note that the wiki uses a module that's deprecated from Python 2 for string wrapper. Instead use the io module:

`from io import StringIO`

### Deliverables:

- A .py file that prompts the user for a string containing a tree in Newick format, and then prints out the same tree.  Your program should gracefully handle poorly formed strings, giving an error message.
- A file containing strings to be used to test your program.
