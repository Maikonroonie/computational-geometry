# Computational Geometry 
## Computer Science | AGH University of Krakow

![Python](https://img.shields.io/badge/python-3.13+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)

## Project Description

This repository contains implementations and analysis of algorithms covered in the **Computational Geometry** course at AGH University of Krakow. The project focuses on fundamental geometric algorithms, spatial data structures, and problem-solving methods, emphasizing algorithmic complexity and numerical stability.

The laboratory resources, including template notebooks, visualizers, and tests, were originally provided by the [BIT Scientific Group](https://github.com/aghbit/Algorytmy-Geometryczne).

<p align="center">
  <img src="https://github.com/user-attachments/assets/5e72ac8b-eca9-4fcf-b061-95cdc59edd9f" alt="Algorithm Visualization" width="600"/>
  <br>
  <i>Visualization of the Sweep Line Algorithm</i>
</p>

## Table of Contents

| Module | Topic | Description | Link |
|:---:|---|---|:---:|
| **Lab 1** | **Geometric Predicates** | Implementation of robust geometric predicates to handle floating-point arithmetic errors and ensure stability. | [Jupyter Notebook](lab1/code_lab1.ipynb) |
| **Lab 2** | **Convex Hull** | Construction of Convex Hulls using **Graham Scan** and **Jarvis March** algorithms. | [Jupyter Notebook](lab2/code_lab2.ipynb) |
| **Lab 3** | **Triangulation** | Algorithms for **Monotonic Polygon Triangulation** and polygon partitioning. | [Jupyter Notebook](lab3/code_lab3.ipynb) |
| **Lab 4** | **Line Intersection** | Efficient intersection detection using the **Sweep Line Algorithm** (Bentley-Ottmann). | [Jupyter Notebook](lab4/code_lab4.ipynb) |
| **Project** | **Range Searching** | Implementation of **KD-Trees** and **QuadTrees** for efficient Orthogonal Range Searching. | [Jupyter Notebook](project/main.ipynb) |

---

## Prerequisites

To run the notebooks, you need:
- **Python 3.13** or higher
- `pip` (Python package installer)
- `git`

## Setup Instructions

Follow these steps to set up the environment locally:

### 1. Clone the repository
```bash
git clone [https://github.com/Maikonroonie/computational-geometry.git](https://github.com/Maikonroonie/computational-geometry.git)
cd computational-geometry
```

### 2. Create a virtual environment (Recommended)
It is best practice to use a virtual environment to manage dependencies.

Windows:
```bash
python -m venv .venv
.venv\Scripts\activate
```
macOS / Linux:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies
Install all required libraries (matplotlib, numpy, etc.) using pip:
```bash
pip install -r requirements.txt
```

### Running the Project
# Executing Jupyter Notebooks
1. Ensure your virtual environment is active.
2. Start the Jupyter Notebook server:
```bash
jupyter notebook
```
3. Your browser should open automatically. Navigate to the labs/ or project/ directory and open the .ipynb file you wish to explore.














