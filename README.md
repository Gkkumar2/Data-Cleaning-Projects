# Data-Cleaning-Projects

# Project 1
## Highest Career Batting Average in Tests - Data Cleaning & Analysis

![Cricket](https://img.icons8.com/color/96/000000/cricket.png)

A data cleaning and exploratory analysis project focusing on the highest career batting averages in Test cricket. 

## 📁 Dataset  
**Source**: [ESPNcricinfo](https://www.espncricinfo.com/records/highest-career-batting-average-282910)  
**Content**: Player statistics including runs, centuries, strike rate, career span, and more.

---

## 🔧 Data Cleaning Steps  
1. **Renamed Columns**:  
   `HS` → `Highest_Score`, `NO` → `Not_outs`, `BF` → `Balls_Faced`, etc.  
2. **Handled Nulls**: Replaced missing values with `0`.  
3. **Removed Special Characters**: Cleaned `*` from `Highest_Score` and `+` from `Balls_Faced`.  
4. **Dropped Duplicates**: Removed duplicate player entries.  
5. **Split Columns**:  
   - Separated `Span` into `Rookie_year` and `Final_year`.  
   - Extracted `Country` from the `Player` column.  
6. **Data Type Fixes**: Converted columns like `Highest_Score`, `Balls_Faced`, and career years to numeric types.  
7. **Feature Engineering**: Added `Career_Length` (years active).  

---

## 📊 Analysis Questions Explored  
1. What is the average career length of a Test cricketer? **≈13 years**  
2. What is the average batting strike rate for players with >10-year careers? **≈47.74**  
3. How many cricketers retired before 1960? **18 players**  
4. Which country has the highest individual score? **ICC/WI (400 runs)**  
5. Country-wise averages for centuries, half-centuries, and ducks.  

---

## 🛠️ Tools Used  
- **Python Libraries**: Pandas, NumPy  
- **Data Cleaning**: Handling nulls, regex, type conversion  
- **Analysis**: Aggregation, grouping, statistical summaries  

---

## ⚙️ Installation  
```bash
pip install pandas numpy matplotlib
```
---
### Clone this repository.
- Run the Jupyter notebook Cricketdata_cleaning.ipynb.

---

## 🔜 Future Work
Add visualizations (e.g., bar charts for country-wise stats).

Include Project 2 (upcoming).

## 📜 License
MIT
