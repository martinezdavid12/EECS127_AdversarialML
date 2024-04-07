# Neural Network Robustness using Non-Convex Optimization for Adversarial Machine Learning

## Overview
In this project, we explore how to make neural net classifiers robust by framing them as a non-convex optimization problem, then using the techniques learned in this class to prove their robustness. In particular, we will follow a technique developed by Wong and Kolter [1].

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Approach](#approach)
- [Contributers](#contributers)
- [License](#license)

## Installation
To run this project, you'll need Python and the following libraries installed:
- NumPy
- Pytorch
- Matplotlib
- Conda
- (Optional) CUDA and a CUDA-compatible GPU

Clone this repository to your local machine using Git:
```
git clone https://github.com/martinezdavid12/EECS127_AdversarialML.git
```

Navigate to the project directory and install the required dependencies:
```
cd EECS127_AdversarialML
pip install -r requirements.txt
```

## Usage - (to be implemented later)
After installing the dependencies, you can run the project using the provided Python scripts. Follow the instructions below:

1. Preprocess the dataset:
```
python preprocess.py --input dataset.csv --output processed_dataset.csv
```

2. Train the neural network:
```
python train.py --data processed_dataset.csv --epochs 100 --batch-size 32
```

3. Evaluate the model:
```
python evaluate.py --model trained_model.h5 --test-data test_dataset.csv
```

## Approach
We will follow the approach developed by Wong and Kolter [1] to make neural net classifiers robust. This involves framing neural networks as non-convex optimization problems and applying techniques from EECS127 to prove their robustness.
**Project Spec:**https://eecs127.github.io/assets/proj/proj_adversarial_prob.pdf

## Contributers
"Authors"

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
