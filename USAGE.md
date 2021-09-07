# Notes 📒

The below information relates to what I personally use and recommend people consider using.

Please assess what is best for you.

# Other Supported Software 👩‍💻

For Pi-Hole, DNSCrypt Proxy, SecureDNS or Technitium DNS Server configuration please refer to their official documentation and then add blocklists and then the whitelist.
 see [lists](https://github.com/hl2guide/Filterlist-for-AdGuard-or-PiHole/blob/master/USAGE.md#lists-).

# Usage for AdGuard Home 🛡

Check that you are using __AdGuard Home v0.106.3__ or later
(vital functionality was hotfixed).

## DNS Settings within AdGuard 🥅

I personally use and recommend people consider using Quad9 (https://www.quad9.net/) as their DNS.

Quad9 tops the speed and reliaility tests for my location; they offer Malware Blocking, support DNS-over-TLS and also DNSSEC.

They are also now "incorporated in Switzerland to guarantee privacy for global DNS users" (quad9).

* _(optional)_ To test it at your location run the tool: [GRC Domain Name Speed Benchmark for Windows/Linux](https://www.grc.com/dns/benchmark.htm)

### Upstream DNS servers 🔼

tls://dns.quad9.net

### Bootstrap DNS servers 🥾

9.9.9.9

### DNS server configuration ⚙

Check/tick the "Enable DNSSEC" checkbox and click the green __Save__ button.

## Lists 📓

Once you have __AdGuard Home__ ready and are logged in, use its main menu to add
multiple __blocklists__ and one __allowlist__ (below).

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/example%20menu.PNG "Menu")

Type | Link (URL)
--------- | -----
📗 Allowlist | [filter_whitelist.txt](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_whitelist.txt)
🛑 Blocklist (1 of 4) | [filter_blocklist1.txt](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist1.txt)
🛑 Blocklist (2 of 4) | [filter_blocklist2.txt](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist2.txt)
🛑 Blocklist (3 of 4) | [filter_blocklist3.txt](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist3.txt)
🛑 Blocklist (4 of 4) | [filter_blocklist4.txt](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist4.txt)

### Optional Modular Whitelists

These are [additional whitelist modules](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard-or-PiHole/master/Whitelist-Modules/__urls_list.txt)
 that are only recommended if you use the specific products on your network.

## Filters Update Interval ⏱

You can modify how often filter lists are updated within Adguard Home in the
__Settings__ > __General Settings__ page.

Set "Filters update interval" to 12 hours _(recommended)_ and click the green "Save" button.
This list updates around twice per day.

# Browsers 🌏

A mix of Internet Browser Addons/Extensions can improve your security and privacy further.

These are best security and privacy focused internet browser extensions/addons in my opinion.

## Mozilla Firefox Users 🦊

Install using this [collection](https://addons.mozilla.org/en-US/firefox/collections/3899969/BestSecurityPrivacy/?page=1&collection_sort=name).

## Microsoft Edge, Brave, Vivaldi and Google Chrome Users 🌐

Visit the offical [Google Chrome Webstore](https://chrome.google.com/webstore/category/extensions):

_Manually add:_

- [AdGuard AdBlocker](https://chrome.google.com/webstore/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg)
- [ClearURLs](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk)
- [Decentraleyes](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj)
- [DuckDuckGo Privacy Essentials](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflcldnnnapblkhphbgpggdiikppg)
- [Emsisoft Browser Security](https://chrome.google.com/webstore/detail/emsisoft-browser-security/jfofijpkapingknllefalncmbiienkab)
- [HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp)
- [I don't care about cookies](https://chrome.google.com/webstore/detail/i-dont-care-about-cookies/fihnjjcciajhdojfnbdddfaoknhalnja)
- [LocalCDN](https://chrome.google.com/webstore/detail/localcdn/njdfdhgcmkocbgbhcioffdbicglldapd)
- [Malwarebytes Browser Guard](https://chrome.google.com/webstore/detail/malwarebytes-browser-guar/ihcjicgdanjaechkgeegckofjjedodee)
- [Never-Consent](https://chrome.google.com/webstore/detail/never-consent/pgahndjfiejekcbidhejmpplgdhejdpb)
- [Privacy Badger](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp)
- [Privacy Pass](https://chrome.google.com/webstore/detail/privacy-pass/ajhmfdgkijocedmfjonnpjfojldioehi)
- [SponsorBlock - Skip Sponsorships on YouTube](https://chrome.google.com/webstore/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone)

# Software-Level Firewall 🔥

I personally also use [SimpleWall](https://www.henrypp.org/product/simplewall) to have a baseline protection on an application level.

# Windows 10 Antispy Tool 🕵️‍♀️

If you use Windows 10, please use [O&O ShutUp10](https://www.oo-software.com/en/shutup10) to disable spying features initially and then after each major update.
