# Analysis of International Debt Using SQL Techniques

## Project Overview

This project dives into the international debt data collected by The World Bank, exploring the intricacies of the financial obligations that developing countries have towards this global institution. The main objective is to analyze the dataset to uncover insights into the total amount of debt owed by these countries, identify the country with the maximum debt, and understand the distribution of debt across different indicators.

### Data Source

The dataset originates from The World Bank and comprises information on the amount of debt (in USD) owed by developing countries across various categories.

### SQL Techniques Utilized

1. **Data Exploration and Cleaning:**
   - Initial exploration of the `international_debt` table to understand the dataset's structure and content.
   - Utilization of `SELECT` statements to fetch specific columns and rows, enhancing the readability and efficiency of the data handling process.

2. **Aggregation Queries:**
   - Application of `COUNT(DISTINCT)` to determine the number of distinct countries in the dataset, providing a foundational understanding of the data's scope.
   - Use of `SUM()` and `AVG()` functions to calculate the total and average amounts of debt, respectively, facilitating a deeper analysis of the debt's magnitude and its distribution across countries and indicators.

3. **Analytical Insights:**
   - Identification of the country with the highest debt using `GROUP BY` and `ORDER BY` clauses, showcasing the ability to pinpoint critical data points within a large dataset.
   - Exploration of debt indicators through `DISTINCT` keyword to classify the types of debt, revealing the diversity of financial obligations.

4. **Subqueries and Joins:**
   - Execution of subqueries to find specific data points, such as the maximum amount of debt for a particular indicator, demonstrating the capability to perform complex data retrieval operations.
   - Although not explicitly mentioned, the analytical process potentially involves joining tables or combining data from multiple sources, illustrating advanced SQL techniques for comprehensive analysis.

5. **Data Validation and Verification:**
   - Verification of analytical findings against authoritative sources, ensuring the accuracy and reliability of the conclusions drawn from the dataset.

### Key Findings

- The total debt owed by the countries listed in the dataset amounts to approximately 3.08 trillion USD.
- China has been identified as the country with the highest total debt, amounting to over 285 billion USD.
- Analysis of average debt across different indicators revealed significant variations, with the top debts being in the categories of principal repayments on external debt (long-term) and disbursements on external debt (long-term).

### Conclusion

Through meticulous analysis using SQL techniques, this project has shed light on the global landscape of international debt among developing countries. It provides a clear picture of the financial burdens these countries face, offering insights that could guide policy-making and financial assistance programs.

## How to Use This Repository

- The SQL queries are structured to be run against the `international_debt` database, accessible through a PostgreSQL connection.
- Users are encouraged to explore the dataset further, using the provided SQL queries as a foundation for their analysis.

### Dependencies

- PostgreSQL: For database management and query execution.
- Any SQL client that can connect to a PostgreSQL database.

### License

This project is open-sourced under the MIT license.
