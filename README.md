# Twitter-Scrap
Twitter scrapping - Guvi
Twitter Scraping with MongoDB and Streamlit

This is a web-based Twitter scraping tool built with Python, using the Streamlit framework for the user interface, the Snscrape package for accessing Twitter data, and the MongoDB database to store the extracted tweets. The app allows users to search for tweets containing a specific hashtag or keyword within a given time frame, and view, download, and analyze the results in real-time.

Installation:

To use this app, you need to have Python 3.x installed on your system, as well as the following Python packages:
• streamlit
• snscrape
• pandas
• pymongo
• PIL
You can install them using pip,
like this: pip install streamlit snscrape pandas pymongo pillow or requirement.txt file.

You also need to have access to a MongoDB database, and provide the connection string and database name in the program.

Usage

To run the app, open a terminal, navigate to the directory where the program is located, and enter the following command: streamlit run twitter_scrape.py
or use jupiter notebook it will show the command in the below output space you can just copy and run the command in Terminal or Command Prompt.
This will start the app in your web browser, and you can interact with it using the menus and buttons.

Features:

The app has five menus that allow you to perform different tasks:

Home: This is the landing page, where you can read a brief description of the app and see an image.

About: This page provides information about the tools and technologies used in the app, such as Twitter Scrapper, Snscrape, MongoDB, and Streamlit.

Search: This page allows you to search for tweets containing a specific keyword or hashtag, within a specified time frame. You can also choose how many tweets to display on the screen, and the fields to include in the output.

Display: This page shows the tweets that match the search criteria, in a table format. You can sort the tweets by different columns, and click on a tweet to see more details.

Download: This page allows you to download the tweets that match the search criteria, in CSV or JSON format.
