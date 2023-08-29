# Beautifulsoup-scraping
This Python script employs web scraping techniques to extract valuable data about SpaceX Falcon 9 and Falcon Heavy launches from a Wikipedia page. 
This Python script demonstrates web scraping techniques to extract insightful information regarding SpaceX Falcon 9 and Falcon Heavy launches from a Wikipedia page. The script utilizes the requests library for retrieving webpage content and BeautifulSoup for parsing the HTML structure.

The script's core functions are designed to extract crucial launch details, including flight numbers, dates, times, booster versions, launch sites, payloads, payload masses, orbits, customers, launch outcomes, and booster landing statuses. These details are systematically organized into a structured dictionary format for easy access and manipulation.

By iterating through tables on the Wikipedia page, the script captures data from each row and compiles a comprehensive list of launch records. Subsequently, this list is transformed into a Pandas DataFrame, facilitating a tabular representation of the acquired launch data.

To facilitate further analysis and data storage, the script concludes by exporting the DataFrame to a CSV file named 'spacex_web_scraped.csv'.
