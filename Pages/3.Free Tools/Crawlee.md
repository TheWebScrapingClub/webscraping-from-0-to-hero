# Crawlee

## What is Crawlee?

[Crawlee](https://crawlee.dev/) is a Node.js library for web scraping, maintained by [Apify](https://apify.com/).

## Our View on Crawlee

### Usage Rating of Crawlee

**RISING STAR**: Crawlee is one the most complete Node.js web scraping libraries. Despite being a relatively new player in the scraping scene, Crawlee is rapidly growing in popularity due to its extensive features and focus on mimicking real-user behavior to bypass website anti-bot protections.

### Configuration

Crawlee comes with three main crawler classes: **CheerioCrawler**, **PuppeteerCrawler** and **PlaywrightCrawler**. All classes share the same interface for maximum flexibility when switching between them.

#### CheerioCrawler

A plain HTTP crawler, that parses HTML using the Cheerio library. It's very fast and efficient, but can't handle JavaScript rendering.

#### PuppeteerCrawler

A headless browser crawler, controlled by the Puppeteer library. It can control Chromium or Chrome. [Puppeteer](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Puppeteer.md) is the de-facto standard in Node.js headless browser automation.

#### PlaywrightCrawler

Playwright can be considered as the successor to Puppeteer. It can control Chromium, Chrome, Firefox, Webkit and many other browsers. If you're not familiar with Puppeteer already, and you need a headless browser, we recommend you go with [Playwright](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Playwright.md).

### When to use Crawlee

Crawlee builds on top of popular Node.js libraries such as Cheerio, Puppeteer and Playwright while adding extra functionalities such as out of the box anti-block features.

This makes Crawlee a great choice for Node.js web scraping developers looking for a flexible and complete library that takes away the complexity of configuring scrapers to bypass modern anti-bot protections.

### Reference and interesting links

[Official website](https://crawlee.dev/)

[Building an Amazon Scraper in Node.js with Crawlee - Written tutorial](https://developers.apify.com/academy/web-scraping-for-beginners/challenge/initializing-and-setting-up)
[Building an Amazon Scraper in Node.js with Crawlee - Video tutorial](https://www.youtube.com/watch?v=yTRHomGg9uQ)
