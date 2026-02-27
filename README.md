# Course-Map





\# BABI4005 – Assignment 4  

\## Scraping \& Unstructured Data: BABI Course Prerequisite Network





\### Project Overview



This project analyzes the prerequisite structure of BABI (Business Analytics \& Business Intelligence) courses at BCIT. Course data was collected from the official BCIT course subject page:



https://www.bcit.ca/course\_subjects/business-analytics-business-intelligence-babi/ 



Using web scraping techniques, prerequisite information was extracted from individual course pages and transformed into a structured network model.



The goal was to convert unstructured HTML content into meaningful analytical insights using graph modelling and centrality analysis.





\### Methods



The project was completed in the following stages:



1\. Scraped the BABI course subject page to collect individual course links.

2\. Extracted prerequisite information from course pages using JSON-LD structured data.

3\. Built a directed graph using NetworkX where:

&nbsp;  - Nodes represent courses

&nbsp;  - Directed edges represent prerequisite relationships

4\. Applied centrality metrics to analyze structural importance within the curriculum.

5\. Exported structured datasets to CSV format.







\### Key Findings



\- \*\*BABI3500\*\* requires the highest number of prerequisites (4), making it the most knowledge-intensive course.

\- \*\*BABI1100\*\* unlocks most other courses, functioning as a foundational course within the program.

\- \*\*BABI2500\*\* has the highest betweenness centrality, acting as a structural bottleneck in the curriculum.

\- Multiple entry-level courses exist, indicating flexible starting points within the program.







\### Tools \& Libraries Used



\- Python

\- requests

\- BeautifulSoup

\- NetworkX

\- pandas

\- matplotlib







\### Conclusion



This project demonstrates how unstructured web data can be transformed into structured, analyzable insights. By combining web scraping with network analysis, the prerequisite structure of the BABI curriculum was modelled and evaluated using quantitative metrics.



The final output includes both visual network representations and structured datasets suitable for further analysis.

