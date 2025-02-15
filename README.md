# Key-KPI-Dashboard-using-Power-BI-
The Key KPI Dashboard is a Power BI project that analyzes sales performance using SQL Server data. It provides insights into key metrics like Year-to-Date, Month-to-Date, and Daily Run Rate. The dashboard aids in strategic decision-making by highlighting trends, strengths, and areas for improvement. 
Objective
The objective of this report is to provide a comprehensive analysis of Watcho key KPI metrics using Power BI, leveraging reporting server data to derive actionable insights for strategic decision-making. By using previous day data from the SQL Server, this analysis aims to deliver accurate, timely insights into sales performance, trends, and patterns, facilitating informed decision-making and strategic planning.

Methodology
Data Source
The analysis is based on previous day data sourced from a SQL Server reporting server. This ensures the data used is both reliable and current as of the previous day, providing effective decision support while maintaining data integrity and accuracy.

Metrics Analyzed
A variety of key performance indicators (KPIs) were analyzed to provide a comprehensive overview of sales performance. These metrics include:

LTD (Year-to-Date)

Definition: Cumulative sales from the beginning of the current year up to the present day.
Purpose: Provides a holistic view of annual sales performance, allowing for an assessment of overall business health and long-term trends.
LMTD (Last Month-to-Date)

Definition: Cumulative sales from the beginning of the previous month up to the present day.
Purpose: Facilitates month-over-month comparison to gauge current month's performance relative to the previous month, helping to identify short-term trends and fluctuations.
Trend (MTD - LMTD)

Calculation: Difference between Month-to-Date (MTD) and Last Month-to-Date (LMTD).
Analysis: Indicates the direction of sales growth or decline compared to the previous month, providing a quick visual indicator of performance changes.
MTD (Month-to-Date)

Definition: Cumulative sales from the beginning of the current month up to the present day.
Insight: Tracks the ongoing monthly sales performance in real-time, allowing for timely adjustments and interventions.
Current DRR (Daily Run Rate)

Calculation: Daily average sales rate calculated to predict total sales for the current day.
Utility: Assists in forecasting daily revenue and adjusting operational strategies accordingly, ensuring that targets are met and resources are optimally allocated.
Day, Day-1, Day-2 (Daily Sales Comparison)

Comparison: Compares daily sales performance for the current day, previous day, and two days prior.
Purpose: Identifies daily sales trends and fluctuations in customer purchasing behavior, providing insights into short-term dynamics and immediate responses.
Last Month, Month-2, Month-3 (Monthly Sales Comparison)

Comparison: Compares current month's sales performance with the same periods from the previous two months.
Insight: Provides insights into seasonal trends and long-term sales patterns, helping to understand broader market dynamics and cyclical behaviors.
MTD vs. LMTD (Month-to-Date vs. Last Month-to-Date)

Comparison: Measures the difference in sales performance between the current month-to-date and the previous month-to-date.
Analysis: Highlights month-over-month growth or decline trends for strategic planning, enabling businesses to adapt to changing conditions and optimize performance.
Day vs. Day-1 (Current Day vs. Previous Day)

Comparison: Evaluates sales performance between the current day and the previous day.
Significance: Helps in identifying daily sales trends and operational adjustments, ensuring that short-term changes are quickly addressed and opportunities are seized.
Insights and Analysis
Current DRR Calculation
The Current DRR (Daily Run Rate) calculation provides a real-time assessment of daily sales velocity. By calculating the daily average sales rate, businesses can predict total sales for the current day and make informed decisions about resource allocation and operational adjustments. This metric is crucial for managing daily operational targets and revenue forecasting, ensuring that sales targets are met and operational efficiency is maintained.

MTD vs. LMTD Analysis
Comparing Month-to-Date (MTD) with Last Month-to-Date (LMTD) reveals valuable insights into the current month's performance trends relative to the previous month. This analysis helps in identifying growth opportunities or challenges early, enabling businesses to adapt their strategies and optimize performance. By understanding how current performance compares to previous periods, businesses can make data-driven decisions and improve their overall effectiveness.

Day vs. Day-1 Comparison
Analyzing daily sales variations (Day vs. Day-1) provides insights into immediate shifts in customer behavior and market demand. By comparing sales performance between the current day and the previous day, businesses can understand short-term dynamics and respond quickly to changes. This enables agile responses and optimization of sales strategies, ensuring that opportunities are seized and challenges are addressed promptly.

Trend Indicator
The trend indicator visually represents sales performance trends using conditional formatting. This visual aid simplifies trend identification and facilitates quick decision-making based on sales performance trends. The trend indicator uses the following visual cues:

Upward Green Arrow: Indicates growth when MTD > LMTD.
Downward Red Arrow: Indicates decline when MTD < LMTD. This straightforward visual representation helps in quickly understanding the direction of performance changes, enabling businesses to act promptly and effectively.
Conditional Formatting
Conditional formatting is applied across key metrics to highlight significant changes and anomalies. This ensures that critical insights stand out, supporting effective analysis and decision-making. By using visual cues such as color coding and icons, conditional formatting makes it easier to identify trends, outliers, and areas of concern. This enhances the overall effectiveness of the analysis and helps businesses to focus on the most important aspects of their performance.

Conclusion
Key Findings
The comprehensive analysis of Watcho's key KPIs using Power BI has yielded several significant insights:

Patterns in Performance: The data revealed consistent patterns in daily and monthly performance, highlighting key trends and fluctuations. These patterns provide valuable insights into the sales cycles, allowing the identification of peak sales periods and seasonal variations. Understanding these patterns helps in forecasting and planning future strategies more effectively.
Areas of Strength: The analysis identified specific areas of strength, such as periods of high sales activity, successful product categories, and effective promotional strategies. These strengths highlight what drives the business's success, allowing for the replication of these successful strategies in other areas.
Impact of Daily Trends: The comparison of daily sales performance (Day vs. Day-1) provided immediate insights into shifts in customer behavior and market demand. This real-time analysis allows for quick adjustments to sales strategies and operational tactics, ensuring that the business remains agile and responsive to changing conditions.
Month-over-Month Analysis: The MTD vs. LMTD comparison revealed crucial information about month-over-month growth or decline trends. Understanding these trends is essential for strategic planning and resource allocation, enabling the business to capitalize on growth opportunities and address challenges proactively.
Effective Use of Conditional Formatting: The application of conditional formatting across key metrics ensured that significant changes and anomalies were highlighted effectively. This visual aid made it easier to identify critical insights and supported more informed decision-making.
Trend Indicators: The use of trend indicators, such as the upward green arrow for growth and the downward red arrow for decline, provided a clear and intuitive visual representation of sales performance trends. This facilitated quick decision-making and helped in maintaining a strategic focus on performance improvements.
In conclusion, the Power BI analysis has provided a robust framework for understanding Watcho's sales performance, identifying strengths and weaknesses, and uncovering opportunities for growth. By leveraging the insights gained from this analysis, the business can make informed decisions, optimize strategies, and drive sustained success. The continuous monitoring and analysis of these key KPIs will ensure that Watcho remains competitive and responsive in a dynamic market environment.
