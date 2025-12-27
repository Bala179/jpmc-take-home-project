# JPMC Applied AI/ML Associate Take-Home Project

This repository contains my submission to the take-home project for the Applied AI/ML Associate role at JP Morgan. My report can be viewed [here](https://github.com/Bala179/jpmc-take-home-project/blob/main/jpmc-project-report.pdf).

## Setup
1. Clone the repository and change to the repository directory:
   ```bash
   git clone https://github.com/Bala179/jpmc-take-home-project.git
   cd jpmc-take-home-project
   ```
2. Create and activate a new virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate     # For Linux and MacOS
   venv/scripts/activate        # For Windows
   ```
3. Install the required packages, along with `ipykernel`:
   ```bash
   pip install -r requirements.txt
   python -m ipykernel install --user --name venv --display-name "Python (venv)"
   ```
4. Using this new kernel, run the code at `code/main.ipynb`.
