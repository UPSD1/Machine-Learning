# Flaky Test Detector for ML Libraries

This project implements a tool to detect and analyze flaky tests in Machine Learning libraries, with a focus on approximate assertions.

## Features

1. Detects approximate assertions in Python test files
2. Generates a CSV report of all found assertions
3. Runs selected tests multiple times to check for flakiness

## Requirements

- Python 3.7+
- pytest
- Libraries being analyzed (cleverhans, allennlp, gpytorch, sonnet)

## Installation

1. Clone this repository
2. Install the ML libraries to be analyzed: cleverhans allennlp gpytorch dm-sonnet

## Usage

### 1. Detecting Approximate Assertions

Run the flaky_test_detector.py script

When prompted, enter the path to the Python project you want to analyze.

### 2. Analyzing Test Flakiness

After generating the assertions CSV, run the test runner script

When prompted, enter the path to the assertions CSV file generated in step 1.

## Output

- `[project_name]_assertions.csv`: Contains all detected approximate assertions
- `[project_name]_test_results.csv`: Contains the results of running selected tests multiple times


## Contact

Project Link: [(https://github.coecis.cornell.edu/daa238/CS6158.git)]
