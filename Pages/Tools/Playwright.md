# Playwright

## What is Playwright?
[Playwright](https://playwright.dev/ "Official website") is a testing tool for web application, useful also for web scraping, released on 2021.

## Our View on Playwright

### Usage Rating of Playwright
**BEST CHOICE**: This is among the preferred tools we use
It's the best choice when there's need of a fully rendered browser to scrape a website.

### Configuration
The best configuration we've found up to date against antibot systems consists in: 
1. playwright_stealth module
2. a function to randomize mouse movement
3. selection of a consistent combination of device to emulate and browser
4. slow_mo option to reduce the rendering speed of the browser
5. headless mode

You can find our standard base configuration here.

### When to use Playwright
This configuration is more computing power intesive than a simply scrapy installation so is used only when a fully rendered browser is needed, actually it works pretty well against:
* Perimeterx
* Cloudflare


### Reference and interesting links
[Official website](https://playwright.dev/)

[Our tests](https://chrome.google.com/webstore/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg?hl=it)

[Article: Making chrome headless undetectable](https://intoli.com/blog/making-chrome-headless-undetectable/)


