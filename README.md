# Binary code classification with graph neural networks
This project investigates ways to automate a task common in reverse engineering and malware analysis: function classification (particularly, library code identification).
The code uses the `angr` utility to create control flow and data dependency graphs from binary code. It then creates a classification model using a graph isomorphism network from the PyTorch Geometric library.
More details on the process are found in `Report_Code_Classification.pdf`.
