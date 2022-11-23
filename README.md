# JioSaavn-scrapping

**Scraping Top Charts on ‘JioSaavn’ using Python libraries requests, BeautifulSoup and pandas.**

Scrapped 25 top songs from each of the top charts listed on the home page at JioSaavn

Built functions such as source_code()get_name()etc to parse song name, artist name etc.

Stored data consisting of 275 rows x 3 columns and into songs.csv using Pandas

**Outline**

JioSaavn is an Indian online music streaming service and a digital distributor of Hindi, English, Malayalam, Bengali, Kannada, Tamil, Telugu, Bhojpuri and other regional Indian music around the world. Here songs are categorized in many charts based on popularity, artists, release era and many others.

In this project, we will retrieve information from Top charts pages/urls using Web Scrapping: The process of extracting and parsing data from websites in an automated fashion using a computer program / code.

Here's an outline of the steps we'll follow:

Install important libraries that will be helpful for the project i.e. requests, BeautifulSoup4, pandas.

Download the web page using the requests library.

Parsing the HTML source code using beautiful soup library.

Inspecting HTML source code of the web pages.

Extracts song title, artists name(s), song duration from the web pages.

Compile extracted information into python lists and dictionaries.

Save the extracted information to a csv file.

Checkout Jupyter notebook here:- [https://jovian.ai/sachintyagi0009/jiosavan](https://jovian.ai/sachintyagi0009/jiosavan)
