# Overview

Search for a given on Google.com, scraper and parse the search results in a json array. 

# Test 1 - Basic web scraping

 - Read 'keywords.txt' file 
  - Loop through first 5 keywords 
    - Fetch Google search results for the keyword
    - Scrape & parse the html
    - Store the search results in a JSON array
 - Store the position of amazon.com across all these keywords in JSON with the exact URL

# Test 2 - Web scraping on Scale with IP Block 

 - Read 'keywords.txt' file 
 - Take proxy infiormsation from lumnati (Password shared on email)
 - Take all of the keywords 
 - Fetch Google search results for the keyword
   - Scrape & parse the html
   - Store the search results in a JSON array
 - Store the position of amazon.com across all these keywords in JSON with the exact URL
 

# Test 3 - Emulate location in Google 

   - Read 'keywords.txt' file 
   - Take a random keyword 
   - Fetch Google search results for the keyword in the location "seattle washington USA"
   - Scrape & parse the html
   - Store the search results in a JSON array
   - Store the position of amazon.com across all these keywords in JSON with the exact URL
 

# Test 4 - Basic web scraping with pagination

   - Open this page - https://www.guestpostengine.com/search?q=health
   - Take the Domain name (Class kt-widget__username), Domain Authority, Global Rank & Traffic data
   - Paginate through first 10 pages
   - Store the results in a JSON array
