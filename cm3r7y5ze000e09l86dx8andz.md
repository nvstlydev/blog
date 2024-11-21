---
title: "Crypto, Push Notifications, & More — BETA v1.2.16 Changelog"
seoTitle: "Crypto, Push Notifications, & More — BETA v1.2.16 Changelog"
seoDescription: "Crypto and push notifications are here! We’ve rolled out early beta testing for the crypto version of our app and Discord bot. Traders can now submit..."
datePublished: Mon Oct 10 2022 04:25:48 GMT+0000 (Coordinated Universal Time)
cuid: cm3r7y5ze000e09l86dx8andz
slug: crypto-push-notifications-more-beta-v1-2-16-changelog-f27b1577ec4c
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1732187893881/9d70fbed-a9af-444d-8088-e6f64152915f.gif
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1732205533871/ca0d9f08-bde4-4b6d-a18c-c7bc61210762.png
tags: startups, startup, social-media, crypto, forex, cryptocurrency, finance, fintech, trading, economy, investing, stocks, futures, stockmarket, tradingplatfrom

---

BETA v1.2.15 Release

**Crypto and push notifications are here! We’ve rolled out early beta testing for the crypto version of our app and Discord bot. Traders can now submit their crypto trades using real-time market data from 12 different exchanges. Crypto stats will be reset after early beta concludes as we still have quite a bit to improve on and issues to look into. Please report any unexpected issues you may run into. Use the $help command and checkout the crypto section, but we strongly recommend checking out the full** [**documentation**](https://help.nvstly.com)**.**

Push notifications are finally enabled! You can receive instant notifications via your internet browser of trades from other traders you follow. To modify these, go to your Settings, under Account Management, click on the Notifications button. You can enable or disable the types of notifications you get from each user you follow.

We also plan on rolling out the new Trade Sharing feature on which we’ve been relentlessly working. It will allow you to share your trades to Discord & Twitter with full customization of how your messages and/or embeds look. Initially this will be carried out through webhooks, but we intend on implementing the ability to link your own Discord bot with the same capabilities. We’ll also be releasing an update soon regarding this new feature along with exciting news about our new web 2.0 design.

Our launch on Product Hunt is coming soon and we’ll need your support! If you would please [create a free account](https://producthunt.com/) on their website so when launch day comes you’ll be ready! We’ll make a blog on the day of our launch which will notify you as it did with this one, so you can’t miss it! To learn more on what Product Hunt is and why we’ll be using it to showcase our app you can refer to [this post here](https://nvstly.com/blog/Trade-Hub-Launches-on-Product-442669). Appreciate you all!

### App Updates

Last month we had some crucial unresponsive bot & website issues with unexpected downtimes, we’re pleased to announce that we have officially fixed & improved the underlying issues as of about 3 weeks ago. We apologize for the inconvenience and frustration it may have caused you. If you still have any trades from that time period you need fixed or submitted, please reach out to us by [email](http://team@nvst.ly) or on [Discord](https://discord.com/invite/rhAvzyzk9J).

**All users will need to upload their profile pictures again, we have switched over to a CDN for storing all images.**

### Added Features

**CRYPTO**

**Default Trading Market**

You can change your default trading market to `stocks` or `crypto`. It is set to stocks by default until you change it.  
If your default is set to `stocks`, you must use the `.x` syntax at the end of your crypto ticker or by specifying the ticker or pair using the `/` separator to trade crypto.  
If your default is set to `crypto`, to trade stocks you will need to use the `-s` syntax at the end of your stock ticker. *This is not needed when submitting an options trade.*

**Default Exchange**

You can change your default cryptocurrency exchange to any of the 12 supported exchanges. It is set to `Binance` by default until you change it.  
You can still submit trades from a different exchange than your default by specifying the exchange name after the price.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1732187889119/45379251-0982-4b60-b2a3-70042cd6ad8b.png align="left")

Example of default exchange when submitting crypto trades

*Exchange can be specified anywhere in notes*

**Default Pair**

A trading pair is the currency you use to buy or sell a cryptocurrency with. It is set to `USDT` by default and can be changed.  
You can still submit trades using any other pair by specifying it with your ticker.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1732187890163/5567d664-e736-4472-8e10-031a922538aa.png align="left")

Example of default pairs when submitting crypto trades

*Default pair set to* `*USDT*`*, specified* `*USD*` *for DOGE trade*

**Crypto: Final Note**

If you’re submitting a trade with your default market set to crypto, and the trade is on your default exchange and using your default pair, then you don’t need to specify anything but the cryptocurrency and the price it’s being traded at. To change your defaults, use the `$defaults` command. See the [documentation](https://help.nvstly.com) to learn more.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1732187891120/44ef1d36-81ba-4d1c-acc3-af047a4954cb.png align="left")

Example of submitting trades when opposite default market is set

*Default market was set to crypto &* `*AAPL-S*` *was used to tell the bot stock trade*  
*No* `*.X*` *syntax or* `*/pair*` *needed for* `*LTC*`*, it used default* `*USDT*`  
*Default market was set to stocks &* `*ETH.X*` *was used to tell the bot crypto trade & used default* `*USDT*`

Push notifications have been added. You can now receive instant notifications through your browser by allowing notifications for this website in your browser settings. They can be enabled, disabled, or modified in your *Settings* under the *Account Management* section. Trade notifications are for all events: open, average, partial/trim, and close. New followers and reputation notifications are available as well.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1732187892053/9f36457e-efe7-4c7a-a44d-5271859e349e.png align="left")

Push notification settings

Indices and their options have been added and can now be traded, such as the SPX.

Can now make Discord & social media tags public on your dashboard through settings.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1732187892815/2f9bd29f-cc00-4d48-a6ba-06a41ab43c3c.png align="left")

Discord social badge on dashboards

### Changes & Fixes

**For New Trades** (trades submitted via the web app),

New Trade display now remembers your last selections such as *long/short* or *daytrade/swing/etc*. to provide maximum efficiency.

Added notice when the submitted price is too far off the current market price.

**For dashboards**

Recent trades on dashboards now show *STC/BTC* if they have been closed. *These will be revamped to show expired or TP/SL hits eventually.*

Combined *total* & *closed* trade stats

Dropdown bug fixed. *When using the dropdown and not closing it before clicking on a trade, it would still show, interfering with Trade Insight’s display.*

**Misc**

When signing up with a Discord account with an unverified email, it now gives a notice that you can’t sign up with an unverified email.

`$rep` command issues have been fixed, as well as the `$rep $` command to rep everyone you follow. Will now inform you that the user doesn't have an account if you attempt to rep an unregistered user again.

Web embeds have been added for missing webpages, and now work the same for both long & short URLs.

### On Our Side

Documentation for crypto, push notifications, and trade sharing features has been finished and added.

implemented a CDN that now stores all user profiles and any future images or videos.

Web embeds have been added for missing webpages, and now work the same for both long & short URLs.

Bot has been updated to the most recent Discord.JS version.

Added trhub.net to the Google Search Console

NVSTly is a free social trading app where retail traders collaborate, track & share trades, ideas, and analysis.