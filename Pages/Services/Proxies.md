# Proxies

## What is a proxy?
Generally speaking, a proxy is a server that stays between a client and the target server.
![Proxy image from Wikipedia](https://en.wikipedia.org/wiki/Proxy_server#/media/File:Proxy_concept_en.svg)
They are tipically used in web scraping project for the following reasons:
- Ip rotation, a single scraper execution connects to multiple proxies, so the target website doesn't see that requests are coming from a single source
- Avoid geoblocking, some websites have different behaviours in different geographical areas.

## What kind of proxies are available?
Proxies can be divided in groups by their anonimity level or by the device they are running on.
According the anonimity level we have:
- **Transparent Proxies**: the entering request is not altered and the request made by the proxy specified the original Ip. No information about the original request or user is hidden.
- **Anonymous Proxies**: an anonymous proxy does not reveal your IP address but it does reveal that you are using a proxy server.
- **High Anoniymous Proxies (a.k.a. Elite Proxies)**: Elite proxy servers hide both your IP address and the fact that you are using a proxy server at all. These are the most advanced proxies that offer the most security.
For a more in depth analysis, please check [this useful article](https://proxyscrape.com/blog/proxy-anonymity-levels)

As said before, proxies can be divided also by devise they are running on.
- **Datacenter proxies** are typically running on servers and if your target server uses Canvas Fingerprint and blocks the views from these machines, they can be blocked.
- **Residential proxies** instead are running from devices outside datacenters (typically studios, offices and so on). They're tipically less reliable but if they're run on desktops, they can be used to avoid fingerprinting.
- **Mobile proxies** if the device is a mobile phone\tablet.

## Where to find proxies ready to use?
There are websites that offer a list of free proxies ready to use. They are free but not so reliable, so the list can be checked frequently and probably you'll discard a lot of entries because they are not working:
- [https://free-proxy-list.net/](https://free-proxy-list.net/)
- [https://spys.one/en/](https://spys.one/en/)
- [https://www.freeproxylists.net/](https://www.freeproxylists.net/)

For professional pursposes there are several IP providers that offer their services like:
- [BrightData](https://brightdata.com/lp/proxy-network)
- [Oxylabs](https://oxylabs.io/)
- [Zyte](https://www.zyte.com/smart-proxy-manager/)

