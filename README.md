# Central Tendency Case Study

This Jupyter notebook demonstrates measures of central tendency (mean, median, mode) using a white wine quality dataset. It explores data distributions and creates representative values for quality assessment—perfect for statistics learners or data analysts.[file:1]

## 📋 Overview
- **Dataset**: 4,898 wine samples with 12 features (fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, sulfur dioxides, density, pH, sulphates, alcohol, quality score 3-9).
- **Purpose**: Educational hands-on with Pandas/NumPy for loading data, Seaborn/Matplotlib for visualizations (histograms, distplots), and central tendency calculations.
- **Key Insights**:
  - Mean fixed acidity: ~6.85; median similar, indicating symmetry.
  - Quality mode: 6 (most common score).
  - Distributions vary—some normal, others skewed.

## 📊 Tasks Covered
- **Task 1**: Load "Wine Quality Dataset.csv", inspect shape (4898x12), head, info, columns.
- **Task 2**: Plot feature distributions, compute mean/median/mode.
- **Task 3**: Build "repacid" Pandas Series with representative values.

## 🚀 Quick Start
1. Clone/download the repo.
2. Open `Central_Tendency_Case_Study.ipynb` in Jupyter/Colab.
3. Upload `Wine Quality Dataset.csv` (or download via notebook code).
4. Run cells sequentially—imports: `pandas`, `numpy`, `matplotlib`, `seaborn`.

**Example Output**: Histograms show acidity peaks; quality countplot peaks at 6.

## 🛠️ Tech Stack
- Python 3.x
- Pandas, NumPy (data manipulation)
- Matplotlib, Seaborn (visuals)

## 📈 Results Preview
| Feature          | Mean   | Median | Mode/Notes          |
|------------------|--------|--------|---------------------|
| Fixed Acidity    | 6.85   | 6.8    | Symmetric dist.     |
| Quality          | Varies | Varies | 6 (most frequent)   |
