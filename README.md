# eBay Scraper

This project is an **eBay web scraper** designed to extract relevant data from product listings on eBay using URLs provided by the user. The data scraped is stored in a CSV file for easy access and analysis. This tool is useful for quickly gathering details about specific eBay listings, including information like price, product description, seller ratings, and more.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Arguments](#arguments)
- [Output](#output)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Scrapes eBay product data**: Given an eBay product URL, extracts data like the product title, price, seller details, and ratings.
- **CSV Export**: Stores the scraped data in a CSV file, making it easy to access, analyze, or further process.
- **Error Handling**: Handles common issues like invalid URLs and network failures, ensuring the scraper runs smoothly.
- **Scalable**: Easily modify the scraper to extract additional fields or adapt it to similar e-commerce websites.
## Install dependencies:

Ensure you have Python installed.

bash

    pip install -r requirements.txt

    Set up any required configurations (if applicable).

## Usage

    Add the URLs to be scraped: Edit Ebaycom-Input.xlsx with the list of eBay URLs you want to scrape, each on a new line. 

    Run the notebook

    This will start the scraping process, and the results will be saved to a CSV file in the specified output directory.

    View the CSV output: Once scraping is complete, open the generated CSV file (default: output.csv) to view the results.



## Arguments

    --input : Specifies the input file containing URLs to scrape. Default is urls.txt.
    --output: Specifies the name of the output CSV file. Default is output.csv.

## Output

The scraper outputs a CSV file with columns such as:

    Product Title: Name of the product.
    Price: Listed price of the product.
    Seller: Seller's name or ID.
    Rating: Seller rating and reviews.
    Product Description: Detailed description of the product.

## Technologies

    Python: The core programming language used.
    BeautifulSoup: For parsing HTML and extracting data.
    Requests: For making HTTP requests to eBay.
    CSV: Used to export data in an organized, accessible format.

## Contributing

Contributions are welcome! Please open an issue to discuss what you’d like to add or change.
License

This project is licensed under the MIT License. See the LICENSE file for details.
