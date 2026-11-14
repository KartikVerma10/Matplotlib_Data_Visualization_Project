# Matplotlib Data Visualization Project

A practical collection of data visualization examples built with Matplotlib and Pandas. 

This repository uses a sample Amazon product dataset to show how to structure, style, and clean up different types of plots. It includes reusable code for handling common layout issues (like overplotting) and applying global font styling for a clean, consistent, and professional look. It's designed to be a quick reference guide for anyone looking to step up their Matplotlib game.

## 📊 Visualizations Included

The main Jupyter Notebook (`Matplotlib_Data_Visualization_Project.ipynb`) covers the following techniques:

1. **Time Series with Annotations:** Simulated daily sales trends featuring 7-day rolling averages, linear trend fitting, and dynamic min/max callouts.
2. **Violin Plots:** Visualizing the probability density, medians, and ranges of discount percentages and customer ratings across top categories.
3. **Scatter Plots with Regression:** Plotting actual vs. discounted prices with per-category linear regression trend lines and slope annotations.
4. **Histograms with Smoothed KDE:** Rating distributions overlaid with smoothed Kernel Density Estimation curves using Gaussian filtering.
5. **Boxplots with Jittered Scatter:** A hybrid approach combining statistical quartiles with raw, jittered data points to prevent overlap and reveal exact distributions.
6. **Hexbin Density Maps:** A 2D histogram approach to solve overplotting in dense scatter data (Actual vs. Discounted Price).
7. **Radar (Spider) Charts:** Comparing normalized multivariate profiles (prices, discounts, ratings) across different product categories on a polar axis.

## 🛠️ Tech Stack

* **Python 3**
* **Pandas:** Data ingestion, string cleaning, and aggregation.
* **NumPy:** Mathematical operations and trend line calculations.
* **Matplotlib:** Core plotting, subplots, and global parameter styling (`plt.rcParams`).
* **SciPy:** Gaussian filtering (`gaussian_filter1d`) for KDEs.

## 📂 Dataset

This project utilizes an `amazon.csv` dataset containing product details, pricing, ratings, and categories. The notebook includes a preprocessing block that cleans string-based currency symbols (₹) and percentages into usable numerical floats.

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with Jupyter Notebook or JupyterLab.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Matplotlib_Data_Visualization_Project.git
   cd Matplotlib_Data_Visualization_Project
   ```
2. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib scipy jupyter
   ```
3. Ensure the `amazon.csv` file is in the root directory of the project.

### Usage
Launch Jupyter Notebook to view and run the project:
```bash
jupyter notebook
```
Open `Matplotlib_Data_Visualization_Project.ipynb` and run the cells sequentially to generate the output images in the automatically created `amazon_outputs` folder.


## **Kartik Verma**

**Engineering Student | Machine Learning Enthusiast**

- 💻 Python Developer
- 🤖 Machine Learning Enthusiast

### GitHub

https://github.com/KartikVerma10

### LinkedIn

https://www.linkedin.com/in/kartik-verma-47252532a 
---

# ⭐ Support

If you found this project useful, please consider giving this repository a **⭐ Star**.

Your support motivates me to continue learning, building, and sharing more Machine Learning and AI projects.

**Happy Coding! 🚀**
