🎬 Netflix Data Analysis Project

 📊 Overview
This project focuses on analyzing Netflix dataset using Python. The goal was to clean, transform, and analyze the data to extract meaningful insights about movies, ratings, and genres.

---

 🔧 Tools & Technologies Used
- Python 🐍
- Pandas
- Matplotlib
- Google Colab

---

 🧹 Data Cleaning
- Removed unnecessary columns (Overview, Poster_Url, etc.)
- Handled missing values
- Converted data types (e.g., Genre to category)

---

 ⚙️ Feature Engineering
- Split multiple genres using `.str.split()`
- Used `.explode()` to separate genres into rows
- Categorized ratings using `pd.cut()`

---

 📊 Exploratory Data Analysis (EDA)
- Analyzed rating distribution
- Identified most popular genres
- Checked vote count and popularity trends

---

 📈 Key Insights
- Most movies fall in the average rating category (6–7)
- Popular genres include Drama and Action
- Movies with higher vote count tend to have better ratings

---

 📌 Conclusion
This project helped in understanding how to clean and analyze real-world datasets and extract meaningful insights using Python.

---

 📁 Project File
- Netflix_Data_Analysis_Project.ipynb
