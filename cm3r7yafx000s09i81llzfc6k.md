---
title: "Superspeed, Webull Integration Open Beta, Referral System with Cash Rewards, & More on v2.2"
seoTitle: "Superspeed, Webull Integration Open Beta, Referral System with Cash Re"
seoDescription: "This latest update brings epic improvements, long-awaited features, and numerous changes. Both the app and Discord bot have received upgrades to increase..."
datePublished: Thu May 30 2024 17:56:03 GMT+0000 (Coordinated Universal Time)
cuid: cm3r7yafx000s09i81llzfc6k
slug: superspeed-webull-integration-open-beta-referral-system-with-cash-rewards-more-on-v2-2-823a3e1511e1
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1732187899743/67ceca5e-981e-499b-800e-afdcd9d41e7c.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1732204734171/13ce277b-7812-43a9-b29d-7327752f3f1a.png
tags: startups, startup, social-media, crypto, forex, cryptocurrency, finance, fintech, trading, economy, investing, stocks, futures, stockmarket, tradingplatfrom

---

This latest update brings epic improvements, long-awaited features, and numerous changes. Both the app and Discord bot have received upgrades to increase speed and responsiveness. Brokerage integration is finally here, starting with Webull, and the open beta is now live. We’ve also introduced a referral system where users can earn cash rewards for inviting other traders. And there’s much more, so keep reading!

Over the past few weeks, we’ve focused heavily on enhancing user experience by increasing the speed and responsiveness of both the app and Discord bot. We’ve made changes to ensure the global [Trades feed](https://nvstly.com/trades "NVSTly: Social Investing | Latest Trades") updates in real-time and loads trades quickly. Try scrolling down the Trades feed — you’ll notice how much faster it is to load more trades, even for options. The [Leaderboard rankings](https://nvstly.com/ranks "NVSTly: Social Investing | Rankings") have been overhauled, now loading in under a second compared to up to half a minute before. Submitting trades to the bot on Discord is also much faster, with stock and crypto trades processed in under a second and options trades around one second or less — a 300–900% speed increase. We’re currently refining options data, so you might encounter some minor issues, but they shouldn’t significantly impact user experience. Expect these to be resolved within the next week.

Brokerage integration is finally here! We’ve been talking about it since the end of 2021, and now it’s available. We’re conducting open beta testing for Webull. Users can now link their Webull brokerage account with the NVSTly platform and enjoy hands-free, automated trade submissions. This allows users to auto-track their trades, automate trading signals, or automatically share trades to Discord and social media. After connecting Webull, any trades executed within your broker account will be instantly shared with the app. We’re monitoring all broker-submitted trades to identify any issues with open/average/partial/close events and TP/SL settings. If trades aren’t logged as intended, we’ll reach out to gather feedback so we can refine the system and move on to the next broker. Please report any issues or trade position fixes in our #help channel on [Discord](https://nvstly.com/go/discord "NVSTly Discord Server"), by sending a DM to our support bot, or by emailing [team@nvst.ly](mailto:team@nvst.ly "NVSTly Contact").

[Original post](https://nvstly.com/blog/Superspeed-Webull-Integration-Open-Beta-862082)

NVSTly v2.2 Changelog

### v2.2 Changelog

[v2.1 Changelog](https://nvstly.com/blog/v2-0-Is-Complete-Mobile-585417 "NVSTly v2.1 Changelog")

### App

Increased overall speed of the app & Discord bot through various methods including the utilization of caching. Slimmed down options data being fetched when submitting trades. Added caching for Leaderboard/Ranks, they now load instantly. Updates in 30 minute intervals to calculate any new trader stats. Increased Trades feed speed when loading new trades by slimming down data being fetched. Implemented worker threads to speed up responsiveness of some elements on the app. And more.

Webull integration to auto submit trades when a Webull broker account is linked. See [Webull Integration](https://docs.nvstly.com/info/broker-integration/webull-integration "NVSTly Documentation: Webull Broker Integration") documentation to learn how to connect. *2FA is required to connect.*

Referral system implemented. Users can earn cash rewards for **every** successful billing period from their invitees. Rewards are 10%/15%/20% for free/PRO/PRO+ members. Generate a referral code, link, and QR image in [*Account Settings*](http://nvstly.com/settings/profile "NVSTly Account Settings: Profile") to get started. Minimum balance of $5 required to request payout. Payment methods include CashApp, PayPal, and any cryptocurrency listed on the Coinbase exchange. Invited someone who has already signed up? Ask them to input your referral code in [*Membership Settings*](https://nvstly.com/settings/membership "NVSTly | Account Settings: Membership"). Check out the [documentation](https://docs.nvstly.com/info/readme/referral-system-and-payouts "NVSTly Documentation: Referral System & Rewards") & [service terms](https://nvstly.com/terms#section-7 "NVSTly Terms of Service: Section 7: Referrals & Payouts") for more info.

Added Two-factor Authentication security. *(A prerequisite for brokerage integration)*  
Changed QR code for 2FA settings UI to be white-on-black rather than black-on-white  
2FA codes now have more leniency, inputting 2FA codes that expired few seconds ago will still work.  
Made 2FA codes only a one-time use as they should have already been, can’t use the same 2FA code for more than one action requiring 2FA.

When TP/SL is set, changed, removed, or triggered, now sends as a trade notification. For Trade Sharing; Setting, changing, or removing is utilized through an Update event and values are done through Trade Notes. When triggered, it is utilized through a Close event.

Implemented average exchange fees onto all crypto trades. This fee subtracts from the overall profit/loss on every individual crypto trade, including all trade history or previous trades. [Fees vary by exchange.](https://docs.nvstly.com/submit-crypto-trades-on-discord/supported-exchanges#exchange-fees "NVSTly Documentation: Supported Exchange & Deducted Fees") Added fee amount to `[[trade.return]]` property for [*Trade Sharing*](https://docs.nvstly.com/trade-sharing/trade-sharing-overview "NVSTly Documentation: Trade Sharing").

Various changes regarding Stripe, mostly on our side with some consumer facing changes.  
Added support for [CashApp](https://cash.app/app/T4SRMMV "CashApp Referral") & Amazon Pay payment methods.  
Changed any other unnoticed branding from *Trade Hub* to *NVSTly*.  
Updated all links to use nvstly.com from *nvst.ly*, fixed any missing or broken links.  
Statement descriptors for PRO/PRO+ now show as `NVSTLY PRO MEMBRSHP` and `NVSTLY PRO+ MEMBRSHP` changed from `TRADEHUB PRO MEMBRSHP`  
Fixed issue with receipts not being sent to emails.  
Added no-refund info on receipts and some payment links.  
Stripe now deals with account email changes.  
Added better handling for managing subscriptions, switching (upgrading/downgrading) membership plans, and added a *Cancel Membership* button to be able to cancel subscription with more ease & less confusion than using the *Manage Membership* button.

Removed exchange support for BitForex due to [potential exit scam](https://finance.yahoo.com/news/hong-kong-based-crypto-exchange-045609957.html "Yahoo Finance: BitForex Potential Exit Scam") and being shut down.

### Web

Added the ability to change email via [*My Profile*](https://nvstly.com/settings/profile "NVSTly Account Settings: Profile") section of *Account Settings*.

Login button bug fuxed. After invalid password, would get stuck loading indefinitely and could not be clicked on after putting in new password. (Hitting the *Enter* key worked.)

Basic filter settings & buttons on [Trades feed](https://nvstly.com/trades "NVSTly: Social Investing | Trades") now work.

For [guild/server-only Leaderboard/Ranks](https://docs.nvstly.com/discord-bot-setup/server-only-leaderboard "NVSTly Documentation: Server-only Leaderboard"), all traders will be ranked & displayed regardless of win rate. [Global Leaderboards](https://nvstly.com/ranks "NVSTly: Social Investing | Rankings") still only show ranked traders with win rates of 50% or above.

Added captcha for signups and email changes.

Notification UI design text overlapping has been fixed.

Notifications for Average events has been fixed. (Was using Partial event template previously)

Improved floating UI components.

Fixed page titles.

Page now reloads when switching languages.

Added confirmation dialog to *Disconnect Account* button for [*Linked Accounts*](https://nvstly.com/settings/sharing "NVSTly Account Settings: Sharing") within *Account Settings*.

Fixed spacing issue on *Trade Insight* UI.

Changed text on Trade Delay settings from *15-min Delay* to *Configurable Delay*.

Changed [X/Twitter](https://x.com/nvstly "NVSTly on X.com") preview on *Trade Sharing* message builder to reflect NVSTly handle.

### Bot

Fixed *Close/Exit* bot trigger aliases & added more. `Sell`, `selling`, `sold`, `close`, `closing` now work again, `exit` and `exiting` aliases added.

Updated *Invalid ticker symbol* error to include possible error for options trades with non-existent contracts and to re-check details.

Properly syncing roles when iOS in-app purchase is made.  
Properly syncing roles when Discord is linked to an NVSTly account.  
Properly syncing roles when a user’s membership is modified.

Fixed the permissions checklist. Since v2, we were not sending a permissions checklist when the bot didn’t have required perms in a channel for it to work. So it now sends the checklist with all the permissions it has and which one(s) are missing. Will send checklist in the channel if it has perms to send messages, otherwise it will send checklist via DM.

Automated the updating of channel name displaying how many guilds/servers the bot is in.

**Commands:**  
Fixed `adminperms` slash & text command.  
Small bug fix & added Discord ID support for `daily`/`weekly`/`monthly`, `rep`, `follow`/`unfollow`, `stats`, & `chart` commands.

### On Our Side

User edit UI implemented. (Ability to assign/remove badges, membership/trial assignment, user permissions, etc.)

Upgraded UI for New Blog.

Added *Copy ID* on trader dashboards to easily copy a user’s ID.

Registering slash commands on bot is done more efficiently now.

Added custom generated banners to all Tickerbot bios.

Added confirmation dialog when deleting a ticker bot.

### What’s To Come

*   X/Twitter integration is coming back, with the ability to automate the posting of trades utilizing their API
*   Forex market support. (Futures will come some time after)
*   More TBA

[![NVSTly: Social Investing on Google Play](https://cdn.hashnode.com/res/hashnode/image/upload/v1732187896865/cfff90d6-65f7-4f82-b540-21a7c3ce648d.png)](https://play.google.com/store/apps/details?id=ly.nvst.android)

[![NVSTly: Social Investing on App Store](https://cdn.hashnode.com/res/hashnode/image/upload/v1732187897507/a95ce252-9f7b-4d79-83f1-b7844733e893.png)](https://apps.apple.com/us/app/nvstly-social-investing/id6475617649)