# web_scraping_challenge

During this activity data was gathered from a various Mars themed websites. The python library BeautifulSoup was used to import and parse the top Mars related news articles from the given website, accessing the html code of the website to extract the specified data which was article titles and previews. The collected titles and previews of the top news articles were stored in dictionaries, and finally printed as a list.

After news data, Martian weather data was analyzed for temperature and pressure trends. BeautifulSoup was again used to extract weather data stored in a table. The extracted data was converted into a Pandas dataframe, and cleaned to standardize data types for easy analysis. After finding the number of total rows in the dataset (n = 1867), analysis was done to determine the average temperature by month on Mars. It was found that the 3rd Martian month is the coldest (avg temp = -83 C) and the 8th month is, realatively, the warmest (avg temp = -68 C). The atmospheric pressure by month was also analyzed, appearing to be at it's lowest in the middle of the year (months 4-7). Finally, the temperature data was plotted against time to estimate the length of a Martian year, assuming that temperature will follow a predictable trend as Mars revolves around the sun. From the data, a year on Mars appears to be approximately 650 terrestiral days long.


Sources used:
Pretty print documentation used as reference to not automatically alphabetize results: https://docs.python.org/3/library/pprint.html
Xpert Learning Assistant in Bootcamp Spot: Used for storing the table data in part two, pointed me towards the right direction of using list comprehension for extracting individual data points from each row.
Datetime conversion: https://www.geeksforgeeks.org/python-pandas-to_datetime/
Finding index of min and max points: https://www.geeksforgeeks.org/python-pandas-series-idxmin/