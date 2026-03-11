# DAS-Group-08: Movie Data Analysis Project

## 📝 Project Overview
This repository contains the collaborative data analysis for **Group 08** as part of the **STATS5085 Data Analysis Skills** course. 

### Research Question
**"Which properties of films (such as release year, duration, budget, genre, or popularity) influence whether they are rated by IMDB as greater than 7 or not?"**

To answer this, we utilize a **Generalized Linear Model (GLM)**, specifically **Logistic Regression**, to analyze the factors affecting high film ratings.

---

## 👥 Group Members
| Name | Student ID | GitHub Username |
| :--- | :--- | :--- |
| [Rui Xu] | [3091749X] | [XuRui12110] |
| [Zhenzi Wang] | [3044756W] | [Cecilia-wangzz] |
| [Zhiyao Wang] | [3088880W] | [CamileWang] |
| [Ziyang Wang] | [3075362W] | [Xuexiaoban12138] |
| [Lixing Liu] | [2996645L] | [ArashiLlx] |

---

## 📂 Repository Structure
- `Group_08_Analysis.qmd`: Main Quarto file containing all R code and analysis.
- `dataset08.csv`: The raw movie dataset (Year, Length, Budget, Genre, Rating, etc.).
- `Group_08_Presentation.pdf`: Final presentation slides summarising our findings.
- `README.md`: This documentation file.

---

## 🛠️ Data Description
The dataset `dataset08.csv` includes:
- **year**: Release year of the movie.
- **length**: Duration in minutes.
- **budget**: Production budget.
- **votes**: Number of user votes.
- **genre**: Primary category (Action, Comedy, Drama, etc.).
- **rating**: Average user rating.
- **Target Variable**: A binary indicator (1 if Rating > 7, 0 otherwise).
---

## 💻 Collaborative Workflow
- **Branching**: Individual analysis is performed on feature branches before merging to `main`.
- **Pull Requests**: All merges require a review and approval from at least one group member.
- **Commits**: Meaningful messages (e.g., "Add Logistic Regression model for Rating > 7").
- **Reproducibility**: The `.qmd` file renders the complete analysis from the raw CSV.

---

## 🚀 How to Render
1. Open `Group_08_Analysis.qmd` in RStudio.
2. Ensure `tidyverse` and `ggplot2` are installed.
3. Click **Render** to generate the analysis report.


