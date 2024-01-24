# AI: Reasoning & Problem Solving - Application of CSP using Backtracking and Local Search

## Description
This repository is dedicated to showcasing the application of Constraint Satisfaction Problems (CSP) techniques in solving complex puzzles. It focuses on two popular puzzles: Kakuro and Sudoku, using backtracking and local search algorithms. The project demonstrates how AI and reasoning can be effectively applied to problem-solving in a structured and logical manner.

## Implementation Details

### Kakuro
- **Algorithm**: The Kakuro puzzle is solved using a combination of backtracking and constraint propagation techniques.
- **Constraint Propagation**: This technique is used to reduce the search space by eliminating values that violate constraints.
- **Backtracking**: A depth-first search approach that tries different values for cells and backtracks when a conflict is detected.
- **Minimum Remaining Values (MRV) Heuristic**: This heuristic is applied to choose the next cell to fill, prioritizing cells with the fewest legal values left.
- **Non-Recursive Approach**: The solution is implemented in a non-recursive manner using a stack to keep track of the state.
- **Performance Metrics**: The implementation includes performance metrics like the number of backtracks, which provides insight into the efficiency of the algorithm.

### Sudoku
- **Algorithm**: The Sudoku puzzle is solved using a local search algorithm.
- **Local Search**: This approach involves randomly filling the empty cells and iteratively improving the solution by reducing conflicts.
- **Conflict Counting**: A function to count the number of conflicts (row, column, and box conflicts) for a given cell value.
- **Best Number Selection**: For each cell, the algorithm finds the number that minimizes conflicts and updates the cell accordingly.
- **Random Initialization**: The initial state of the Sudoku board is randomly generated with valid numbers.
- **Validation**: Functions are included to validate the Sudoku board for completeness and adherence to the game's rules.

## How to Use
- Clone the repository and navigate to the notebook files.
- Run the Jupyter notebooks to see the implementation and results for Kakuro and Sudoku puzzles.
- The notebooks include detailed comments explaining each step of the process.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Python libraries: `requests`, `itertools`, `random`, `copy`

## Contributing
Contributions to enhance the algorithms or add new puzzle solvers are welcome. Please fork the repository and submit a pull request with your changes.

## License
This project is open-source and available under the MIT License.
