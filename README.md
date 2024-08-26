# U.S.-County-Debt-to-Income-Ratio-Data-Extractor-and-Merger

This Python script automates the process of extracting county names from a Federal Reserve webpage and merging them with household debt-to-income ratio data. Key features include:

1. Web scraping using Selenium and BeautifulSoup to extract county names
2. Data processing with pandas to merge county names with existing debt-to-income ratio data
3. Handling of CSV files for input and output
4. Creation of a combined dataset with county names, years, and debt-to-income ratio ranges

The script successfully extracted 3,137 unique county names and merged them with 313,819 rows of debt-to-income ratio data, resulting in 100 data points per county. The final output is saved as a CSV file, providing a comprehensive dataset for analyzing household debt across U.S. counties over time.

This tool can be valuable for researchers, economists, and policymakers interested in studying regional economic trends and household financial health in the United States.
