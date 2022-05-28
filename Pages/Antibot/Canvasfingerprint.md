# Canvas Fingerprint

## What is Canvas Fingerprint?
Canvas Fingerprint is an anti-bot technique that can be found in some installations of Cloudflare Bot Management. 
It consists in a javascript that renders an image in background on website loading: similar hardware configurations give the same result and this allows the anti bot to trigger a captcha if the hardware configuration is similar to a server machine. It may happens that the same scraper works on a workstation but does not work on a VM hosted server.


## Our View on Canvas Fingerprint

### How to Identify Canvas Fingerprint
As far as we know, at the moment Cloudflare (in some configuration) is the only anti bot who uses this solution (not visible from wappalyzer). An homemade bot for analyzing anti bot measures can be found on discord server "[Scraping Enthusiast](https://discord.gg/Y8yuF55m7j)" managed by the developers of Puppetter and can recognize the Canvas Fingerprint using a series of queries on the website.


### Recommended approach to Canvas Fingerprint
**BEST CHOICE**: [Playwright](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Playwright.md) + [Stealth](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Playwright_stealth.md) + hosting on a workstation

### Reference and interesting links
[How canvas Fingerprint work](https://fingerprintjs.com/blog/canvas-fingerprinting/)
[How canvas Fingerprint work 2](https://browserleaks.com/canvas#how-does-it-work)
[Test if a VM is detected here](https://fingerprintjs.com/products/bot-detection/)
