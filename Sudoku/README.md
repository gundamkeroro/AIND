# Artificial Intelligence Nanodegree
## Introductory Project: Diagonal Sudoku Solver

# Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: Iff a unit contains only 2 naked twins, this means this 2 naked twins must belong to this two boxes, thus no boxes in this unit can have these 2 naked twins. In this situation, we can use constraint propagation to remove these dight from other boxes in this unit. This method reduced the number of candidates in some boxes.

# Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: In diagonal elements the same values can't appear twice, then add an addtional diagnal unit list. It will also helps to reduce the number of possible values of elements in each box, if a certaion value is in a box, we can remove this value from all diagnal peer in this unit. 