# PerimeterX

## What is PerimeterX?
[Perimeterx](https://www.perimeterx.com/products/bot-defender "Perimeterx") Anti-Bot system is a protection system some websites use for blocking web scraping. One example at the moment is [ssense.com](https://www.ssense.com/).

## Our View on PerimeterX

### How to Identify PerimeterX
Use [Wappalyzer Chrome Extension](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/0386528f99a1209a538f6d042e859cd9933011c8/Pages/Tools/Wappalyzer.md)

### Reccomended approach to PerimeterX
During the execution of the scraper it happens, after some pages, that a challenge like the one in the picture is trigged, blocking the execution. It's needed a fully browser to not trigger the captcha, adding some random movement of the mouse and timers before moving to another page.
**BEST CHOICE**: [Playwright](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Playwright.md) + [Stealth](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Playwright_stealth.md)

### Reference and interesting links
[Official web page](https://www.perimeterx.com/products/bot-defender)
[How Perimeterx works](https://www.trickster.dev/post/how-does-perimeterx-bot-defender-work/)

