# Web scraping with Python open knowledge
During the past several years at [Re Analytics](http://re-analytics.com/ "Re Analytics website") we've spent a lot of time finding the best practices for web scraping, to make it scalable and efficient to maintain.
It's like the cat and mouse game, you need to be always updated on the latest developments but, at the same time, the information needed is very sparse on the net.
For this reason, we started to centralize all the information we collected and the best practices we developed, to build a point of reference for the Python web scraping community. 
Feel free to add your contributions to this repository, sharing each other's knowledge will boost the value of this repository for everyone.

## Why Using Some Best Practice
Our goal is to scrape as many sites as we can so we've always looked for these key elements to make a successful large-scale web scraping project. At the moment they are focused on web scraping of E-commerce website because it's what we've done for years, but we're open to integrate them with best practices derived from other industries.
- **Resilient execution**: We want the code to be as low maintenance as possible
- **Faster maintenance**: We work smarter if we find standard solutions, and do not have to decode creative creations every time. 
- **Regulatory compliance**: web scraping is a serious thing, we need to know exactly what tools are used.
The following practices are always evolving and feel free to suggest yours. 

### 1.Preliminary Study

#### 1.1.Technology Stack
Perform a technology stack evaluation for the target website using [Wappalyzer Chrome Extension](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/0386528f99a1209a538f6d042e859cd9933011c8/Pages/Tools/Wappalyzer.md), with attention in the "Security" block.
When a technology stack is detected under the "Security" section, please verify if in this list of technologies there is a specific solution for that technology.
#### 1.2.API search
Has the website some internal or public APIs for fetching the price\product data? If so, this is the best scenario available and we should use them to gather data
#### 1.3. JSON in HTML Search
Sometimes websites have JSON in their HTML, not only when there's an API. Finding this, will ensure stability.
#### 1.4. Pagination
How the website handles the pagination of product catalogue? Internal services that provide the html code of the catalogue are preferred vs loading the full page code
### 2. Code Best Practices
#### 2.1. JSON
Use json if available (on html of the page or from API). It's less prone to changes
#### 2.2. XPATHS
Use Xpaths, not css selectors for getting a clearer code.
#### 2.3. Indent using TABS
Use tabs for indentation instead of spaces - code weights less and it's easier to detect badly indented structure
#### 2.4. No formatting rules in numeric fields
Don't insert rules for cleaning prices or numeric fields: formats change over different countries and are not standards, let's keep this task to post scraping phases in the DBs.
#### 2.5. Product List Page wins on Single Product Page
Load the fewer pages you can. Try to see if the fields you need are all available from product catalogue pages and try avoiding enter the single product page.
