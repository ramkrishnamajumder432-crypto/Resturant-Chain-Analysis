# Restaurant Chain Analysis

## Project Overview
This project explores restaurant data to understand restaurant distribution, ratings, pricing, cuisines, customer reviews, and location-based patterns. The analysis is organized into three Jupyter notebooks corresponding to Cognifyz internship Level 1, Level 2, and Level 3 tasks.

## Project Files
- `cognifyz intern-LEVEL1.ipynb` — Level 1 analysis tasks.
- `cognifyz intern-LEVEL 2.ipynb` — Level 2 analysis tasks.
- `cognifyz intern-LEVEL 3.ipynb` — Level 3 analysis, including restaurant reviews.
- `Dataset .csv` — Dataset used by the notebooks.

## Tools and Libraries
- Python
- Jupyter Notebook
- Pandas — data loading, cleaning, and manipulation
- NumPy — numerical operations
- Matplotlib and Seaborn — data visualization
- Plotly Express — interactive visualizations
- Folium — geographic visualization and mapping

## Getting Started

### 1. Download or clone the repository
```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

### 2. Create and activate a virtual environment (optional)
On Linux/macOS:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

On Windows:
```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install the required libraries
```bash
pip install pandas numpy matplotlib seaborn plotly folium jupyter
```

### 4. Start Jupyter Notebook
```bash
jupyter notebook
```

Open one of the notebooks and run the cells in order. Keep `Dataset .csv` in the same directory as the notebooks, because the notebooks load it using a relative file path.

## Analysis Workflow
1. Load the restaurant dataset with Pandas.
2. Inspect the data and check for missing values.
3. Clean text fields such as restaurant names, cities, addresses, and localities.
4. Handle missing records as implemented in the notebooks.
5. Explore the dataset and create visualizations.
6. Review the results from the Level 1, Level 2, and Level 3 notebooks.

## Notes
- Run the notebooks from the project directory so the CSV file can be found.
- The notebooks may modify or remove missing-value rows during cleaning. Review those cells before applying the same process to other datasets.
- Add screenshots of your own notebook outputs or charts here if you want to showcase results on GitHub.

## Author
**Ramkrishna Majumder**

Restaurant Chain Analysis project by Ramkrishna Majumder.
