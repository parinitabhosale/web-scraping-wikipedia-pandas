# Web Scraping: Largest US Companies by Revenue

## Objective
Extract a table from a Wikipedia page using Python and convert it into a structured Pandas DataFrame for analysis.

## Data source
Wikipedia: List of largest companies in the United States by revenue
https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue

## Approach
1. Sent a request to the Wikipedia page using the Requests library
2. Parsed the HTML with BeautifulSoup
3. Located the table and extracted the column headers
4. Looped through the table rows (tr) and cells (td) to collect the data
5. Built a Pandas DataFrame from the extracted rows and headers
6. Saved the final data to a CSV file

## Tools
Python, Requests, BeautifulSoup, Pandas, Jupyter Notebook

## Files
- `Scrapping_Data_From_Real_Website.ipynb`: notebook with the full code
- `Companies.csv`: the scraped data
