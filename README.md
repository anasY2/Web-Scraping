# Web-Scraping 
## Definition
Web scraping refers to the extraction of data from a website. This information is collected and then exported into a format that is more useful for the user. Be it a spreadsheet or an API.
## Project Outline
* We are going to scrape https://github.com/topics.
* We will get a list of 30 topics and for each topic we will get it's title, URL and description.
* For each topic we will get top 20 repositories.
* For each repositories, we will get the repo name, it's owner, URL and number of stars.
* For each topic we will create a CSV file and store the above data.
* Example of CSV format:<br>
                  Year,Make,Model<br>
                  1997,Ford,E350<br>
                  2000,Mercury,Cougar<br>
## Tools and Technologies Used
* Language - Python
* Libraries:
     * Pandas - pandas is a software library written for the Python programming language for data manipulation and analysis.
     * Requests - The requests module allows you to send HTTP requests using Python. The HTTP request returns a Response Object with all the response data (content, encoding, status, etc).
     * Beautiful Soup - Beautiful Soup is a Python package for parsing HTML and XML documents. It creates a parse tree for parsed pages that can be used to extract data from HTML, which is useful for web scraping.
     * OS - The OS module in Python provides functions for interacting with the operating system. OS comes under Python's standard utility modules.
## Result
All the resultant datasets are saved as CSVs in a separate folder (in this case topic-wise_datasets).
