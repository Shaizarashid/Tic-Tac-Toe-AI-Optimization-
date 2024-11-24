# Tic-Tac-Toe-AI-Optimization-
This repository contains Python implementations of algorithms to solve a randomized Tic-Tac-Toe game board. The notebook explores AI techniques like Minimax and Alpha-Beta Pruning for finding optimal moves, comparing their efficiency and performance.

# Results
| Run     | Without Alpha-Beta Pruning (Nodes Evaluated) | With Alpha-Beta Pruning (Nodes Evaluated) |
|---------|---------------------------------------------|-------------------------------------------|
| Run 1   | 10                                          | 7                                         |
| Run 2   | 8                                           | 7                                         |
| Run 3   | 3                                           | 3                                         |
| Average | 7                                           | 5.66                                      |

| Run     | Parallelized Alpha-Beta Pruning (Nodes Evaluated) | Serial Alpha-Beta Pruning (Nodes Evaluated) |
|---------|--------------------------------------------------|---------------------------------------------|
| Run 1   | 12                                               | 7                                           |
| Run 2   | 10                                               | 7                                           |
| Run 3   | 5                                                | 3                                           |
| Average | 9                                                | 5.66                                        |

| Run     | Parallelized Alpha-Beta Pruning (Time Taken) | Serial Alpha-Beta Pruning (Time Taken) |
|---------|---------------------------------------------|-----------------------------------------|
| Run 1   | 0.09 seconds                                | 0.0 seconds                             |
| Run 2   | 9.58 seconds                                | 0.0 seconds                             |
| Run 3   | 8.00 seconds                                | 0.0 seconds                             |
| Average | 5.86 seconds                                | 0.0 seconds                             |

| Run     | **Parallelized Alpha-Beta Pruning** (Time Taken) | **Serial Alpha-Beta Pruning** (Time Taken) |
|---------|-------------------------------------------------|---------------------------------------------|
| Run 1   | 0.09 seconds                                    | 0.0 seconds                                |
| Run 2   | 9.58 seconds                                    | 0.0 seconds                                |
| Run 3   | 8.00 seconds                                    | 0.0 seconds                                |
| **Average** | **5.86 seconds**                              | **0.0 seconds**                            |


| Run     | Alpha-Beta Pruning (Nodes Evaluated) | Enhanced Alpha-Beta Pruning (Nodes Evaluated) |
|---------|-------------------------------------|----------------------------------------------|
| Run 1   | 7                                   | 7                                            |
| Run 2   | 7                                   | 7                                            |
| Run 3   | 3                                   | 3                                            |
| Average | 5.66                                | 5.66                                         |

