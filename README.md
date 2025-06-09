**Project Title:**
**Top 100 U.S. Companies Web Scraping & Data Analysis**

**Description:**
This project focuses on web scraping, data cleaning, and exporting structured data using Python. I extracted the Top 100 U.S. Companies by revenue from a public website, cleaned and organized the data into a structured format using pandas, and exported it to Excel/CSV for further analysis or visualization.

**Key Features:**
Web Scraping using requests and BeautifulSoup

Extracted structured data from an HTML table

Handled text formatting and whitespace cleanup

Built a pandas DataFrame with columns:

Rank

Company Name

Industry

Revenue (USD millions)

Revenue Growth

Number of Employees

Headquarters Location

Exported clean data to:

.csv (Comma Separated Values)

.xlsx (Excel) for better compatibility with Excel/BI tools

**Technologies Used:**
Python

pandas

BeautifulSoup

requests

Jupyter Notebook

Excel/CSV

**Use Cases:**
Data Portfolio Showcase

Intro to Web Scraping & Data Wrangling

Preparing datasets for use in Power BI / Excel dashboards

**sample Output:**
Rank	Company Name	Industry	Revenue	Growth	Employees	HQ
1	Walmart	Retail	648,125	6.0%	2,100,000	Bentonville, AR
...	...	...	...	...	...	...

**File Structure:**

 web_scraping_project/
  web_scraping.ipynb
  web_scraping.xlsx
