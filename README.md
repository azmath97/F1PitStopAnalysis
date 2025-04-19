# F1PitStopAnalysis
🏎️ Formula 1 Pit Stop Analysis (1950–2020)
This project analyzes pit stop performance in Formula 1 races from 1950 to 2020, using data from the Formula 1 World Championship dataset. It explores trends in pit stop durations, compares constructor performance, and investigates how various factors like race circuits and seasons influence pit stop efficiency.

## **🧾 Dataset Overview**
The dataset includes the following key attributes:

raceId: Unique identifier for each race

driverId: Unique identifier for each driver

constructorId: Unique identifier for each constructor

milliseconds: Pit stop duration in milliseconds

seconds: Converted pit stop duration in seconds

circuitId: Unique identifier for each race circuit

name: Name of the circuit or constructor

year: Year of the race

### **🔧 Operations Performed**
#### 📥 Data Loading and Inspection
- Loaded data using pandas.read_csv()
- Inspected data with .head(), .info(), .describe()
- Checked for missing values and verified column data types

#### 🧮 Data Manipulation
Merged various datasets: races, pit stops, constructors, circuits, and results

Filtered data for meaningful analysis (e.g., removed outliers)

#### 📊 Data Analysis
Explored how pit stop durations evolved over time

Analyzed constructor performance in pit stops

Investigated the impact of circuits on pit stop times

Analyzed the relationship between pit stops and race outcomes

#### 🔄 Feature Engineering
Created new features like average pit stop duration by constructor

Grouped data by year, constructor, and circuit for trend analysis

### 📈 Data Visualization
Visualized average pit stop durations over the years

Displayed pit stop data by constructor and circuit

Used scatter plots and bar charts for comparative analysis

### ▶️ How to Run
Place the dataset files in your working directory.

Open and run the Jupyter notebook (pit_stop_analysis.ipynb).

Install required libraries:
pip install pandas numpy matplotlib seaborn

## 🎓 Summary
This project demonstrates proficiency in:

Data manipulation and merging

Time series analysis of pit stop durations

Group-based analytics and pivot tables

Data visualization with Seaborn and Matplotlib

###  Dataset Link :

You can access the dataset and the notebook for this analysis here:
[Formula 1 Pit Stops Analysis - Kaggle](https://www.kaggle.com/code/kevinkwan/formula-1-pit-stops-analysis/notebook)
