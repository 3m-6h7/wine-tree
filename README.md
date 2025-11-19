# wine-tree

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A Python project to classify wine samples from the Wine dataset using a Decision Tree classifier with the `entropy` criterion, and visualize the resulting tree.

---

## Table of Contents

- [Description](#description)  
- [Logic of Implementation](#logic-of-implementation)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Description

**wine-tree** is a simple Python project that demonstrates how to classify wine samples using a Decision Tree classifier. It includes data loading, preprocessing, training, evaluation, and tree visualization.

---

## Logic of Implementation

1. **Loading the data**  
   - Dataset loaded using `load_wine` from `sklearn.datasets`.

2. **Converting to Pandas DataFrame**  
   - For efficient analysis and easier handling of features.

3. **Splitting the data**  
   - Train-test split ensures the model is trained and evaluated on separate subsets.

4. **Initialising the classifier**  
   - Decision Tree classifier is initialised with the `entropy` criterion for information gain.

5. **Training the classifier**  
   - Model is trained using `fit`.

6. **Visualising the tree**  
   - Tree plotted with `plot_tree`, including feature and class names, and saved as a PDF.

7. **Evaluating the model**  
   - Accuracy computed by comparing predictions to true labels.

---

## Getting Started

### Prerequisites

- Python 3.8 or later  
- Libraries: `pandas`, `scikit-learn`, `matplotlib`

You can install dependencies using pip:

```bash
pip install pandas scikit-learn matplotlib
```
### Installation

1. Clone the repository:

```bash
git clone https://github.com/3m-6h7/wine-tree.git
```
2. Navigate to the project folder:

```bash
cd wine-tree
```

## Usage

Run the main script to train and visualize the Decision Tree:

```bash
python python-code/wine_tree_classifier.py
```
This will output the accuracy and save a PDF of the decision tree visualisation 

## Project Structure

- `python-code/` — Contains the main Python script for training and visualizing the Decision Tree.  
- `wine_tree.pdf` — Output visualization of the trained tree (generated after running the script).  
- `README.md` — Project documentation.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repo.  
2. Create a new branch: `git checkout -b feature/my-feature`  
3. Make changes and commit: `git commit -am 'Add feature'`  
4. Push to your branch: `git push origin feature/my-feature`  
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


