# Web scraping from 0 to hero
Originally named "Web Scraping Open Project", this repository wants so create a common knowledge among web scraping experts, interesting enough for both rookies and experts in the field.
Anyone can submit some content if it adds value to the project.
Of course, we won't accept any AI-generated content and sellish and sponsored material, even if there are some sections dedicated to commercial tools, but they're based on user experience and not on marketing.

## Why this repository?
Web scraping is becoming harder and more expensive, with anti-bot becoming more aggressive and requiring commercial tools for being bypassed. But, at the same time, the need for web data is growing exponentially, following the post-Covid-19 increase in digitalization. On top of this, AI models will need more and more data to be trained and the main source is usually the web (just ask [Reddit](https://techcrunch.com/2023/07/04/reddit-braces-for-life-after-api-changes/ "Reddit API controversy") and [Twitter](https://business.twitter.com/en/blog/update-on-twitters-limited-usage.html "Twitter anti-scraping measures") )
So while there are some increasing challenges, there are more and more opportunities for developers who want to embark on the career of a web data engineer.
In this repository we're building a silo of all the sparse and fragmented content around the web and sharing some experience with tools, languages, and best practices to create a great basecamp for who's starting now but also a source of inspiration for experts looking for new tools and solutions.

## Who am I?
I'm [Pierluigi Vinciguerra](https://www.linkedin.com/in/pierluigivinciguerra/), co-founder and CTO at [Databoutique.com](https://www.databoutique.com) and I'm working in web scraping for more than 10 years.
I've always felt the need to centralize in some places the information about web scraping that are sparse around the web. At first, I started taking some notes and in 2022 I've decided to share with everyone starting a free substack called [The Web Scraping Club](https://substack.thewebscraping.club/), a quite successful one considering the niche I'm writing to, even if it's only my voice that is heard. With this repository, I want to create a chorus of web scraping experts sharing their experiences and ideas so that all the industry could benefit from it.

## How this repository works?
This repository wants to be a central hub for information about web scraping, so to keep it readable and ordered this page will be used as a table of content, with links to all the topics covered. 
Topics can be added by anyone if they are relevant and add some value to the repository.
I tend to use the pages to create short content (about 400/500 words max) and link to external pages if longer content is needed, but that's not a rule. 
You can write an excerpt of a longer blog on these pages and then link the full article.
Feel free to add your contributions to this repository, sharing each other's knowledge will boost the value of this repository for everyone.

Content not allowed:
  - **Out of scope content**
  - **Promotional content**
  - **Referral codes**
  - **AI-generated content**

The table of content below will be updated regularly as soon as some new topics are coming to my mind, if it's not linking to any article it means that the page still does not exist, so feel free to add one.

## Table of content

### 1.Before scraping a website
#### 1.1 Is scraping that website legal?
  - Reading terms and conditions of the website
  - Is the data I want to scrape compliant with privacy laws or copyrighted?
  - Do I really need to scrape that website or I can buy pre-scraped data?
#### 1.2 Preliminary website study
  - Does the website have an API (internal or exposed)?
  - Does it have some JSON inside the HTML?
### 2. Best practices
  - Use JSON instead of HTML, if possible
  - Selectors
  - Data formatting
  - Reducing the requests number
### 3. Tools
#### 3.1. Headless python scrapers
  - [Scrapy](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Scrapy.md)
  - [scrapy_splash](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Scrapy_splash.md)

#### 3.2. Python scrapers with fully rendered browsers
  - [Playwright](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Playwright.md)
  - [playwright_stealth](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Playwright_stealth.md)
 
#### 3.3. Non Python scrapers with fully rendered browsers
  - [Puppeteer](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Puppeteer.md)

#### 3.4. Non Python full-featured web scraping libraries
  - [Crawlee](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Crawlee.md)

### 4. Common anti-bot softwares & techniques
#### 4.1. Anti-bot Softwares
  - [Akamai](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/Akamai.md)
  - [Cloudflare](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/Cloudflare.md)
  - [Datadome](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/Datadome.md)
  - [PerimeterX](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/PerimeterX.md)
  - [Kasada](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/Kasada.md)
  - [F5 Shape Security](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/Shape.md)
  - Forter
  - Riskified
#### 4.2. Anti-bot Techniques
  - [Passive fingerprinting](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/Passivefingerprint.md) including:
  - [TCP/IP Fingerprint](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/TcpFingerprint.md)
  - [TLS fingerprint](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/TLSFingerprint.md)
  - [HTTP Fingerprint](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/HttpFingerprint.md)
  - [Browser Fingerprinting](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/Browserfingerprint.md) techniques including:
  - [Canvas Fingerprinting](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/Canvasfingerprint.md)
  - [WebGL Fingerprinting](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/Webglfingerprint.md)
  - [Device Fingerprinting](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Antibot/Devicefingerprint.md)

### 5. Test websites for your scraper
  - [https://bot.incolumitas.com/](https://bot.incolumitas.com/) one of the most complete set of tests for your scrapers
  - [https://pixelscan.net/](https://pixelscan.net/) check your ip and your machine
  - [https://bot.sannysoft.com/](https://bot.sannysoft.com/) another great list of tests
  - [https://abrahamjuliot.github.io/creepjs/](https://abrahamjuliot.github.io/creepjs/) set of tests on fingerprinting
  - [https://fingerprintjs.com/products/bot-detection/](https://fingerprintjs.com/products/bot-detection/) page about BotD, a javascript bot detection library included in Cloudflare, where you can also test your configuration

### 6. How to make money with web scraping
  - Freelancing
  - Sell your scrapers with Apify
  - Sell your data on Databoutique.com


