# Exploratory Data Analysis of IPL Matches(2008-2024)

## 📌 Overview
The **Indian Premier League (IPL)** is India’s premier professional T20 cricket league, where city-based teams compete in high-intensity matches lasting about three hours.  

This dataset spans **13 years of IPL history (2008–2024)** and contains rich details about matches, players, teams, and results.  
It provides an excellent foundation to analyze cricket performance, uncover patterns, and explore factors that influence match outcomes.

---

## 📂 Dataset Description
The dataset includes two CSV files:

- **`deliveries.csv`** → Ball-by-ball details of every IPL match  
- **`matches.csv`** → Match-level summaries (teams, venues, winners, etc.)

---

## 🎯 Objectives
With this dataset, we aim to:

- 📊 Examine **team performances** over the seasons  
- 👤 Analyze **player statistics** and consistency  
- 🏆 Study **match outcomes** and winning factors  
- 📈 Explore **seasonal trends** across IPL history

---

## 🧰 Tools & Technologies
- **Programming Language:** Python  
- **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook / VS Code  
- **Dataset:** IPL matches and deliveries dataset (Kaggle)

---

## ⚙️ Data Cleaning & Preparation
- Removed null values and corrected inconsistent team names.  
- Converted Data Types to improve analysis efficiency and enable time-series analysis.  
- Filtered out incomplete or abandoned matches.

---

## 📊 Exploratory Data Analysis (EDA)
Key analyses performed:
- **Total Matches Played**.  
- **Matches Per Season**.
- **Total Teams**.
- **Most Wins** and **Top Venues**.
- **Team-wise Performance Per Season**.
- **Toss Winner vs Match Winner**.
- **Most wins by teams at each venue**
- **Top Scorers**
- **Player of the match**

---


### 📌 Inferences and Conclusion  

After conducting Exploratory Data Analysis (EDA) on the IPL dataset (2008–2024), the following key findings emerged:

---

#### 🔢 General Statistics
- The dataset covers **260,920 deliveries** across **14 seasons** and involves **14 different teams**.  
- The **number of matches per season** has steadily grown, reflecting the tournament’s rising popularity and expansion.  

---

#### 🏆 Performance Highlights
- **Mumbai Indians (MI)** stand out as the **most successful team**, with the highest number of wins.  
- Venues such as **Wankhede Stadium** have hosted the **largest share of matches**, cementing their place as iconic IPL grounds.  
- **AB de Villiers** has earned the **most Player of the Match awards**, underlining his game-changing ability.  
- **Virat Kohli** ranks as the **leading run-scorer** in IPL history.  
- **Chris Gayle** holds the record for the **most sixes**, showcasing the explosive nature of T20 batting.  

---

#### 📍 Venue-based Insights
- Teams like **Chennai Super Kings (CSK)** and **Mumbai Indians (MI)** have excelled at their **home venues**, suggesting a strong **home-ground advantage**.  

---

#### 🧠 Key Questions Explored
- **Does home-ground advantage matter?**  
  ✅ Yes. Teams generally perform better at home, likely due to pitch familiarity and crowd support.  

- **How many super overs have occurred?**  
  ➡️ A total of **9 super overs**, highlighting the competitiveness of close matches.  

- **What is the average scoring rate per over?**  
  ➡️ Run rates differ across match phases:  
    - **Powerplay (1–6 overs):** Fast but calculated  
    - **Middle overs (7–15):** Moderate pace  
    - **Death overs (16–20):** Peak scoring with aggressive hitting  

---

#### 📈 Trends Over Seasons
- Team performance has been **cyclical**, with some franchises dominating for a few years before declining.  
- Winning the **toss** does not ensure victory, but it often shapes **strategic choices** such as batting or bowling first.  

---

✅ Overall, the IPL has evolved into one of the **most competitive and dynamic cricket leagues globally**, with iconic players, teams, and venues shaping its legacy. 
