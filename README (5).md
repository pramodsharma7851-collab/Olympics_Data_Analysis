<img width="959" height="414" alt="image" src="https://github.com/user-attachments/assets/30a7f88d-ea8f-4ab6-a66d-f8f35938e56f" />




# 🏅 Olympics Data Analysis

### Explore Olympic history, medal records, countries, and athletes

<a href="https://find-olympics-analysis-and-records120.streamlit.app/">
  <strong>🚀 OPEN THE LIVE DASHBOARD</strong>
</a>
&nbsp; • &nbsp;
<a href="https://github.com/pramodsharma7851-collab/Olympics_Data_Analysis_Project">
  <strong>VIEW SOURCE CODE</strong>
</a>

<img src="Olympics_rings.png" alt="Olympic rings" width="220">

</div>

---

## 📌 Table of Contents

1. Project Overview
2. Project Links
3. Analysis Modes and Dashboard Features
4. Technologies Used
5. Project Workflow
6. Key Analytical Areas
7. Repository Structure
8. How to Run the Project
9. Visualizations
10. Conclusion

---

## 🎯 Project Overview

The **Olympics Data Analysis Project** is an interactive web application built to explore historical **Summer Olympic Games data from 1896 to 2016**. It allows users to examine medal tallies, compare countries, investigate athlete records, and explore participation and performance trends through tables and visualizations.

The goal is to make Olympic data easier to explore and help users investigate questions such as:

- How do medal tallies vary by country and Olympic year?
- Which sports contribute to a country's medal count?
- How has participation by men and women changed over time?
- What event and medal records are associated with a selected athlete?
- How do athlete age, height, and weight vary across the available records?

## 🔗 Project Links

| Resource | Link |
|---|---|
| **Live Dashboard** | [Open the Olympics Data Analysis App](https://find-olympics-analysis-and-records120.streamlit.app/) |
| GitHub Repository | [Olympics_Data_Analysis_Project](https://github.com/pramodsharma7851-collab/Olympics_Data_Analysis_Project) |
| Main Application | [`app.py`](https://github.com/pramodsharma7851-collab/Olympics_Data_Analysis_Project/blob/main/app.py) |
| Data Preprocessing | [`preprocessor.py`](https://github.com/pramodsharma7851-collab/Olympics_Data_Analysis_Project/blob/main/preprocessor.py) |
| Analysis Helper Functions | [`helper.py`](https://github.com/pramodsharma7851-collab/Olympics_Data_Analysis_Project/blob/main/helper.py) |
| Dependencies | [`requirements.txt`](https://github.com/pramodsharma7851-collab/Olympics_Data_Analysis_Project/blob/main/requirements.txt) |

## 🔍 Analysis Modes and Dashboard Features

The application provides **six navigation options**: Home and five analysis modes. The modes and features below are based on the repository's application code.

### 1. 🏠 Home

The landing page introduces the dashboard and highlights the main areas users can explore, including medal tallies, overall trends, country performance, and athlete records.

### 2. 🥇 Medal Tally

Explore medal counts using year and country filters.

- View gold, silver, bronze, and total medal counts.
- See an overall medal tally across the available Summer Olympics data.
- Filter results for a particular Olympic year.
- Review a selected country's overall performance or its results in a selected year.

### 3. 📈 Overall Analysis

Explore broad patterns across Olympic history.

- Summary indicators for Olympic editions, host cities, sports, events, athletes, and nations.
- Participation trends across Olympic years.
- Men's versus women's participation over time.
- Age distributions for athletes and medal categories.
- Height-versus-weight patterns by sport, with medal and sex information.
- Compare the records of two selected athletes.

### 4. 🌍 Country-wise Analysis

Select a country to explore its Olympic performance.

- Year-wise medal tally for the selected country.
- Sport/event medal patterns through a heatmap.
- Most successful athletes representing the selected country.
- Sports-wise medal tally for the country.
- Top athletes for a selected sport within that country.
- Men's versus women's medal trends over time.

### 5. 🏃 Athlete-wise Analysis

Select an athlete to examine their records and compare performance.

- Individual medal counts and Olympic records.
- Event-wise and year-wise results for a selected athlete.
- Results for a selected event in a selected Olympic year.
- Age distribution in relation to medal categories.
- Height-versus-weight distribution by sport, with medal and sex categories.

### 6. 📅 Year-wise Analysis

1. Top 10 Athletes in a Olympics season for a selected category M,F and Overall.
2. Top-10 Athletes in a sport in a olympucs season (ex- Top-3 athletes in Athletics in 2012 olympics M)
3. No of athletes participation over the years for a country  ( A line graph showing M,F and total no of athletes ).

## 🧰 Technologies Used

The application imports and uses these core tools and libraries:

| Technology | Role in the Project |
|---|---|
| **Python** | Application logic and data analysis |
| **Pandas** | Data loading, filtering, joining, grouping, and transformation |
| **NumPy** | Numerical operations and working with unique values |
| **Streamlit** | Interactive web application and user interface |
| **Plotly** | Interactive charts |
| **Matplotlib** | Plot rendering |
| **Seaborn** | Statistical charts and heatmaps |

The full dependency list is available in [`requirements.txt`](requirements.txt).

## 🔄 Project Workflow

1. **Load the datasets** — Read `athlete_events.csv` and `noc_regions.csv`.
2. **Preprocess the data** — Filter the records to Summer Olympics, merge the NOC-region mapping, remove duplicate rows, create medal indicator columns, and exclude the 1906 edition.
3. **Prepare analysis outputs** — Use reusable functions in `helper.py` to calculate medal tallies and country-, sport-, year-, and athlete-level summaries.
4. **Filter and explore** — Let users select countries, Olympic years, sports, events, and athletes.
5. **Visualize the results** — Display interactive charts, heatmaps, and tables using Streamlit, Plotly, Matplotlib, and Seaborn.
6. **Deploy the application** — Make the dashboard available online through Streamlit.

## 📊 Key Analytical Areas

The project supports analysis of:

- **Medal performance:** Overall and year-specific gold, silver, bronze, and total medal counts.
- **Country trends:** Changes in medal performance across Olympic years.
- **Sport-level performance:** Medal patterns across sports and events, including country/event heatmaps.
- **Gender representation:** Trends in men's and women's participation and medal counts.
- **Athlete records:** Event-wise and year-wise results, individual medal counts, and comparisons between athletes.
- **Athlete characteristics:** Age distributions and height-versus-weight patterns across sports and medal categories.

These are the analytical views supported by the code. Specific conclusions and numerical claims should be drawn from the corresponding charts and tables rather than assumed in advance.

## 🗂️ Repository Structure

```text
Olympics_Data_Analysis_Project/
├── .gitignore
├── Olympics_rings.png
├── README_Olympics_Data_Analysis (1).md
├── app.py
├── athlete_events.csv
├── helper.py
├── main.py
├── noc_regions.csv
├── preprocessor.py
├── readcsv
└── requirements.txt
```




## 🖼️ Visualizations

The application uses charts, tables, and heatmaps to help explore medal performance, country trends, athlete records, age distributions, height-versus-weight patterns, and participation by gender.

<div align="center">

<img src="Olympics_rings.png" alt="Olympic rings from the project repository" width="180">

<br>

<em>Olympic Games theme — image included in this repository.</em>

</div>

You can also explore the deployed interface here:

**[🚀 Open the Live Olympics Dashboard](https://find-olympics-analysis-and-records120.streamlit.app/)**

Some Highlights from the webapp :-
1.Home Page 
<img width="959" height="414" alt="image" src="https://github.com/user-attachments/assets/b156c8ed-0f41-4d3d-9817-4f72e8fa72a2" />

<img width="959" height="416" alt="image" src="https://github.com/user-attachments/assets/4843f651-051e-4568-8e42-17a9bb124718" />

2.Medal Tally 
<img width="959" height="442" alt="image" src="https://github.com/user-attachments/assets/ff597546-2fe1-47b6-bde2-6e3300aaf72a" />

3.  Overall Analysis
  <img width="936" height="398" alt="image" src="https://github.com/user-attachments/assets/ad9904ca-08d0-44eb-b27d-cba2e1774442" />
  <img width="959" height="414" alt="image" src="https://github.com/user-attachments/assets/04291e4a-94c3-471a-9c13-b344e73e26f0" />

4. Country Wise Analysis
<img width="953" height="398" alt="image" src="https://github.com/user-attachments/assets/3d3e0a5a-3b3f-46aa-96ff-6aa7729d5128" />

<img width="959" height="409" alt="image" src="https://github.com/user-attachments/assets/d3610c71-8216-430a-9fba-2f23964c6768" />

5. Athlete Wise Analysis :
<img width="958" height="432" alt="image" src="https://github.com/user-attachments/assets/d9fe1065-8107-4c41-887f-055f01d41b19" />

6. Year Wise Analysis
   <img width="937" height="428" alt="image" src="https://github.com/user-attachments/assets/f20ac52a-f97d-4142-9ff3-47af1efcd904" />
   

## ✅ Conclusion

This project transforms historical Summer Olympics records into an interactive dashboard for exploring medal performance, country-level trends, athlete achievements, and participation patterns. It demonstrates practical skills in Python, data preprocessing, exploratory data analysis, data aggregation, visualization, and Streamlit application development.

---

<div align="center">

Try these in the webapp :
1.TOP 3 medalist in 1500m and 5000m in 2000 olympic's.
2. India's Medal Tally in 2012 London OLympics
3.Most Successful Athletes of UK in swimming.

**🏅 Explore Olympic history through data.**

</div>
