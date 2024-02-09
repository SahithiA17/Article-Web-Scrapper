Article-Web-Scraping

About The Project
This Python script is designed to scrape articles from The Guardian's technology section using their API. It fetches article data, extracts the titles and content, and then saves each article's content to separate text files. The text files are organized in a folder named with the current date and time of the scraping. You can customize the script by changing the URL to target different sections or sources on The Guardian's website. This script is useful for collecting and archiving articles for research or analysis.

Built With
Beautiful Soup

Guardian API 

This project requires an API key from The Guardian to fetch article data. If you don't already have one, you can obtain an API key by following these steps:

Visit The Guardian Developer Portal: The Guardian API Developer Portal

Sign up for an account or log in if you already have one.

Create a new application and obtain your API key.

Once you have obtained your API key, you need to configure the project to use it. Here's how to do it:

Open the Python script where you make the API request (the one with the URL to The Guardian's API).

Locate the URL variable that contains the API request URL.

In the URL, replace YOUR_API_KEY with the actual API key you obtained from The Guardian.

