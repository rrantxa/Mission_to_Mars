# Mission to Mars: a Web Scraping Project
### *Overview of the Project*
The purpose of this project was to extract Mars news and Mars temperature data from two websites. The analysis was done using the following tools: 
* Jupyter Notebook
* Python
* Pandas, Numpy and Matplotlib libraries
* Beautiful Soup
* Splinter

The analysis process covered the following steps: 

1. The two websites were visited using splinter. 
2. A BeautifulSoup object was created in order to scrape the website.
3. For the Mars News site, the title and description of the latest articles were scraped. For the Mars Temperature site, the temperature data was scraped from a table.
4. In the case of the Mars Temperature website, the data was cleaned and stored in a Pandas DataFrame, in order to perform a brief analysis and visualizations (which can be found in the 'challenge_files' folder).
5. The data and additional resources were stored in output files for both scraping excercises.