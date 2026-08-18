# IMDB-Project
# 🎬 IMDB Movie Data Analysis

### Artificial Intelligence Minor Project

---

## 📌 About the Project

This project explores the **IMDB Movie Dataset** using Python-based data analysis and visualization techniques.

The objective is to extract useful information from movie data and identify patterns related to **ratings, genres, directors, release years, runtime, and revenue**.

The project also extends the original analysis by implementing additional queries, comparisons, and visualizations using Python.

---

## 🎯 What This Project Does

The analysis focuses on answering questions such as:

* Which movies have the highest IMDb ratings?
* What are the highest-rated Comedy movies?
* Which genres are most common?
* Which genres have the highest average ratings?
* How has movie production changed over the years?
* Which directors have the highest average ratings?
* Is there a relationship between movie ratings and revenue?
* Which movies have the longest runtimes?
* Which movies perform well in both ratings and revenue?

---

## 🔎 Analysis Modules

### ⭐ Movie Rating Analysis

Identifies the highest-rated movies in the dataset and ranks them according to their IMDb ratings.

### 🎭 Genre Analysis

Examines the distribution of movie genres and compares their average ratings.

### 🎥 Director Analysis

Evaluates directors based on the average ratings of their movies.

### 📅 Year-wise Analysis

Studies the number of movies released across different years.

### 💰 Revenue Analysis

Explores movie revenue and compares it with IMDb ratings.

### ⏱️ Runtime Analysis

Identifies the longest movies and investigates whether runtime is related to ratings.

### 🏆 Performance Analysis

Finds movies that achieve both high IMDb ratings and high revenue.

---

## 📊 Visualizations

The project uses different types of visualizations to make the analysis easier to understand:

* Bar Charts
* Horizontal Bar Charts
* Line Charts
* Scatter Plots
* Genre Distribution Charts

Each visualization is accompanied by the corresponding Python analysis.

---

## 🧰 Tools & Technologies

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Data analysis             |
| Pandas           | Data manipulation         |
| NumPy            | Numerical operations      |
| Matplotlib       | Data visualization        |
| Seaborn          | Statistical visualization |
| Google Colab     | Development environment   |
| Jupyter Notebook | Project implementation    |

---

## 📂 Dataset

The project uses the **IMDB Movie Dataset** supplied with the original project.

The dataset contains movie-related information including:

* Movie title
* Genre
* IMDb rating
* Director
* Actors
* Release year
* Runtime
* Revenue

---

## ▶️ Running the Project

### Google Colab

1. Open the `.ipynb` notebook in Google Colab.
2. Upload the `IMDB-Movie-Data.csv` file.
3. Make sure the dataset path is correctly specified.
4. Run the notebook cells sequentially.
5. Review the generated tables, calculations, and visualizations.

Example dataset loading code:

```python
import pandas as pd

data = pd.read_csv('/content/IMDB-Movie-Data.csv')

data.head()
```

---

## 📁 Repository Structure

```text
IMDB-Movie-Data-Analysis/
│
├── IMDB_Movie_Analysis.ipynb
│
├── IMDB-Movie-Data.csv
│
├── IMDB_Project_Report.pdf
│
└── README.md
```

---

## 📈 Project Output

The notebook generates:

* Ranked movie lists
* Genre statistics
* Director statistics
* Year-wise movie statistics
* Rating comparisons
* Revenue comparisons
* Runtime analysis
* Data visualizations

The results are generated directly from the dataset using Python.

---

## 💡 Key Learning Outcomes

Through this project, the following concepts are demonstrated:

* Loading datasets using Pandas
* Data filtering and sorting
* Handling categorical data
* Grouping and aggregation
* Working with missing values
* Statistical calculations
* Data visualization
* Extracting insights from datasets
* Writing reusable Python functions

---

## 🚀 Possible Future Enhancements

The project can be extended by:

* Creating an interactive dashboard
* Building a machine-learning-based rating prediction model
* Developing a more advanced movie recommendation system
* Adding additional movie datasets
* Creating a web interface for movie recommendations

---

## 👨‍💻 Author

**Aayush Sharma**

Artificial Intelligence Minor Project
BCA

---

## 📄 Project Status

**Completed**

The repository contains the Python notebook, dataset, analysis, visualizations, and project documentation required for the project submission.
