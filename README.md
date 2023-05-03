![61f57f773b67cdc50e7ca138_header_v1-rev](https://user-images.githubusercontent.com/128593114/235909735-d4df9e8d-965e-4188-965d-b155a934418d.png)


# Linkedin-Job-Analysis
Job Analysis
This project aims to analyze how jobs are distributed across different industries, locations, and company sizes. 
The goal is to provide useful insights for entry-level job seekers.

# Data Collection
The data was scraped from various job listing websites using Selenium automation tool and Python notebooks. We collected information such as company ID, designation, company name, LinkedIn followers, employee count, level, industry, location, detail ID, involvement, total applicants, and job ID.

We then converted the scraped data into a CSV file for further analysis. However, the data was noisy, so we performed some cleaning activities using Excel before importing it into MySQL server.

# Data Analysis
We divided the companies into three categories based on their size: startups with less than 200 employees, mid-sized companies with 500-1000 employees, and large-sized companies with more than 1000 employees.

We found that startups had more opportunities for entry-level employees compared to mid-sized and large-sized companies. However, candidates were applying more for mid-sized and large-sized companies. We also found that the IT industry had the most number of jobs available compared to other industries.

We analyzed the data by location and found that Chennai had the most number of jobs based on the handful of jobs we had scraped. We also found that 2.7 applicants were on a single opening, and Sutherland Barclays had the most number of jobs. Digital marketing was the top designation.

Tamil Nadu had the most number of jobs based on our data. We extracted these insights using SQL queries and exported the CSV files for further analysis.

# Data Visualization
We used Excel pivot to create appropriate charts and an attractive dashboard based on the insights we gathered from the data. The dashboard includes graphs and charts that showcase the distribution of jobs by industry, location, company size, and designation.
![Screenshot 2023-05-03 173356](https://user-images.githubusercontent.com/128593114/235910752-324d5859-962c-481f-8fd8-e7bf4aaa6ff2.png)


# Conclusion
This project provides useful insights for entry-level job seekers who are looking to start or shift their careers. The analysis and visualization of the data help them understand the job market trends and make informed decisions about their career path.
