# Federated-learning-on-Clustered-Sampling-using-MNIST-dataset
## Overview
This project explores clustering and sampling techniques applied to the MNIST dataset. The goal is to analyze and compare the performance of two clustered sampling methods and a random sampling method. The project uses a variety of metrics, such as loss, accuracy, and the number of clients sampled in each round, to evaluate the effectiveness of the different approaches.

## Code Structure
- `main_code.py`: Main script containing the implementation of the clustering and sampling methods. Here the `main_code.py` refers to `clustered-sampling-results-visualization.ipynb`.
- `utils.py`: Utility functions used in the main code. Here `utils.py` refers to `clustered-sampling-mnist-csv-dataset.ipynb`.
- `exp1/`: Directory containing experimental data and results.

## Prerequisites
Make sure you have the necessary dependencies installed. You can install them using:

```bash
pip install numpy matplotlib pickle kaggle
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repository.git
   cd your-repository
   ```

2. Run the main code:
   ```bash
   python main_code.py
   ```

3. View the results in the `exp1/` directory.

## Experimental Results
The project includes visualizations of various metrics, such as mean loss, standard deviation of loss, mean accuracy, standard deviation of accuracy, and the number of clients sampled in each round. These visualizations provide insights into the performance of different sampling methods.
