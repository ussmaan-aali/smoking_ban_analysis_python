## Data analysis using python
This README file provides an overview of the data analysis Python code used to explore and analyze the "SmokeBan" dataset. The code utilizes various libraries and performs several data preprocessing and analysis tasks. Here's a breakdown of the code sections:

#### Importing Libraries
The code starts by importing the necessary libraries, including pandas, numpy, matplotlib, and seaborn. The "plt.style.use" line sets the plot style to "ggplot" for consistency.

#### Import Dataset
The dataset is imported using the pandas library, specifying the file path of the "SmokeBan.csv" file.

#### Exploring Data
This section includes commands to explore the dataset, such as checking the shape, displaying the head of the DataFrame, examining value counts of the 'education' column, providing information about the dataset, describing the dataset, and displaying the column names.

#### Data Preprocessing
Data preprocessing tasks include renaming the 'Unnamed: 0' column to 'id', checking for missing values using "isna().sum()", checking for duplicated data using "duplicated().sum()", identifying duplicated data using "loc[df.duplicated()]", examining the duplicated data, and removing duplicated data while resetting the index.

#### Univariate Analysis
In this section, two bar plots are created to analyze the distribution of age groups. One plot shows the top 10 age groups, and the other shows the bottom 10 age groups. Additionally, a pie chart is created to visualize the distribution of smokers and non-smokers using custom labels.

#### Feature Relationships
This section explores the relationship between age groups and smoking status. Two bar plots are generated to show the top 10 age groups of smokers and non-smokers. Additionally, a count plot is created to analyze the relationship between employees (smokers or non-smokers) in companies where smoking is banned or not banned.

#### Conclusion
The conclusion section summarizes the findings from the analysis. It mentions the presence of sampling bias in the dataset, specifically noting that most observations are from individuals aged 28 to 40. It also discusses the effect of the smoking ban on employees, gender distribution among those affected by the ban, and the relationship between smoking status and smoking policies in companies.

This README file provides an overview of the code and its analysis, for detailed review see the python notebook.
