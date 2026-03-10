# Movie Industry Correlation Analysis 🎬
**Project Goal:** To determine which variables (Budget, Votes, Score, etc.) have the highest correlation with a movie's gross revenue.

##  Data Cleaning & Wrangling
In this project, I performed extensive data preparation to ensure statistical accuracy:
* **Regex Extraction:** Used Regular Expressions (`\d{4}`) to extract the correct release year from messy string data.
* **Handling Nulls:** Identified and dropped missing values in critical columns (`budget`, `gross`) to prevent visualization errors.
* **Data Type Optimization:** Converted columns to appropriate numeric types for computation.

##  Key Insights & Visualizations
* **The "Big Two":** Budget and User Votes show the highest correlation with Gross earnings.
* **Categorical Encoding:** Developed a custom loop to "numerize" non-numeric data (Company, Genre, Director), allowing for a full-scale correlation heatmap of all variables.



##  Libraries Used
* **Pandas:** Data manipulation and cleaning.
* **Seaborn & Matplotlib:** Advanced data visualization (Heatmaps, Regression Plots).
* **Numpy:** Mathematical operations.
