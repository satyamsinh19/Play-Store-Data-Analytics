<h1 align="center">📱 Play Store Data Analytics</h1>

---

<h2 align="center">🎯 Project Overview</h2>

This project involves analyzing Google Play Store data to generate meaningful insights. The analysis is divided into three distinct tasks:

- **Task 1:** Create a scatter plot to visualize the relationship between revenue and the number of installs for paid apps, with a trendline and color-coding based on app categories.
- **Task 2:** Create a dual-axis chart comparing the average installs and revenue for free vs. paid apps within the top 3 app categories, applying specific filters.
- **Task 3:** Generate a heatmap to visualize the correlation matrix between installs, ratings, and reviews counts, with additional filtering criteria. This task is designed to execute between 3 PM and 6 PM only.

Each task is represented by its own Jupyter notebook, with output visualizations in HTML format.

---

<h2 align="center">🧾 Dataset Used</h2>

- `Play Store Data.csv`

---

<h2 align="center">🎓 Focus</h2>

- **Data Cleaning and Preprocessing**  
- **Data Visualization using Python (Plotly & Matplotlib)**  
- **Generating Data Insights for Business and App Store Strategy**

---

<h2 align="center">📈 Key Tasks</h2>

### ✅ Task 1: Scatter Plot for Paid Apps
**Objective:** Visualize the relationship between revenue and the number of installs for paid apps.

**Features:**
- Trendline to highlight the revenue–install correlation.
- Color-coded data points by app category.
- Interactive HTML output.

**🧠 Insights:**
- A strong positive correlation exists between revenue and installs for paid apps.
- Categories like `PRODUCTIVITY` and `BUSINESS` generate higher revenue with fewer installs, implying higher app prices or niche user base.
- Some high-revenue apps are clustered around relatively low install counts, indicating premium pricing strategies.

---

### ✅ Task 2: Dual-Axis Chart for Free vs Paid Apps
**Objective:** Compare the average installs and revenue for free vs. paid apps within the **top 3 app categories**.

**Filters Applied:**
- Install count ≥ 10,000  
- Revenue ≥ $10,000  
- Android Version > 4.0  
- App Size > 15MB  
- Content Rating = Everyone  
- App Name ≤ 30 characters

**🧠 Insights:**
- Free apps consistently outperform paid apps in terms of install count across all three top categories.
- Paid apps show significantly higher revenue per install, especially in the `PRODUCTIVITY` and `TOOLS` categories.
- Indicates a volume vs. value contrast: Free apps chase user base, while paid apps focus on monetization efficiency.

---

### ✅ Task 3: Correlation Heatmap
**Objective:** Generate a heatmap showing the correlation between installs, ratings, and reviews.

**Filters Applied:**
- Apps updated within the last year.  
- Minimum 100,000 installs and >1,000 reviews.  
- Genres **not** starting with A, F, E, G, I, K.  
- Execution window: **3 PM to 6 PM only**

**🧠 Insights:**
- Strong positive correlation between **installs** and **reviews** — more downloads lead to more user feedback.
- Ratings are only weakly correlated with reviews or installs, indicating that rating scores remain stable regardless of volume.
- Suggests that while install/review volumes are scalable, user satisfaction (ratings) depends more on app quality than popularity.

---

<h2 align="center">🛠 Tools & Technologies</h2>

- Python (Jupyter Notebooks)  
- Pandas  
- Plotly  
- Matplotlib  
- NumPy

---

<h2 align="center">📂 Repository Structure</h2>

| File                              | Description                                      |
|---------------------------------- |--------------------------------------------------|
| Task 1.html                       | Output of Task 1 - Scatter plot for paid apps    |
| Task 2.html                       | Output of Task 2 - Dual-axis chart comparison    |
| Task 3.html                       | Output of Task 3 - Correlation heatmap           |
| Play Store Data.csv               | Raw dataset used for the analysis                |
| Task 1.ipynb                      | Jupyter notebook for Task 1 analysis             |
| Task 2.ipynb                      | Jupyter notebook for Task 2 analysis             |
| Task 3.ipynb                      | Jupyter notebook for Task 3 analysis             |
| README.md                         | Project documentation (this file)                |

---

<h2 align="center">🎓 Learning Highlights</h2>

- 🧹 Gained hands-on experience with **data cleaning and preprocessing** using Pandas.  
- 📊 Built **interactive, dynamic charts** using Plotly and Matplotlib.  
- 🧠 Improved skills in drawing **business-relevant insights** from raw app data.  
- 🧵 Practiced advanced filtering, correlation analysis, and storytelling with data.  
- 📦 Learned how to structure a data analytics project for real-world deployment.

---

<h2 align="center">🔗 Connect with Me</h2>

**Satyam Kumar**  
🌐 [LinkedIn](https://linkedin.com/in/yourprofile)  
📬 Email: [satyamkv123@gmail.com](mailto:satyamkv123@gmail.com)

---

