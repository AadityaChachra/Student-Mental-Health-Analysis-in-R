# Student Mental Health Analysis

This project aims to analyze the prevalence and impact of mental health issues among a population of students. 

**Key Features:**

* **Data Loading and Cleaning:**
    * Reads data from a CSV file named 'data.csv'.
    * Removes the 'Timestamp' column.
    * Renames columns for better readability.
    * Converts categorical variables ('Yes'/'No') to binary (1/0).
    * Handles missing values in the 'Age' column by imputing a reasonable value (e.g., the median age).
    * Removes duplicate rows.

* **Exploratory Data Analysis (EDA):**
    * **Correlation Analysis:** 
        * Calculates the correlation matrix between numeric variables.
        * Visualizes the correlation matrix using a heatmap.
    * **Age Group Analysis:**
        * Divides students into age groups.
        * Calculates the number of students experiencing depression, anxiety, and panic attacks in each age group.
        * Visualizes the distribution of these conditions across age groups using pie charts.
    * **Specialist Treatment Analysis:**
        * Analyzes the relationship between the number of mental health conditions and the utilization of specialist treatment.
        * Creates a bar plot comparing the number of students taking and not taking specialist care for different numbers of conditions.
    * **Course and CGPA Analysis:**
        * Examines the prevalence of mental health issues across different courses.
        * Identifies the top courses with the highest number of students experiencing depression.
        * Visualizes the distribution of mental health issues across different CGPA ranges.
    * **Gender Analysis:**
        * Compares the prevalence of depression, anxiety, and panic attacks among male and female students.
        * Visualizes the findings using pie charts.

* **Data Visualization:** 
    * Utilizes `ggplot2` for creating informative and visually appealing charts.
    * Employs `gridExtra` for arranging multiple plots in a single output.
    * Uses `RColorBrewer` for generating visually distinct color palettes.

**Required Packages:**

* `ggplot2`: For creating elegant and customizable plots.
* `dplyr`: For data manipulation and transformation (e.g., filtering, grouping, summarizing).
* `tidyr`: For data tidying and reshaping (e.g., pivoting data from wide to long format).
* `reshape2`: For data reshaping (e.g., melting and casting data frames).
* `corrplot`: For visualizing correlation matrices.
* `plotly`: For creating interactive and dynamic plots.
* `gridExtra`: For arranging multiple plots in a single output.
* `RColorBrewer`: For generating visually appealing color palettes.

**To Run:**

1. **Install Packages:**
   ```R
   install.packages(c("ggplot2", "dplyr", "tidyr", "reshape2", "corrplot", "plotly", "gridExtra", "RColorBrewer"))

2. **Load Libraries:**
   ```R
   library(ggplot2)
   library(dplyr)
   library(tidyr)
   library(reshape2)
   library(corrplot)
   library(plotly)
   library(gridExtra)
   library(RColorBrewer)

3. **Run the R script:** Execute the R script containing the analysis and visualization code.

## Note:

1. This README provides a detailed overview of the project's key features, data analysis steps, and visualization techniques.
2. The specific analysis and visualizations may vary depending on the research questions and the available data.
3. This project provides a valuable framework for understanding the mental health challenges faced by students and can inform interventions and support programs.
