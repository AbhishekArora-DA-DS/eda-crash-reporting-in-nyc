# eda-crash-reporting-in-nyc
The data was cleaned and then further analysis was carried out.

This project provides an in-depth analysis of motor vehicle crashes in New York City over the past decade. It highlights key patterns such as the number of crashes per year, geographical variations, the impact of peak traffic hours, and the severity of crashes involving injuries and fatalities.

## Objective

The objective of this project is to analyze crash data to uncover trends and insights, helping stakeholders make data-driven decisions to improve road safety.

## Dataset

The dataset includes motor vehicle crash data from various boroughs of New York, detailing the number of injuries, fatalities, time of crashes, and other factors.

## Tools Used

- **Pandas** for data manipulation
- **Seaborn** and **Matplotlib** for visualization

## Key Insights and Conclusions

### Conclusion 1: Crashes per Year
The number of motor vehicle crashes per year was highest around 2017 and 2018.

- We observed a sharp increase in crashes from 2012 (~82,000) to 2013 (~170,000), representing an approximate **107% increase**.
- A steep decline occurred between 2019 (~195,000) and 2020 (~102,000), marking an approximate **47% decrease**.

![Plot for Crashes per Year](/result_plots/crashes_per_year.png)

---

### Conclusion 2: Crashes per Borough
Motor vehicle crashes vary significantly across different boroughs.

- **Brooklyn** reported the highest number of crashes (~431,000), followed by **Queens** (~364,000). 
- **Staten Island** had the lowest (~57,000).

![Plot for Crashes per Borough](path_to_image_2)

---

### Conclusion 3: Crashes per Hour
Crashes tend to peak during late afternoon and early evening hours.

- The highest number of crashes occurs at **4 PM (~128,000)** and **5 PM (~126,000)**.
- The lowest number of crashes is recorded around **3 AM (~20,000)** and **4 AM (~23,000)**.

![Plot for Crashes per Hour](path_to_image_3)

---

### Conclusion 4: Injuries vs Fatalities
The overwhelming majority of motor vehicle collisions result in injuries.

- Approximately **99.5% of the incidents resulted in injuries**, while only **0.5%** were fatalities.

![Plot for Injuries vs Fatalities](path_to_image_4)

---

### Conclusion 5: Causes of Crashes
The most common reason for crashes is **Driver Inattention/Distraction**.

- It accounts for **40.2%** of crashes, followed by **Failure to yield Right-of-Way** at **12.1%**.
- The least common reason is **Unsafe Lane Changing**, accounting for **3.8%** of crashes.

![Plot for Causes of Crashes](path_to_image_5)

---

### Conclusion 6: Injuries per Involved Party
Injuries in crashes are highest among **motorists**.

- **Motorists** account for **384,708 injuries**, followed by **pedestrians** with **103,465 injuries**.
- **Cyclists** account for **48,965 injuries**.

![Plot for Injuries per Party](path_to_image_6)

---

### Conclusion 7: Crashes per Month
Crash occurrences tend to peak during the summer months.

- **July** had the highest number of crashes (~163,983), followed by **August** (~159,587).
- The lowest number of crashes occurred in **April** (~125,899).

![Plot for Crashes per Month](path_to_image_7)

---

### Conclusion 8: Injuries and Deaths per Year
The number of injuries peaked at **58,016 in 2018**, with a decline to **30,248 in 2023**.

- The number of deaths fluctuated, with the highest recorded in **2021 (256 deaths)** and the lowest in **2012 (122 deaths)**.
- Overall, injuries showed a general increase until 2018 before declining, while deaths exhibited variability with a concerning increase in recent years.

![Plot for Injuries and Deaths per Year](path_to_image_8)

---

### Conclusion 9: Injuries per Crash Hour
The number of persons injured varies significantly throughout the day.

- Peak injuries occur at **17:00 (5 PM)** with approximately **37.9K injuries**.
- Injuries start rising from **13:00 (1 PM)** and continue increasing until **17:00 (5 PM)**.
- The lowest number of injuries occurs during early morning hours, particularly around **03:00 (3 AM)**.

![Plot for Injuries per Crash Hour](path_to_image_9)

---

## Final Conclusion
The analysis of motor vehicle crashes in New York reveals important patterns related to time of day, geographical location, and the types of individuals involved. The data highlights the highest crash rates during peak traffic hours, particularly in the late afternoon, and underscores the greater risk faced by motorists. The geographical analysis shows Brooklyn as the most affected borough, while fatalities, though relatively rare, have increased in recent years. These insights can guide city officials and traffic safety organizations in improving road safety measures and reducing crash rates in the future.

## Future Work
- **Deeper Geo-Analysis:** Visualize crashes at more granular levels using advanced mapping techniques.
- **Predictive Modeling:** Apply machine learning to predict crash occurrences based on historical data.

## How to Use

1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter notebooks to generate the plots.

---

Thank you for reviewing this project. Your feedback is appreciated!

