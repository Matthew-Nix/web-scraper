# web-scraper

This is an example web scraper that I built for practice from the following tutorial: 
[Web Scraping With Scrapy and MongoDB](https://realpython.com/web-scraping-with-scrapy-and-mongodb/)

I also referenced Real Python's article on using MongoDB:
[Python and MongoDB: Connecting to NoSQL Databases](https://realpython.com/introduction-to-mongodb-and-python/)

This is a simple, straightforward web scraper that works off of a dummy site to pull book info from a sample store.

To run, MongoDB will need to be installed and setup. Otherwise, I've done my best to make everything work off of the local project files and not use hard coded paths.

## Database details
MongoDB database set to localhost:27017
Database collection name: books

Here's a screenshot of how this looks in MongoDB Compass:

![image](https://github.com/user-attachments/assets/436509d5-e5f1-4c77-b23f-dd1c6efa7810)

## Running the scraper
From a terminal, navigate to the web-scraper/books directory and run "scrapy crawl book":

![image](https://github.com/user-attachments/assets/24d58353-ecb7-4299-8e01-4c2b14ccd4f9)

With logging on (this can be changed in settings.py within the web-scraper/books/books directory), there will be no output in the console, but the book_scraper.log file will be filled in.

## Running unit tests
From within the web-scraper/books directory, run "python -m unittest"

![image](https://github.com/user-attachments/assets/266f0aaa-69d0-4063-ab1c-af3e5ca6c056)
