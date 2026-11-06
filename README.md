# 4SF25CI184_3B
🍽️ Zomato Data Analysis – Milestone 1



🛠️ Technologies and Libraries Used

Python – Programming language.

Pandas – Data manipulation and analysis.

NumPy – Numerical operations.

Matplotlib – Data visualization.

Jupyter Notebook – Interactive coding and analysis.

VS Code – Development environment.

Git & GitHub – Version control and project management.



📂 Project Tasks Performed

1. Data Loading and Understanding

Imported the required Python libraries.

Loaded the Zomato CSV dataset using Pandas.

Displayed the first few records using head().

Checked dataset dimensions using shape.

Examined column names and data types.

Generated statistical summaries using describe().

2. Data Cleaning and Transformation

Identified unnecessary columns and removed them.

Checked for duplicate records.

Examined numerical and categorical columns.

Converted columns into appropriate data types.

Used astype() for datatype conversion.

Used pd.to_numeric() for numerical conversion.

3. Handling Missing Values

Identified missing values using isnull() and handled them using:

Mean: Filled missing numerical values using the column average.

Median: Filled missing numerical values using the middle value.

Mode: Filled missing categorical values using the most frequently occurring value.

Compared missing values before and after handling.

4. Data Transformation Using Pandas

Practised different Pandas operations:

apply() – Applied functions to individual column values.

lambda – Performed simple operations on dataset columns.

astype() – Changed column data types.

Created new columns using existing data.

Performed calculations such as rating transformations and cost per person.

5. Insight Generation Using GroupBy

Used Pandas groupby() and agg() operations to generate insights, including:

Number of restaurants by restaurant type.

Average restaurant rating by restaurant type.

Average cost by restaurant type.

Restaurant distribution by area.

Comparison of restaurants based on online ordering.

Comparison of restaurants based on table booking availability.

6. Data Visualization

Created five visualizations using Matplotlib:

Graph

Purpose

Line Graph

Average rating by restaurant type

Bar Graph

Top 10 restaurant types

Histogram

Distribution of restaurant ratings

Scatter Plot

Relationship between average cost and rating

Pie Chart

Online ordering availability

