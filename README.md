
# From education to career: insights dashboard
**_Note: The dashboard and data labels are in Lithuanian._**  
## Problem statement

This dashboard provides insights into students' academic performance, career progression, and job market trends. The goal is to uncover patterns in the relationship between GPA, job offers, career satisfaction, and work-life balance. With these insights, educational institutions and students can make better decisions about career planning and skill development.

### Key findings:

- Despite higher GPAs, women tend to receive lower starting salaries compared to men.
- Many students complete more internships than the number of job offers they receive.
- Career satisfaction appears to decline as individuals advance in their careers.
- Arts students receive the highest number of job offers and internships, while Computer Science students receive the least.
- Work-life balance tends to decline with higher academic performance.

## Why this matters for business

Businesses and universities can use these insights to improve hiring and career development strategies.

- **Optimizing hiring strategies**: understanding which fields produce the most job-ready graduates helps companies refine their recruitment approach.
- **Reducing pay disparities**: identifying salary discrepancies allows organizations to address gender pay gaps and promote equitable compensation.
- **Improving career satisfaction**: employers can leverage career satisfaction trends to implement better work-life balance policies, reducing burnout and increasing retention.
- **Enhancing internship programs**: pinpointing gaps between internships and job offers helps businesses and universities create more effective internship opportunities.

## Steps followed

1. **Data import & cleaning**: imported the dataset into Power BI and performed necessary data transformation.
2. **Column profiling & data types**: reviewed column distribution and quality to ensure correct data types were assigned.
3. **Handling missing values**: checked for missing or invalid values and ensured data consistency.
4. **Generating a date column**: since the dataset lacked a proper date column, I created one to enable time-based analysis and improve data structuring.
5. **Creating calculated columns & measures**: developed custom measures to extract key insights:
   - Average salary by gender and GPA.
   - Job offer-to-internship ratio.
   - Career satisfaction vs. work-life balance.
6. **Defining data relationships**: established connections between fact and dimension tables to ensure accurate analysis.
7. **Building visualizations**: chose visuals based on the insights they reveal:
   - Line and bar charts for salary trends by gender and GPA.
   - Scatter plot to examine job offers vs. internships.
   - Line chart showing career satisfaction trends by career level.
   - Bar chart illustrating job offers and internships by study program.
   - KPI cards to display key metrics such as average salary, job offers, internships, and satisfaction scores.
8. **Adding filters & slicers**: created slicers for gender, study program, and career level to make the dashboard more interactive.
9. **Finalizing dashboard formatting**: applied a clean and user-friendly theme to enhance readability and usability.

## Further analysis & future improvements

Additional analysis could further enhance decision-making:

- **Deeper career satisfaction trends**: investigate how factors like industry type or work-life balance policies impact career satisfaction.
- **A deeper breakdown of salary data**: break down salaries by job role, industry, and experience level for a more detailed view.
- **Internship quality vs. job offers**: explore whether specific types of internships lead to better job opportunities.
- **Predictive modeling**: leverage Power BI’s advanced analytics to forecast future job market trends based on historical data.



