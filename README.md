# tvspy: turn off your smart TV's tracking in 2 minutes

**Live:** https://cranefomo.github.io/tvspy

Most smart TVs run ACR (automatic content recognition). They keep identifying what's on your screen, including your cable box, game console and laptop over HDMI, and use it for ads.

This page shows you exactly which settings to turn off on your TV, step by step, with your remote. No hacking, no ADB, nothing that can break.

## Supported TVs

| Platform | Variants | What it turns off |
|---|---|---|
| Samsung (Tizen) | 2024+, 2018-2023, 2017 and older | Viewing Information Services (ACR), Interest-Based Advertising, Voice Recognition |
| LG (webOS) | 2026+, 2021-2025, 2020, 2019 and older | Live Plus (ACR), ad tracking, User Agreements, home screen promotions, Do Not Sell |
| Xiaomi / Mi TV | Google TV, Android TV | Advertising ID, usage data, PatchWall sponsored home, Xiaomi agreements, location |
| Sony BRAVIA | Google TV, Android TV | Samba Interactive TV (ACR), advertising ID, usage data, agreements |
| TCL, Philips, Hisense, Chromecast | Google TV, Android TV | Advertising ID, usage data, maker agreements (ACR), Apps only mode |
| Roku TV (TCL, Hisense, Roku) | all | Smart TV Experience (ACR), ad tracking, microphone, Privacy Choices |
| Amazon Fire TV | all | Device and app usage data, interest-based ads, ACR on Fire TV smart TVs |
| Vizio | all | Viewing Data (ACR), advertising |
| Hisense VIDAA | all | Viewing Information / Enhanced Viewing (ACR), interactive ads, mic |
| Apple TV | all | App tracking requests, analytics, play history |

## Features

- Pick brand and year, get the exact menu path for each setting
- Checklist with progress, saved in your browser
- Alternative paths when menus differ by firmware or region
- Deep links: `#samsung`, `#lg`, `#xiaomi`, `#sony`, `#googletv`, `#roku`, `#firetv`, `#vizio`, `#vidaa`, `#apple`
- One HTML file, no tracking, no requests to any server

## Honest limits

- Home screen ads are part of the platform. These steps stop **tracking** and **targeting**, not every ad.
- Data collected before you turn it off is not deleted.
- Menu names change by region and firmware. In some regions ACR is off by default and the option may be missing.
- Big firmware updates can ask for consent again. Re-check after them.

## Sources

- [The Markup: Your smart TV knows what you're watching](https://themarkup.org/privacy/2023/12/12/your-smart-tv-knows-what-youre-watching)
- [Roku support: Smart TV Experience](https://support.roku.com/article/115005739288)
- [LG support: settings menu by webOS year](https://www.lg.com/us/support/help-library/how-to-turn-quick-start-on-or-off-on-your-lg-tv--20155512833565)
- [Google TV help: advertising ID](https://support.google.com/googletv/answer/13392198)
- [Sony support: Samba Interactive TV](https://www.sony.com.au/electronics/support/articles/00203482)
- [Apple support: Apple TV privacy settings](https://support.apple.com/guide/tv/atvb66239fa1/tvos)
- [NAI: ad settings on TVs and streaming devices](https://thenai.org/opt-out/connected-tv-choices/)
- [Consumer Reports](https://www.consumerreports.org/electronics/privacy/how-to-turn-off-smart-tv-snooping-features-a4840102036/)
- [Tom's Guide](https://www.tomsguide.com/tvs/your-tv-is-watching-you-how-to-turn-off-data-collection-on-lg-samsung-roku-and-more)
- [Malwarebytes](https://www.malwarebytes.com/blog/news/2026/03/samsung-tvs-stop-spying-on-viewers-in-texas-heres-how-to-disable-acr-anywhere)

Found a wrong path for your model? Open an issue with your TV model and a photo of the menu.

Not affiliated with any TV maker. Made by [@Cranefomo](https://x.com/Cranefomo).
