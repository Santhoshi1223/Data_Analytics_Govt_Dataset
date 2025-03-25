# Data Description
The dataset pertains to *Crime Review for the Month of February 2024*. It contains information about different types of crimes, their categories, and recorded statistics.

### Dataset Columns:
- *Sl. No.*: Serial number of the record.
- *Major Head*: Main category under which the crime is classified.
- *Minor Head*: Sub-category of the crime.
- *Unit Name*: Name of the unit reporting the crime.
- *Crime Count*: Number of recorded instances of the crime.
- *Cases Detected*: Number of cases successfully detected.
- *Arrests Made*: Number of suspects arrested.

---

# Overview of the Jupyter Notebook
The notebook performs various operations to analyze and visualize the dataset, including:

### 1. *Data Exploration:*
- Displaying the first 5 records using df.head().
- Checking the shape of the dataset using df.shape.
- Getting a summary of the dataset with df.info().
- Checking for null values and handling them effectively.

---

### 2. *Data Cleaning and Preprocessing:*
- Filled missing values in the *"Minor Head"* column with 'Unknown'.
- Converted necessary columns to integers where applicable.

---

### 3. *Data Visualization:*
The notebook includes several visualizations to explore and analyze the dataset:

- *Bar Plot*: Showing the number of crimes per major head.
- *Pie Chart*: Distribution of detected vs undetected cases.
- *Box Plot*: Distribution of crime counts to identify outliers.
- *Heatmap*: Correlation between numerical columns for pattern recognition.

---

# Data Insights
Key insights derived from the analysis include:

1. *Crime Distribution:* Certain categories contribute significantly to the total number of crimes.
2. *Detection Efficiency:* A substantial gap exists between reported crimes and detected cases.
3. *Arrest Rate Analysis:* Arrests made show correlation with detection rates.
4. *Missing Data Handling:* Missing values in categorical columns (like *"Minor Head"*) are filled to ensure analysis consistency.
5. *Correlation Patterns:* Correlation analysis reveals relationships between crime counts, cases detected, and arrests made.