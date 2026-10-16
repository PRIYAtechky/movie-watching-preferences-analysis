# 🎬 Movie Watching Preferences Analysis

<p align="center">
  <a href="https://www.kaggle.com/datasets/padmapriya1207/movie-watching-preferences">
    <img src="https://img.shields.io/badge/Kaggle-Dataset-20BEFF?logo=kaggle&logoColor=white" alt="Kaggle Dataset">
  </a>
  <img src="https://img.shields.io/badge/Python-Analysis-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-orange?logo=googlecolab&logoColor=white" alt="Google Colab">
</p>

## Project Overview

This project explores movie-watching preferences and audience behavior using survey data collected from 56 respondents. It examines viewing habits, favorite movie genres, preferred platforms, and the factors that influence movie selection.

The project follows a structured data analysis workflow using Python, including data inspection, data cleaning, exploratory data analysis (EDA), data visualization, and feature engineering.


## 📌Problem Statement

To analyze movie-watching preferences and identify patterns in audience behavior based on age group, viewing frequency, favorite genres, platform preferences, and factors influencing movie selection.

## Project Objectives

- Understand movie-watching habits across different age groups.
- Identify common viewing preferences among respondents.
- Analyze popular movie genres and OTT platforms.
- Explore the reasons influencing audience viewing choices.
- Examine the factors people consider when selecting movies.
- Prepare a clean and analysis-ready dataset.

### Key Features

| Feature | Description |
|---|---|
| `timestamp` | Date and time of survey submission |
| `age_group` | Age group of respondents |
| `movie_frequency` | How often respondents watch movies |
| `viewing_preference` | Preferred movie-viewing option |
| `favorite_genre` | Favorite movie genre |
| `movie_type` | Type of movie respondents enjoy most |
| `ott_platform` | Most-used OTT platform |
| `ott_reason` | Main reason for choosing OTT |
| `theatre_reason` | Main reason for choosing theatre |
| `theatre_frequency` | Frequency of theatre visits |
| `movie_selection_factor` | Main factor influencing movie selection |

##  Tools and Technologies

- **Python** — programming and data analysis.
- **Google Colab** — cloud-based notebook environment.
- **Pandas** — data manipulation and cleaning.
- **NumPy** — numerical operations.
- **Matplotlib** — data visualization.
- **Seaborn** — statistical visualization.
- **Scikit-learn** — categorical encoding and preprocessing when required.
- **GitHub** — project hosting and version control.
- **Kaggle** — dataset hosting.


## 📁 Repository Structure

```text
movie-watching-preferences-analysis/
│
├── data/
│   ├── theatre_vs_ott.csv
│   └── theatre_vs_ott_cleaned.csv
│
├── theatre_vs_ott_analysis.ipynb
├── requirements.txt
└── README.md
```

##  How to Run the Project

### Using Google Colab

1. Open the analysis notebook in Google Colab.
2. Upload the original CSV dataset or connect Google Drive.
3. Install any missing libraries if necessary.
4. Run the notebook cells in sequence.
5. Review the cleaning steps and visualizations.
6. Export the cleaned dataset when the analysis is complete.

### Using GitHub

Clone the repository:

```bash
git clone https://github.com/PRIYAtechky/movie-watching-preferences-analysis.git
```

Navigate to the project folder:

```bash
cd movie-watching-preferences-analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the notebook locally:

```bash
jupyter notebook theatre_vs_ott_analysis.ipynb
```


## Conclusion

This project demonstrates how Python can transform raw survey responses into structured data and meaningful visual insights. Through data cleaning, exploratory analysis, visualization, and feature engineering, the project examines audience movie-watching habits and the factors influencing their preferences. The findings provide a summary of the surveyed audience's behavior and a foundation for further analysis.


Dataset: [Movie Watching Preferences — Kaggle](https://www.kaggle.com/datasets/padmapriya1207/movie-watching-preferences)

---

<p align="center">
  <i>Developed using Python and Google Colab for data analysis and learning.</i>
</p>
