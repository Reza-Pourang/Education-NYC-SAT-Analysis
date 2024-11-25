SAT Performance Analysis of NYC Public Schools (2012)

Overview: This project analyzes the SAT performance of public schools in New York City during the year 2012. The goal is to identify trends, borough-wide differences, and the top-performing schools in terms of SAT scores. The analysis uses Python and basic data science techniques, including data cleaning, exploratory data analysis, and visualizations to uncover key insights.

Data: The dataset used for this analysis contains the SAT performance data of 478 public schools in New York City for the year 2012. Data is structured as explained below.
* DBN: District Borough Number.
* School Name: Name of school.
* Number of SAT Test Takers: Total students from a school participated in the SAT exam.
* Math Score: The average math SAT score for the school.
* Reading score: The average reading SAT score for the school.
* Writing score: The average writing SAT score for the school.

Installation: To run the analysis locally, you'll need Python and the required libraries.
* Requirements: Python 3.x, Pandas, Matplotlib, Seaborn, and NumPy
* For convenience, you can also use Google Colab to run the analysis, where no installation on your local machine is required.

Usage
Clone the repository:
git clone https://github.com/RezaPou73/NYC-SAT-Analysis.git
* Open the NYCschoolSAT.ipynb Jupyter notebook to explore the analysis steps.
* Run the notebook in Jupyter or Google Colab to reproduce the analysis and visualizations.

Methodology
* Step 1: Data Preprocessing
Data Cleaning: Cleaned missing data and ensured consistency across the dataset by converting non-numeric entries to numerical values and filling missing data with column averages.
Data Transformation: Added a new column, "Total Score," representing the sum of Math, Reading, and Writing scores for each school.

* Step 2: Exploratory Data Analysis
Descriptive Statistics: Calculated key measures, including average, median, and standard deviation for relevant columns.
Data Visualization: Built a variety of visualizations, including bar plots, scatter plots, and box plots, to explore school performance and borough-wide score variation.

* Step 3: Key Findings
The Top Performing Schools: Identify schools with the highest combined SAT scores.
Borough Analysis: Emphasize boroughs with huge differences in combined SAT scores.
Trend Analysis: Studied the different relationships that exist among math, reading, and writing scores for selected schools.

Results
* Top 10 Schools by Combined SAT Scores: Followed the listing of schools in descending order of their total SAT scores. 
* Borough with Highest Variation: Identified the borough that showed the highest standard deviation in SAT results, hence huge disparities in performance.
* Trends: Analyzing for correlation and trends between math, reading, and writing scores.

Visualizations: The following visualizations are included to help tell the story of the project:
* Distribution of SAT Scores: A histogram of all the Total Scores by schools.
* Top Schools Plot: A bar plot showing the names of top 10 performing schools.
* Borough Performance: A boxplot showing SAT scores distribution across boroughs.
