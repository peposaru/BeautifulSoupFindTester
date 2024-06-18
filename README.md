### Problem
While scraping sites I realized I had to run my whole program over and over to test if the data I wanted was being correctly scraped via BeautifulSoup. 
### Purpose
I made this program so I have a quick way of inputting tags, attributes and values to see what text is outputted in an efficient manner. 

Scrape elements from a webpage based on the provided tag, attribute, and value.

#### Args:

url (str): The URL of the webpage to scrape.
  
tag (str): The HTML tag to search for.
  
attribute (str): The attribute to search for (optional).
  
value (str): The value of the attribute (optional).

#### Returns:
list: A list of text content of matching elements found.
