# 📊 Stack Overflow Companies Web Scraping Project

## Overview
This project focuses on web scraping data from the Stack Overflow Companies page to build a structured dataset for analysis. It demonstrates skills in web scraping, data wrangling, and data export using Python libraries, emphasizing real-world data acquisition techniques critical for data science workflows.

## Objectives
- Apply web scraping techniques using Python's `BeautifulSoup` and `requests` libraries.
- Extract data across multiple pages to simulate real-world scraping scenarios.
- Clean, structure, and prepare the raw data for analysis.
- Export the final dataset into CSV and SQL formats for flexible use in data projects.

## Tools & Technologies
- **Python**
- **BeautifulSoup** (for HTML parsing)
- **Requests** (for sending HTTP requests)
- **Pandas** (for data cleaning and transformation)
- **ConvertCSV** (for CSV-to-SQL conversion)

## Data Sources
- [Stack Overflow Jobs - Companies](https://stackoverflow.com/jobs/companies)

## Workflow
1. **Web Scraping:**  
   - Sent HTTP requests to retrieve HTML content from Stack Overflow company pages.
   - Parsed the content to extract relevant information such as company name, industry, size, location, and tech stack.
   - Implemented pagination handling to scrape multiple pages.

2. **Data Cleaning:**  
   - Removed missing or incomplete records.
   - Standardized field formats (e.g., company sizes, tech stacks).
   - Validated data types for analysis-readiness.

3. **Data Export:**  
   - Saved the cleaned dataset to a `.csv` file.
   - Converted `.csv` to `.sql` using [ConvertCSV](https://www.convertcsv.com/csv-to-sql.htm) for database integration.

## Sample Output
| Company Name | Industry         | Location     | Company Size | Tech Stack                     |
|--------------|------------------|--------------|--------------|--------------------------------|
| ABC Tech     | Software          | New York, NY | 201-500      | Python, AWS, React             |
| XYZ Systems  | Healthcare IT     | Chicago, IL  | 51-200       | Java, Azure, SQL Server        |
