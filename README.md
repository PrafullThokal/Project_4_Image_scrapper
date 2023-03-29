# Project_4_Image_scrapper

This GitHub repository contains the source code for a Flask web application that allows users to search for images and scrape them from Google. The images are then stored in a MongoDB database. The application is designed to be deployed on the Azure cloud platform.

This project is a Flask web application that allows users to search for images and scrape them from Google. The images are then stored in a MongoDB database.

When a user inputs a search query, the server sends a request to Google Images and scrapes the resulting images using the BeautifulSoup library. The images are then downloaded to a specified directory on the server, and their binary data is also stored in a MongoDB database.

The user can search for as many images as they want, and the images will be added to the database along with their respective index numbers. The images can then be accessed and retrieved from the database using MongoDB queries.

Overall, this project demonstrates how to build a simple image scraping application using Flask and MongoDB. It can be useful for anyone who wants to build similar applications or learn more about web scraping and database management.
