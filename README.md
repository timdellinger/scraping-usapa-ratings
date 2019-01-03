# scraping-usapa-ratings
Python notebooks using Selenium and BeautifulSoup to scrape USAPA pickleball skill ratings into a pandas dataframe &amp; .csv file


'ratings scraping.ipynb' uses Selenium to control Chrome and scrape the USAPA website.  Output is .html files of
  each skill and gender devision.
  
'soup takes html and outputs csv.ipynb' opens these .html files and outputs a .csv file for each, and a final .csv
  file that contains data from all divisions combined.
  
'having a look at the data.ipynb' opens the final .csv file and does some quick analytics, with data on gender and
  playing level

'all divisions combined.csv' is a file that came out of a 30 Sept 2018 pull of the data.  It contains name,
    ratings, and hometwon for all rated USAPA members.
    
 'all divisions combined 17 Dec 2018.csv' is data pulled on 17 Dec 2018
 
 'all divisions combined 3 Jan 2019.csv' is data pulled on 3 Jan 2019
 
 'putting it together.ipynb' is an older version of 'soup takes html and outputs csv.ipynb' that had trouble
   with the encoding at times.
