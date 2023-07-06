# Reading Terms of services of the website
**This is not a legal advice, please refer to a lawyer if you're in doubt**
This great article by [Apify](https://blog.apify.com/enforceability-of-terms-of-use/) summarizes what are the different types of Terms of Use and when they are enforceable or not.
Basically, it depends if the user, or the scraper, did some active actions for accepting them.
  - Browsewrap: when the TOS is placed somewhere on the website but the user doesn't need to make any action. Not enforceable in most cases, since the user could not have seen them.
  - Clickwrap: then the TOS needs to be accepted with a click by the user. They are generally enforceable since the user actively accepted them and any break of TOS could be punished.
  - Scrollwrap: similar to clickwrap but the user needs also to scroll down the page to the end of TOS before accepting. Enforceable in most cases too.
  - Sign-in-wrap: when you need to login and somewhere in the UX you accept the TOS. Depending on the UX, how easy to see are TOS, could be enforceable.

Generally speaking, better not to scrape websites that require a login and an active acceptance of TOS that ban scraping, even because the study made by Apify refers to US the legislation results of cases may differ in other countries.
