# Project-Data-Analysis-1
This is my first practice project in data analysis. I used Excel for data processing and Looker Studio for visualization. This project focuses on transaction analysis to identify fraud patterns based on various factors such as latency and device type.

## Project Objective
- Analyze the number of transactions identified as fraud.
- Determine the total financial loss caused by fraudulent transactions.
- Identify the type of devices most commonly associated with fraudulent transactions.
- Examine the relationship between network latency and fraud occurrence.

## Dataset Used
<a href="https://github.com/elangherama/Project-Data-Analysis-1/blob/main/transaction_data.csv">Dataset<a/>

## Process
1. Data Collection
   - The dataset was obtained from Kaggle.
     
2. Data Cleaning
   - Used the "Text to Columns" feature to separate data into appropriate columns.
   - Applied MAX, MIN, and COUNTIF functions to validate data, remove duplicates, and ensure there were no blank entries.
   - Used a Box and Whisker Chart to detect outliers in the dataset.

3. Data Processing
   - Conducted all data analysis using Pivot Tables in Excel.
     
4. Data Visualization
   - The analysis results were visualized using Looker Studio to gain better insights.

## Dashboard
<a href="https://github.com/elangherama/Project-Data-Analysis-1/blob/main/Project_1_Fraud_Analysis.pdf">View Dashboard<a/>

## Project Insight
- A total of 1,000 transactions were recorded, with 48.1% identified as fraud.
- The total fraudulent transaction value reached $378.86K.
- Fraud was more common on mobile devices (267 transactions) compared to desktops (214 transactions).
- Higher latency correlates with increased fraud occurrences, indicating a potential link between network delays and fraudulent activities.

## Final Conclusion
The analysis revealed that nearly half of all transactions (48.1%) were identified as fraud, with a total fraudulent transaction value of $378.86K. Fraud was more prevalent on mobile devices (267 transactions) compared to desktops (214 transactions).
Additionally, a strong correlation was found between higher latency and increased fraud occurrences, suggesting that network delays may be a significant risk factor in fraudulent transactions.
Based on these findings, stricter fraud detection strategies should be implemented, including latency-based fraud detection enhancements and stronger security measures for mobile transactions to mitigate potential misuse. 


