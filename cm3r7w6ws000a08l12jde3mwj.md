---
title: "Forex Market Supported, POV Charts Revamped, & More on NVSTly v2.3"
seoTitle: "Forex Market Supported, POV Charts Revamped, & More on NVSTly v2.3"
seoDescription: "Although this update doesn’t include many new features, changes, or improvements, it does bring some significant enhancements..."
datePublished: Fri Jul 26 2024 08:33:53 GMT+0000 (Coordinated Universal Time)
cuid: cm3r7w6ws000a08l12jde3mwj
slug: forex-market-supported-pov-charts-revamped-more-on-nvstly-v2-3-14d479fa140e
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1732187801759/e9bba75b-874c-4146-8ba1-2d0f24ede01b.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1732203829084/f0005c09-5077-4765-9db8-295ab567067d.png
tags: startups, startup, social-media, crypto, forex, cryptocurrency, finance, fintech, trading, economy, investing, stocks, futures, stockmarket, tradingplatfrom

---

Although this update doesn’t include many new features, changes, or improvements, it does bring some significant enhancements. NVSTly is proud to announce that the platform now supports the forex market. You can now track and share forex trades, bringing us one step closer to our goal of supporting all financial markets, with only the futures market left to integrate.

[](https://nvstly.com)

NVSTly Implements Forex Market Support

We hope that the availability of tracking and sharing forex trades will open our app to a broader range of users. This is a major addition for NVSTly, setting us apart from any other social trading platform — no competitor supports all the markets and dozens of cryptocurrency exchanges that NVSTly does. We are confident and fully believe in the feedback that NVSTly is the [#1 free interactive social investing platform](https://nvstly.com) available today. There is no other platform that comes close to this title.

Apart from integrating forex market support, we have completely revamped POV Charts — a feature available on all Trade Insight interfaces. POV Charts provide viewers with the trader’s perspective, marking the candlesticks where they entered, averaged, trimmed, closed, or updated their position. This allows viewers to see chart patterns, trends, and technical analysis from the trader’s point of view. We’ve updated these charts to show data and candlesticks after the latest position update or trade closure. Additionally, we’ve fixed an annoying bug that caused repeating candlesticks or chart patterns on historical data.

**Latest update on options data & trades:** As mentioned in the [previous update](https://nvstly.com/blog/Whats-Going-on-with-Options-084222 "What's going on with options data?"), we have fixed issues relating to options trades and data. Currently, we are still using a temporary solution that is working without problems, and still in the same scenario as mentioned in the last update.

### v2.3 Changelog

[v2.2 Changelog](https://nvstly.com/blog/Superspeed-Webull-Integration-Open-Beta-862082 "Previous Changelog")

### App & Web

**Support for the forex market has been added.** Trade tracking and sharing are now available for all forex ticker pairs. Forex market support has been implemented throughout the entire web and mobile apps, and is fully integrated with Discord through our Discord bot.

Forex trades can now be submitted through the New Trade feature.  
Forex trades can now be updated, averaged, partial or trimmed, closed, or standalone notes added or quickly closed through the Active Positions feature on the New Trade UI.  
All forex trades are equipped with their own Trade Insight interface.  
Forex trades have been added to the live [Trades](https://nvstly.com/trades "NVSTly: Social Investing | Latest Trades") feed.  
Trader dashboard now display all forex trades & stats when *Forex* filter is enabled, or if set as the [default market](https://nvstly.com/blog/Forex-Market-Supported-POV-Charts-885873#defaultmarket "Default Market").  
Forex trades use it’s own stat system based on PIPs rather than percentages. *Stats for all markets cannot be displayed together because of this, forex stats can only be displayed separate of stocks, options, & crypto.*  
Forex trade notifications implemented for toast, push, & Discord DMs.

**POV Charts** on Trade Insight interfaces have been revamped. Charts now show future or present data after a position update or when the trade has been closed. Charts still loads to the candle where the last position update has occurred, but now can scroll right to see present data or data after the position update, until it gets to real-time candles.  
\- Fixed bug where chart showed duplicate candles or patterns. It showed the same set of candles or patterns as you scrolled back to historical chart data.  
\- Updated chart library  
\- Fixed other bugs  
\- Work with forex trades  
\- We are aware POV Charts do not work with some crypto exchanges and will be working to resolve this issue.

**Default Market Setting**  
Trader Dashboards now display trades from specific markets based on your default market setting, which can currently only be set through the bot using the $defaults command. For example, if your default market is set to *Forex*, only Forex trades will appear under ‘Latest Trades,’ and performance stats will reflect Forex trades only. The same applies if the default market is set to *Crypto*. If your default market is set to *Stocks*, the dashboard will show both *Stocks* and *Options* trades and stats by default. However, you can use the filters above the performance stats to display only Stocks or Options trades and stats.

Expired trades that are not worthless (-100%) now show on [Trades](https://nvstly.com/trades "NVSTly: Social Investing | Latest Trades") feed. Whereas before, all expired trades did not show on Trades feed to prevent the feed from showing a lot of -100% expired trades at the end of day.

Trader Dashboards now show both *Open* & *Closed* trades, instead of just *Closed* trades.

### Mobile Only

Fixed alignment issue for *P/L* & *Position* columns on dashboards for mobile devices or smaller screen resolutions.

When opening mobile app after install for the first time, it shows Signup/Login UI by default, instead of dashboard that shows the page as broken since not logged in. Or when on mobile browser visiting a page not available without an account, it now redirects you to Signup/Login UI.

### Bot

Forex trades can now be tracked via text message signals or trade sharing, as well submitted through slash commands. *Forex ticker pairs should* ***NOT*** *be separated by* `*/*` *slash. (I.e.* `*USDCAD*`*,* `*USDJPY*` *but* ***NOT*** `*USD/CAD*`*,* `*USD/JPY*`*)*

$daily/weekly/monthly command has been updated to include buttons for *Stocks*, *Options*, *Crypto*, and *Forex* markets.

### On Our Side

Fixed BingX exchange support, and switched to new SPOT endpoint. Previous endpoint had been deprecated.

Updated branding on all Hubert & Peggy or related illustrations.

Added ability to re-auth Schwab data API from admin panel.

### What’s to Come

We don’t usually announce upcoming features until they’re almost ready for release, for various reasons. But here’s a sneak peek of what we’re working on.

*   Futures market support
*   Social posts & comments on trades
*   Market data suite

[![Discord](https://cdn.hashnode.com/res/hashnode/image/upload/v1732187798213/2c709a99-b7d6-4c48-ab73-d012f929ee8f.png)](https://nvstly.com/go/discord)

Join us on Discord!

[![](https://cdn.hashnode.com/res/hashnode/image/upload/v1732187799130/01bc1202-f013-46c0-936f-6e827e5bb565.png)](https://nvstly.com/ios)

NVSTly on App Store

[![](https://cdn.hashnode.com/res/hashnode/image/upload/v1732187799968/22fd2892-1d71-4b7a-b33d-e20a22488192.png)](https://nvstly.com/android)

NVSTly on Google Play