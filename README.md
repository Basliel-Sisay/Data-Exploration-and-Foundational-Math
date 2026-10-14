# Data Exploration and Foundational Math

 <table>
    <tr>
      <th>Name</th>
      <th>ID</th>
    </tr>
    <tr>
      <td>Basliel Sisay</td>
      <td>UGR/3563/16</td>
    </tr>
  </table>

An exploratory data analysis and foundational machine learning laboratory project analyzing student academic performance metrics. This repository demonstrates essential data preprocessing workflows, descriptive statistics, exploratory visualization, correlation analysis, linear algebra principles and feature scaling techniques using Python.

---

## Project Overview

The objective of this project is to take a raw dataset with real world imperfections such as missing inputs, non-physical values and statistical outliers, and transform it into an analysis ready state for predictive modelling.

### Core Modules and Methodology
- **Part A — Inspect and Clean**: Inspect feature shapes and data types. Identify and remove extreme outliers such as impossible study hours, flag invalid entries such as negative attendance and evaluate data distribution to select appropriate imputation techniques between mean and median.
- **Part B — Summarize**: Compute central tendency and dispersion metrics including mean, median, variance and standard deviation across numerical attributes.
- **Part C — Visualize**: Generate distributions and relationship plots to understand feature distributions and detect patterns across variables.
- **Part D — Correlation and Causality**: Compute Pearson correlation coefficients to assess the strength and direction of linear relationships with the target variable, while evaluating the distinction between correlation and causation.
- **Part E — Vectors and Dot Product**: Formulate linear combination score predictions using linear algebra dot products between student feature vectors and assigned weight vectors.
- **Part F — Scaling**: Implement and compare normalization strategies such as standard scaling and min-max scaling to prepare numerical features for gradient-based machine learning algorithms.

---

## Repository Structure

```text
├── .gitignore           # Excludes Jupyter notebook checkpoint directories
├── MLlab.ipynb          # Jupyter notebook containing all implementations and analysis
├── README.md            # Comprehensive project overview and documentation
└── student_data.csv     # Dataset containing student academic records and performance metrics
```

---

## Dataset Schema

The dataset contains records evaluated across four continuous numerical attributes:

| Column | Type | Role | Description |
| :--- | :--- | :--- | :--- |
| `study_hours` | Float | Feature | Average study hours per week including processed edge cases and nulls |
| `attendance` | Float | Feature | Student lecture and session attendance percentage |
| `previous_mark` | Float | Feature | Prior examination and assessment scores |
| `final_score` | Float | Target | Overall final examination performance score |

---

## Getting Started

### Prerequisites

Ensure Python 3.8 or higher is installed along with the required libraries:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### Running the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/Basliel-Sisay/Data-Exploration-and-Foundational-Math.git
   cd Data-Exploration-and-Foundational-Math
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook MLlab.ipynb
   ```

3. Execute the cells sequentially to run the data pipeline and numerical computations.
