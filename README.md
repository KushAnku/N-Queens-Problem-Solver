# N-Queens Problem Solver

This project provides an implementation to solve and analyze the classic **N-Queens Problem**. The problem involves placing `N` queens on an `N x N` chessboard such that no two queens threaten each other. This means that no two queens can be in the same row, column, or diagonal.

## Features

- **Random Configuration Generator**: Generates random initial configurations for the chessboard.
- **Cost Calculation**: Computes the number of conflicts in a given configuration.
- **Textual Visualization**: Displays the board layout in a human-readable format.
- **Extensible Design**: The code can be expanded to include additional algorithms, such as hill climbing, simulated annealing, or genetic algorithms.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Libraries:
  - `numpy`
  - `matplotlib`
  - `math`

Install required libraries using:

```bash
pip install numpy matplotlib
```

### Running the Code

Clone this repository:

```bash
git clone https://github.com/your-username/n-queens-solver.git
cd n-queens-solver
```

Run the script:

```bash
python Singh_Code.py
```

### Example Output

```text
Initial Configuration: [3, 1, 4, 7, 5, 2, 0, 6]
. . . Q . . . .
. Q . . . . . .
. . . . Q . . .
. . . . . . . Q
. . Q . . . . .
. . . . . Q . .
Q . . . . . . .
. . . . . . Q .
Cost of Initial Configuration: 8
```

## Project Structure

- **`Code.ipynb`**: Main Jupyter Notebook with the implementation.
- **`README.md`**: Project documentation.

## Future Enhancements

- Implement optimization algorithms like Hill Climbing and Simulated Annealing.
- Add a GUI for better visualization.
- Benchmark different configurations and optimization methods.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
