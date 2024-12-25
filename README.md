# Dyanmic Hedging--Optimizing Black Scholes Delta hedging using Neural Networks

Developed on Python3.10.16
`python --version` (should output 3.10.16)
Definitely won't work with anything later than 3.10.16 (Pytorch)

FRE 7773 final project

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project delves into dynamic hedging techniques, utilizing neural networks and reinforcement learning to optimize hedging strategies.  
It includes research papers, implementation notebooks, and data related to the subject.

## Project Structure

The repository is organized as follows:

- `Neural_nets/`: Contains implementations and experiments with neural networks for hedging.
- `lit_review/`: Literature reviews and related documents.
- `papers/`: Research papers and reference materials.
- `fin_submission`: Contains our final submissions for our project, including our written report outlining this project
- `FNN_custom.ipynb`: Attempt to implement custom loss function for Neural Network (minimizing "optimal delta hedge" MSE).
- `FNN_residuals.ipynb`: Neural network with loss function being MSE of prediction and target.
- `graphics.ipynb`: Notebook for generating visualizations related to hedging strategies.
- `requirements.txt`: List of dependencies required to run the notebooks.

## Installation

To run the notebooks and experiments, ensure you have Python installed. It's recommended to use a virtual environment.

1. **Clone the repository:**

	```bash
	git clone https://github.com/Thomas101Shen/Dynamic_hedging.git
	cd Dynamic_hedging
	```

2. **Create and activate virtual environment:**
	```
	python -m venv venv
	# On Windows
	venv\Scripts\activate
	# On Unix or MacOS
	source venv/bin/activate
	```
3. **Install dependencies**
	`pip install -r requirements.txt`

4. **Activate jupyter notebook**
	`jupyter notebook`


