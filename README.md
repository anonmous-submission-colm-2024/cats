# Experiment Reproduction Guide

## Acknowledgements

We would like to express our sincerest gratitude to the reviewers for dedicating their time and expertise to reviewing our code and work. 
Your feedback is invaluable in enhancing the quality of our research.

## Reproducing Results

To reproduce the experimental results and figures presented in our work, please follow the steps outlined below. The process has been simplified into a single script to ensure ease of use and to maintain consistency across different environments.

### Prerequisites

Ensure you have the following prerequisites installed:
- Bash shell (Unix/Linux/Mac)
- Required Python packages (listed in `requirements.txt`)
- Set accelerate configuration file based on your environment by running `accelerate config` 

### Steps

1. Open a terminal in the root directory of the project.
2. Run the following command:

```bash
bash reproduction_script.sh [path1] [path2] [path3]
```
`path1` will store the activation histogram for calculating the thresholds. `path2` will store the weights for fine-tuned models. `path3` will store the output figures.