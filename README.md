# 🎥 IMDb Movies Analysis

## 📌 Overview
This project provides an in-depth analysis of the **IMDb Top 1000 Movies dataset**, exploring trends, patterns, and relationships among movie attributes. Data visualizations and exploratory data analysis (EDA) techniques have been used to uncover insights into IMDb ratings, genres, gross earnings, runtime, and sentiment from movie overviews.

The project demonstrates data cleaning, data visualizations, and insightful conclusions, making it a valuable resource for understanding what factors contribute to a movie's success.

---

## 📊 Key Features
- **IMDb Ratings Distribution**: Visual analysis of how ratings are distributed among the top 1000 movies.
- **Genre Analysis**: Identify the most common genres and their overlaps using heatmaps.
- **Year-Wise Trends**:
  - Trends in movie releases and average IMDb ratings over the years.
- **Gross Earnings Analysis**:
  - Relationship between gross earnings, runtime, and the number of votes, with a 3D scatter plot.
- **Director and Actor Impact**:
  - Top-rated directors and collaborations among stars using network graphs.
- **Sentiment Analysis**:
  - Explore the relationship between IMDb ratings and sentiment polarity in movie overviews.

---

## 🗂️ Dataset
- **Source**: [IMDb Top 1000 Movies Dataset](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-top-1000-movies)
- **Columns**:
  - `Series_Title`: Movie title.
  - `Released_Year`: Year of release.
  - `IMDB_Rating`: IMDb rating of the movie.
  - `Runtime`: Runtime in minutes.
  - `Genre`: Movie genres.
  - `Director`: Movie director(s).
  - `Star1, Star2, Star3, Star4`: Lead actors.
  - `Gross`: Total gross earnings (in USD).
  - `No_of_Votes`: Total votes received.
  - `Overview`: Short description of the movie.

---

## 📈 Visualizations
### Example Insights:
1. **IMDB Ratings Distribution**:
   - Most ratings fall between 7 and 9, with a sharp decline below 7.
2. **Genre Heatmap**:
   - Significant overlaps between genres like Drama, Action, and Adventure.
3. **3D Scatter Plot**:
   - Higher gross earnings are correlated with a larger number of votes and longer runtimes.
4. **Collaboration Network**:
   - Visual representation of frequent partnerships among top actors.

---

## 🔧 Setup and Usage

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `networkx`, `textblob`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/disha-karmakar/IMDb_Movies_Analysis.git
   cd IMDb_Movies_Analysis
2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook IMDb_Analysis.ipynb
## Files
- **IMDb_Analysis.ipynb:** The main notebook containing all the analysis and visualizations.
- **imdb_top_1000.csv:** The dataset used for the analysis.
---
## 🤝 Contributing
Contributions are welcome! If you'd like to add new features, improve visualizations, or optimize the analysis:
1. Fork the repository.
2. Create a new branch (git checkout -b feature-name).
3. Commit your changes (git commit -m 'Add feature').
4. Push to the branch (git push origin feature-name).
5. Create a pull request.
---
## 📄 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


