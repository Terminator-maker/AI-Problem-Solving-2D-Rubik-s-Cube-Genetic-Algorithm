# 🧬 AI Problem Solving: 2D Rubik's Cube & Genetic Algorithm

This repository contains solutions for two classic Artificial Intelligence problems, implemented as part of the AI course at the **University of Science and Culture** under the supervision of Dr. Azadeh Tabatabaei.

---

## 🧩 Project Breakdown

### 1. 2D Rubik's Cube Solver (Heuristic Search)
* **Problem Description:** A 2D Rubik's cube grid with randomly arranged numbers that must be sorted in ascending order using the minimum number of cyclic row or column shifts[cite: 16].
* **Approach & Implementation:** 
  * Utilized a double-ended queue (`deque`) to manage states efficiently[cite: 19].
  * Implemented and compared two heuristic functions[cite: 18]:
    1. Counting the number of unsorted rows.
    2. Calculating the sum of Manhattan distances for each element to its correct target position.

### 2. Linear Equation Optimization (Genetic Algorithm)
* **Problem Description:** Optimizing the weight coefficients ($w$) of a linear equation ($y = w_1x_1 + w_2x_2 + w_3x_3 + w_4x_4$) to maximize the output $y$ towards a target value[cite: 17, 20].
* **Approach & Implementation:**
  * **Population & Fitness:** Generated initial random population and evaluated solutions using a customized fitness function[cite: 20].
  * **Evolution Operators:** Implemented parent selection, crossover (gene recombination), and mutation (with probability adjustments)[cite: 20, 21].
  * **Visualization:** Tracked performance across iterations and generated comparative charts using `Matplotlib` and `Pandas`[cite: 18, 23].

---

## 🛠️ Tech Stack
* **Python**
* **NumPy & Pandas** (Data manipulation and structuring)
* **Matplotlib** (Algorithm performance and iteration plotting)
* **Collections (deque)** (State graph traversal)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/Terminator-maker/AI-Problem-Solving-2D-Rubik-s-Cube-Genetic-Algorithm.git](https://github.com/Terminator-maker/AI-Problem-Solving-2D-Rubik-s-Cube-Genetic-Algorithm.git)
   cd AI-Problem-Solving-2D-Rubik-s-Cube-Genetic-Algorithm
Install dependencies:

Bash
pip install -r requirements.txt
Run the scripts or Jupyter Notebooks included in the repository.
files:
1.Document (format: pdf)
2.Code - PDF - Google Colab
3.Code - py
4.Code - ipynb Format

Workspace:
Google Colab (https://colab.google/)

Google Colab project link: 
https://colab.research.google.com/drive/163IhUU8rGzyz1x7laQbn9u0jj4rSSsVl?usp=sharing

written in python 3.10.12
