# Pattern Recognition Implementations

This repository contains a implementation algorithm, written in Python. This code does use `scikit-learn`, as it demonstrates building the model from scratch, but it uses libraries for efficiency and convenience in handling arrays and distances.

## Libraries Used

### NumPy

![NumPy Logo](https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg)

- **Purpose**: We use `numpy` for efficient array operations and mathematical calculations.
- **Where Used**:
  - `np.array`: Converts lists to arrays for faster computations.
  - `np.partition`: Finds the smallest distances in `k` nearest neighbors selection.
  - `np.bincount`: Counts occurrences of labels to determine the most common label in the nearest neighbors.
  - `np.sqrt` and `np.sum`: Calculate Euclidean distances in the `calc_distance` function.

### Scikit-learn

![scikit-learn Logo](https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg)

- **Purpose**: If desired, `scikit-learn` can be used to validate our custom KNN model by comparing its predictions to those of the library's KNN model.
- **Where Used**: This project doesn't use `scikit-learn`'s KNN, only use to load dataset and split up the test and train.

## Installation

To install the necessary dependencies:

```bash
pip install numpy
pip install -U scikit-learn
```
