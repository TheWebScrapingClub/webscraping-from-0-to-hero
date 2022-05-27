# Scrapy_splash (Scrapy module)

## What is scrapy_splash?
[Splash](https://github.com/scrapy-plugins/scrapy-splash "Splash") is the javascript rendering engine mantained by Zyte and scrapy_splash is the python module.

## Our View on scrapy_splash

### Usage Rating of scrapy_splash
**BEST CHOICE**: This is among the preferred tools we use

### Configuration
In settings.py file of the [scrapy](https://github.com/reanalytics-databoutique/webscraping-open-doc/blob/main/Pages/Tools/Scrapy.md) project we need to enable the middleware, as stated in the [official github repository](https://github.com/scrapy-plugins/scrapy-splash).
We need to declare also the variable SPLASH_URL that points to the address of a running splash server. You can install and run it via docker as explained in the github repository.

### When to use scrapy_splash
This python module is required when there's the need to solve javascript challenges in the website, typically when loading the first page of the website.
Usually it's enough to solve reCaptcha javascript challenges (added to a proper scrapy settings configuration)

### Reference and interesting links
[Github repository with instructions and examples](https://github.com/scrapy-plugins/scrapy-splash)

[Useful article](https://www.zyte.com/blog/handling-javascript-in-scrapy-with-splash/)

[Another Howto](https://medium.com/@shahwaiz055/scrapy-splash-400a03a829bf)

