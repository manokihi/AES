The assignment solutions are contained in Jupyter/Colab notebooks (*.ipynb). For each notebook, there is also a Python source
file (*.py). The solutions solve the Checkerboard Classification problem using a Neural Network (NN). The solutions start by
solving the smallest non-trivial example of 2x2 squares, k=1 and proceed with k=2, k=3, and k=4 for 8x8 (64 squares).

I chose to retain a separate notebook for each different sized board to preserve the output data, which consists of
training output for a large number of epochs. The output also contains a Decision Boundary Plot visualization.
The training runs are summarized below:

Board Size  k  Sample Size  Hidden Size  lr    epochs
----------  -  -----------  -----------  ---   ------
2x2         1  3000          64          0.10   30000
4x4         2  4000          64          0.10   40000
6x6         3  4000          64          0.05  100000
8x8         4  5000          64          0.05  150000
