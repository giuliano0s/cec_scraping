# CEC Web Scraper

This is a simple web scraping tool that extracts product information from [https://www.cec.com.br/](https://www.cec.com.br/), a major Brazilian home improvement and construction store (similar to Home Depot or Leroy Merlin).

The scraper collects data such as product name, price, brand, and category, and saves everything into a structured Excel file (`cec.xlsx`).

> ⚠️ Note: This code was developed in 2023. As of 2025, the site structure may have changed, so parts of the script may no longer work without adjustments.

## Output
The output file `cec.xlsx` (available in the repository) contains:
- 17,000+ unique product entries
- Clean columns with structured information
- Useful for analysis, price comparison, or inventory tracking

## How to run
1. Clone this repository
2. Make sure you have the required dependencies (e.g., `Selenium`, `pandas`)
3. Run the scraper script to collect and save the data (note: the site may require adjustments to selectors if changed)
4. Open `cec.xlsx` to explore the collected dataset

## Example use cases
- Price monitoring
- Product data extraction for BI tools
- Competitor analysis in the home improvement retail market
