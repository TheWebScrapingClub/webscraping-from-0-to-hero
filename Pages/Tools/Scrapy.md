# Scrapy

## What is Scrapy?
[Scrapy](https://scrapy.org/) is a Python framework for web scraping, maintained by [Zyte](https://www.zyte.com/). 

## Our View on Scrapy

### Usage Rating of Scrapy
**BEST CHOICE**: This is among the preferred tools we use
Scrapy is our best choice for every website that doesn't have any particular website anti-bot tool. It's the de-facto standard in the industry for web scraping in Python.

### Configuration
With a proper default headers setting, a small number of concurrent requests on the website and a delay between them, you can scrape many of the common websites.
Inside a standard settings.py file you will find the following voices:

`USER_AGENT = "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/54.0.2840.71 Safari/537.36"`

This option is needed to identify you and your bot as a genuine user assigning a specific user agent, in this case a Chrome Browser.

`ROBOTSTXT_OBEY = True`

This option indicates if the scraper should follow or not the rules written in the robots.txt file on the target website. For a fair web scraping practice, should be set to True.

`CONCURRENT_REQUESTS = 3`

Number of concurrent requests Scrapy could make to the target website. Depending from the target dimension, this could vary but in our opinion should not be more than 10 to not overload target website servers and trigger anti-bot protection systems.

`DOWNLOAD_DELAY = 1`

Number of seconds of delay between the requests in each thread (thread number is specified with CONCURRENT_REQUESTS  options.

Its standard installation can be integrated with python modules that augment its powers:

* [advanced_scrapy_proxies](https://github.com/reanalytics-databoutique/advanced-scrapy-proxies): module to handle external lists of proxies, using them randomly and deleting not working ones
* scrapy_splash: to render javascript code in a web page via an API
* selenium webdriver: when you need a full headless browser working

### Our standard and best practices
Please read our standards and best practices for web scraping in python before implementing a new website with Scrapy.

### When to use Scrapy
Whenever possible, the first attempt to scrape a website should we always with a standard configuration of Scrapy (unless we already know it's not enough from the antibot analysis we performed)

### Reference and interesting links
[Official website](https://scrapy.org/)

[Short tutorial](https://towardsdatascience.com/a-minimalist-end-to-end-scrapy-tutorial-part-i-11e350bcdec0)


