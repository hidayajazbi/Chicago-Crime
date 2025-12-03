# Chicago Violent Crime Analysis (2015–2020)

### By: Hidaya Jazbi & Mohammad Albarabrah  
### Course: Programming / Data Analysis Project  
### Dataset: Chicago Violent Crime (2015–2020)

---

## 📌 Project Overview
This project analyzes violent crime trends in Chicago from **2015 to 2020** using Python and a real dataset containing **70,748** crime records.  
The dataset includes information about:

- Crime type (Robbery, Homicide, Criminal Sexual Assault, Kidnapping)
- Date of the crime
- Arrest status (True/False)
- Geographic coordinates (latitude/longitude)
- Descriptions
- Year and month extracted from dates

Our goal was to answer **business-style analytical questions** using Python, data cleaning, aggregation, and visualization.

---

## Business / Research Questions

We answered the following five questions in our Jupyter Notebook:

1. **How has the total number of violent crime incidents changed from 2015 to 2020?**  
2. **Which types of violent crimes are most common overall?**  
3. **How do arrest rates differ by crime type?**  
4. **Are there any seasonal patterns in violent crime across the months?**  
5. **Which year had the highest arrest rate for violent crimes?**

Each question includes:
- Python code  
- Bar charts  
- Clear written explanations  
- Insights based on the dataset  

---

## Data Cleaning & Preparation

Inside the notebook (`Crime.ipynb`), we:

- Loaded the dataset using `pandas`
- Converted the date column to datetime format
- Extracted the month from each date
- Grouped data by year, type, and month
- Calculated arrest rates using mean values
- Created visualizations using `matplotlib`

---

## Key Insights (Summary)

- Violent crime **peaked in 2016–2017** and steadily decreased through 2020.  
- **Robbery** is the most common violent crime by a very large margin.  
- **Homicide has the highest arrest rate (~36%).**  
- Crime follows a **seasonal pattern**, with the lowest levels in February and the highest in July–August.  
- Arrest effectiveness varies by year; one year has notably higher arrest rates than others.

---

## Files in This Repository

| File | Description |
|------|-------------|
| `Crime.ipynb` | Main Jupyter Notebook with all code and analysis |
| `crime_notebook.html` | HTML export of the notebook |
| `chicago_crime_2015_2020.csv` | Dataset used for the analysis |
| `README.md` | Project documentation (this file) |
| `requirements.txt` | Python libraries needed to run this project |
| `Chicago Crime project.pptx` | Presentation slides |

---

## How to Run This Project

### 1. Install Required Libraries
If using your own environment, install dependencies:

```bash
pip install -r requirements.txt
