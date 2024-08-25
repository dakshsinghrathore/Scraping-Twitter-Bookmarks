## Objective 🎯
bash script that will scrape the URLs of tweets from Twitter Bookmarks and saves them in a markdown file.

## Project Context 💡

Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. In general, web data extraction is used by people and businesses who want to make use of the vast amount of publicly available web data to make smarter decisions.


In this project we will be scraping Twitter and collecting the URL of the tweets from the Bookmarks page and we will be doing this with simple command line tools such as cURL and jq.


- [Disclaimer: Web Scraping has to be used only for learning purposes. Any other attempts to use the data scraped might result in legal action or Your IP might get blocked.]

## Project Stages 📝

The project consists of the following stages:

![bookmarkScraping](./Images/bookmarkScraping.png)

## High-Level Approach 👨🏻‍💻
- Configure the required web driver to access the browser capabilities in testing mode.
- Open up the Twitter login page in a browser session.
- Sign in to a Twitter account using your credentials, passed on using appropriate cURL commands.
- Scrape the URLs of tweets and redirect the same to a markdown file.
