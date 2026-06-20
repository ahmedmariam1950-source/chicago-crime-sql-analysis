Chicago Crime Data Analysis using SQL
📊 Project Overview
This project explores crime patterns using the Chicago Crime dataset on Kaggle. The goal is to extract meaningful insights using SQL queries.
Tools Used
- SQL (BigQuery via Kaggle)
- Kaggle Dataset
Key Analysis Performed
- Identified most common crime types
- Analyzed crime distribution by location
- Explored frequency of crimes using SQL aggregation
Sample Query
SELECT crime_type, COUNT(*) AS total
FROM crimes
GROUP BY crime_type
ORDER BY total DESC;
📈 Key Insight
The analysis revealed that certain crime types occur significantly more frequently, highlighting patterns that can support data-driven decision-making.
Learning Outcome
This project strengthened my ability to:
- Write SQL queries for real-world datasets
- Use GROUP BY, ORDER BY, and LIMIT effectively
- Translate real-world questions into data queries
🙌 Acknowledgment
This project was completed as part of the She Code Africa Mentorship Program.
