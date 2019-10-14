# ictlife-code-puzzle
Crypt Arithmetic Code Challenge 

# Installation
git clone https://github.com/lexluga/ictlife-code-puzzle

# Run
To Execute the file run open your terminal or python console and run 
python CryptArithmetic.py

# Pseudocode
1. Find All the letters in the puzzle 
2. Find Unique Letters in the Puzzle 
3. Check if there are more 10 Unique Digits ( Implying that the puzzle is definately Unsolvable)
4. Converts the letter to ASCII equivalents with an object Generator.
5. Converts All posssible solutions with itertools.permutations()
6. Converts Each Possible Solution to a Python Expression
7. Tests each Possible Solution by testing the python expression with the eval() function.

# Time Complexity

1 . O(n^2)
Given that we perform a linear time operation for each value in the input data.

