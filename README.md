# Block-AI-FilterList-for-uBlockOrigin
A huge network request fliterlist of sites (~950) that contain AI generated content, for the purposes of blocking access to site that contains AI generated content with uBlock Origin. 

## Installing the blocklist for uBlock Origin

### One-click filter import

If you have uBlock Origin installed, click [this link](https://subscribe.adblockplus.org?location=https%3A%2F%2Fraw.githubusercontent.com%2Iz-zzzzz%2FBlock-AI-FilterList-for-uBlockOrigin%2Frefs%2Fheads%2Fmain%2Flist_for_uBlock_Origin.text&title=Sites%20using%20AI%20generated%20content) to import the filter list in just a click! Quick and simple.

### Manual Import

1. Make sure that you have the uBlock Origin Extension for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/), [Chrome](https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm), or any browser that supports uBO (& Android via Firefox or Kiwi Browser).

2. Click on the uBlock Origin Extension, and in the bottom right, there is a cog-wheel symbol--named the dashboard. Click it.

3. Once you are in the dashboard, look towards the top. Click on the tab that says "Filter lists".

4. Look towards the bottom, and expand the ```Import``` button.

5. Copy and paste this URL into the dialogue box: 
```
https://raw.githubusercontent.com/Iz-zzzzz/Block-AI-FilterList-for-uBlockOrigin/refs/heads/main/list_for_uBlock_Origin.text
```

6. Apply changes, and you're set!

uBlock Origin will automatically refresh the filter list once a day, so you'll always have up-to-date filters. 

If you want to force an update of the filter list, pressing the stopwatch next to the newly added list, then pressing ```Update now``` will achieve that.

### For Adguard:

1. Open Adguard Home Dashboard
2. Go to filters --> DNS blocklists.
3. Click `Add blocklist`, then `Add a custom list`.
4. Enter the name of the list (eg. AI blocklist) into the first dialogue box.
5. Copy and paste the url into the second dialogue box.
6. Hit save, and the list is added!


## Allowlisting sites
Don't like a website being blocked? You can easily create an allowlist in your own personal uBlock Origin or uBlacklist filter list. 

Here's how to do it. 

### For uBlock Origin:
1. Toggle the [DOM inspector](https://github.com/gorhill/uBlock/wiki/DOM-inspector) `</>` through uBlock Origin's [logger](https://github.com/gorhill/uBlock/wiki/The-logger).
2. Locate the URL you want to allowlist.
3. Click on the filter you want to disable (eg. vecteezy.com); it should then be crossed out.
4. Press the save icon, then the "Create" button.

Boom! Now it's allowlisted!

Or, if you don't want to go through that mumbo-jumbo, add this line in your filter list: 
```
TODO
```

Change "example.com" to the URL you want to allowlist. Copy & paste that in uBlock Origin's "My filters" list, and you're set!

## Special Thanks

Special thanks to: 

+ This [pastebin](https://pastebin.com/B8kP4imQ) (since it added even more sites to my blocklist)

+ u/AchernarB for the [awesome snip-bit of code.](https://www.reddit.com/r/uBlockOrigin/comments/13uyex5/how_to_block_results_from_a_specific_site_in_the/)

+ Raymond Hill, [uBlock Origin extension](https://github.com/gorhill/uBlock)

+ iorate, [uBlacklist extension](https://github.com/iorate/ublacklist)

+ [laylavish (Original author)](https://github.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist)

## Related Projects

[Super SEO Spam Suppressor (SSSS)](https://github.com/NotaInutilis/Super-SEO-Spam-Suppressor) by NotaInutilis

> An anticapitalist blocklist targeting websites abusing SEO tactics to spam web searches with data pollution and security risks: content farms, scrapers, copycats, generative AI, scams, advertisements, malwares, and useless wasteful garbage in general. It is best used with uBlacklist. 

[Journey Buster 3](https://journeybuster.com/) by k0vac

> A Chromium extension that lets you know if an image is AI generated, for use on Twitter.

[Awesome List of uBlacklist Subscriptions](https://github.com/rjaus/awesome-ublacklist) by rjaus

> A compilation of awesome uBlacklist subscriptions to block various sites from appearing in Google, Bing, or DuckDuckGo search.

[Anti-AI Google Search Tips](https://github.com/laylavish/TipsTricksGoogleSearch) by yours truly

> Tips and tricks to make Google Search (and other search engines that have similar operators) return authentic imagery.

[uBlockOrigin-HUGE-AI-Blocklist](https://github.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist) by laylavish

> Original author for a blacklist.
