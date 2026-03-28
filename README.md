# 🎬 Movie Dataset Analysis & Machine Learning

A comprehensive **Data Analysis and Machine Learning project** exploring trends in the movie industry using the TMDb movie dataset.
This project performs **Exploratory Data Analysis (EDA), visualization, and predictive modeling** to understand how factors like **budget, genre, runtime, and popularity influence movie success**.

---

# 📌 Project Overview

The film industry generates billions of dollars every year. Understanding patterns behind successful movies can help studios, producers, and analysts make better decisions.

This project analyzes **10,000+ movies** from the TMDb dataset to uncover insights about:

* Movie release trends
* Budget vs revenue relationships
* Audience preferences
* Genre popularity
* Movie profitability
* Factors influencing movie success

The project also includes a **Machine Learning model to predict movie revenue**, demonstrating how data science can be applied to real-world entertainment industry data.

---

# 📊 Dataset Information

Dataset Used: **TMDb Movie Dataset**

Total Movies: **10,866**

Total Features: **21 columns**

### Important Features in the Dataset

* Movie Title
* Budget
* Revenue
* Genres
* Runtime
* Popularity
* Vote Average (Rating)
* Production Companies
* Release Date
* Director

⚠️ Some dataset columns contain missing values which are cleaned during preprocessing.

---

# ❓ Key Questions Explored

This analysis answers several important questions about the movie industry:

### Movie Trends

1. Which year had the highest number of movie releases?
2. Which month releases the most movies?
3. How has movie production changed over time?

### Movie Profitability

4. Which movie generated the highest profit?
5. Which movie had the lowest profit?
6. Which movies had the highest budgets?
7. Which movies earned the highest revenue?

### Audience Preferences

8. Which movies received the highest ratings?
9. Which runtime duration is most popular among audiences?
10. Do longer movies receive higher ratings?

### Industry Insights

11. Which genres produce the most movies?
12. Which production companies release the most movies?
13. Which directors directed the most films?

### Financial Relationships

14. Is there a relationship between **budget and revenue**?
15. Do higher budgets lead to higher profits?
16. How does runtime affect popularity?

### Advanced Analysis

17. Which genres are the most profitable?
18. Which directors have the highest success rate?

---

# 🧹 Data Cleaning & Preprocessing

Before analysis, the dataset was cleaned and prepared:

* Removed duplicate records
* Handled missing values
* Dropped irrelevant columns
* Converted date formats
* Extracted useful features
* Created new calculated columns

### Feature Engineering

A new feature was created:

**Profit = Revenue − Budget**

This helps analyze which movies were financially successful.

---

# 📈 Exploratory Data Analysis (EDA)

Various visualizations were created to understand patterns in the dataset using **data visualization libraries**.

### Examples of Analysis Performed

* Movies released per year
* Budget vs revenue relationship
* Revenue distribution
* Genre frequency analysis
* Runtime distribution
* Director productivity
* Production company analysis

### Example Visualizations

* 📊 Movie Releases Per Year
* 💰 Budget vs Revenue Scatter Plot
* 🎭 Genre Distribution Chart
* ⏱ Runtime Distribution
* ⭐ Rating Distribution

These visualizations help identify **trends, correlations, and anomalies** within the dataset.

---

# 🤖 Machine Learning Model

To extend the analysis, a **Machine Learning model** was implemented to predict movie revenue.

### Objective

Predict **movie revenue** using features such as:

* Budget
* Runtime
* Popularity
* Vote Average

### Model Used

Linear Regression

### ML Workflow

1. Data preprocessing
2. Feature selection
3. Train-test split
4. Model training
5. Model evaluation

This demonstrates how **data science techniques can be used to forecast movie performance**.

---

# 🛠️ Technologies Used

Programming Language

* Python

Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

Development Environment

* Jupyter Notebook

---

# 🚀 How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/movie-dataset-analysis-ml.git
```

### 2️⃣ Navigate into the folder

```bash
cd movie-dataset-analysis-ml
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Start Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells to reproduce the analysis.

---

# 📊 Key Insights

Some interesting insights discovered during the analysis:

* The number of movies released per year increased significantly after 2000
* Movies with **larger budgets tend to generate higher revenues**
* Certain genres dominate movie production
* Runtime distribution shows most movies are around **90–120 minutes**
* Popularity and budget often influence a movie's financial success

---

# 🔮 Future Improvements

This project can be extended further with:

* Sentiment analysis on movie reviews
* Advanced ML models for revenue prediction
* Deep learning for movie success prediction
* Interactive dashboards using Plotly or Power BI
* Recommendation system for movies

---

# 📌 Conclusion

This project demonstrates how **data analysis and machine learning can uncover valuable insights in the movie industry**.

By analyzing historical movie data, we can better understand the factors that contribute to a movie’s success and apply predictive techniques to forecast future outcomes.

---

# ⭐ Support

If you found this project helpful, consider giving it a **star ⭐ on GitHub**.

It helps others discover the project and supports open-source learning.

---

# 👨‍💻 Author

Rudraksh Tiwari

B.Tech Student | Data Science Enthusiast | Python Developer

---

# 📜 License

This project is open-source and available under the MIT License.

