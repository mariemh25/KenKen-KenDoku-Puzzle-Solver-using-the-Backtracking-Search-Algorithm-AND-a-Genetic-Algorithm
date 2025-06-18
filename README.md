#  KenKen (KenDoku) Puzzle Solver

A smart puzzle solver that tackles KenKen (KenDoku) puzzles using both:
-  **Backtracking Search Algorithm**
-  **Genetic Algorithm (GA)**


##  About the KenKen Puzzle

KenKen is a logical and mathematical puzzle that blends Sudoku with arithmetic operations. The puzzle is played on an N×N grid, where:
- Each **row and column** must contain unique digits from 1 to N.
- **Cages** (outlined groups of cells) contain a target number and a mathematical operation (➕, ➖, ✖️, ➗) that must be achieved using the digits in that cage.

Example:  
A cage labeled `6+` in a 4×4 puzzle must be filled with digits (e.g., 1, 2, 3) that sum to 6.



##  Project Features

###  Solving Algorithms
- **Backtracking Search Algorithm**
  - Explores all possible solutions recursively
  - Prunes branches violating constraints
- **Genetic Algorithm (GA)**
  - Represents puzzle states as chromosomes
  - Applies selection, crossover, and mutation
  - Evolves the population to find optimal/near-optimal solutions

###  Interface
- Interactive user-friendly UI
- Choose solving method (Backtracking or GA)
- Visualize grid and solution process
- Monitor performance metrics (e.g., fitness, time)

###  Output & Visualization
-  `fitness_plot.png`: Displays fitness over generations (GA)
-  `block_diagram_kenken_detailed.png`: System architecture



##  Folder Structure
```
final-project/
├── AIproject.ipynb                    # Main Jupyter Notebook (Backtracking + GA)
├── block_diagram_kenken_detailed.png  # System architecture diagram
└── fitness_plot.png                   # Fitness graph from Genetic Algorithm
```


##  Performance Metrics

-  **Solution Time**
-  **Fitness Score** (for GA)
-  **Correctness** (based on row/column uniqueness and cage validation)



##  Technologies Used

- Python (NumPy, Matplotlib, ipywidgets)
- Jupyter Notebook
- Artificial Intelligence (Search & Evolutionary Algorithms)


##  Challenges Tackled

- Encoding KenKen puzzles as chromosomes
- Handling arithmetic constraints during evolution
- Maintaining valid row/column uniqueness in GA
- Comparing traditional search vs evolutionary approach



##  Outcome

By using both **Backtracking** and **Genetic Algorithms**, this project showcases the strengths and trade-offs of each method in solving complex logic puzzles. It's a great demonstration of applying AI techniques to real-world problem-solving.

