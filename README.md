# Filterlist for AdGuard or Pi-Hole 🖥💟🛡

🧊 This repository is no longer maintained and is archived (no more commits)

![Logo](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/Logo_AG.png)

## Very Important News (as of September 30, 2021)

⚠⚠⚠⚠⚠ℹℹℹℹℹ

_I've made the decision to sunset this repository at the end of September 2021._

Thanks to all who have used this repo 👍

Those who use **AdGuard Home** may wish to check out: https://github.com/hl2guide/AdGuard-Home-Whitelist

I've personally moved my set up to a "block all then manually whitelist" solution.
It locally uses AdGuard Home far more efficiently and directly.

What I've done:

* ✅ modified the script to be more friendly and easier to run
* ✅ open sourced the generator (PowerShell and Python based) for the public
* ✅ commited up until September 30, 2021 and then stopped
* ✅ archived it and will no longer commit to it (no more updates)

My assessment of this repo is that it:
* is too large
* has a wide hit-and-miss ratio
* makes AdGuard Home use too much RAM
* makes manually adding whitelisted sites slow or not apply
* takes too long to generate
* is not the right approach

and that it simply doesn't meet modern requirements.

## Info ℹ

This is a very aggressive filter-list that consolidates over __[370 lists](#filter-lists-%EF%B8%8F)__.

| Supported Software | Official Site | Source Code |
|--|--|--|
| 🛡 AdGuard Home | [official site](https://adguard.com/en/adguard-home/overview.html) | [source code](https://github.com/AdguardTeam/AdguardHome) |
| 🕳 Pi-Hole | [official site](https://pi-hole.net) | [source code](https://github.com/pi-hole/pi-hole) |
| 🕵️‍♀️ DNSCrypt Proxy | [official site](https://dnscrypt.info)  | [source code](https://github.com/DNSCrypt/dnscrypt-proxy) |
| 🔐 SecureDNS | none | [source code](https://github.com/Texnomic/SecureDNS) |
| 👨‍💻 Technitium DNS Server | [official site](https://technitium.com/dns/) | [source code](https://github.com/TechnitiumSoftware/DnsServer) |

## Features

* Includes AdGuard's official **AdGuardSDNSFilter**
* Contains only domains (some with wildcards) and IP addresses (as of v2.57)
* Cleaned, sorted, with duplicates removed
* Updates about every six hours
* Not "set and forget"

## What it Blocks 👁‍

| Threats | Annoyances | Privacy Invaders |
|--|--|--|
| botnets | advertisements | affiliates |
| crypto-lockers | enrichments | analytics |
| data miners | fake sites | invasive telemetry |
| drug sales | social media junk | trackers |
| fake news | spam | some CDNs |
| phishing sites | suspicious sites | widgets |
| ransomware sites | typosquatting |  |
| scam sites |  |  |
| shock sites |  |  |

## Focus 🔍

This repository focuses on the following overall tenants:

| Tenant | Outcome |
|--|--|
| _Blocks Social Media_ | Blocks distractions, time-wasters and nonsense on the internet |
| _Blocks Trackers and Ads_ | Blocks privacy invading aspects of major services |
| _Blocks Security Concerns_ | Blocks some corporation domains (Adobe, Xiaomi etc) |
| _Provides Personal Freedom_ | Does __not__ block websites of an "adult nature" |

Please Note: Naturally this is a balancing act. At times this list will be more restrictive
than you might like.

Please configure a manual whitelist.

## More 📚

* [about page](https://github.com/hl2guide/Filterlist-for-AdGuard/blob/master/ABOUT.md) - Must read vital notes and details
* [usage page](https://github.com/hl2guide/Filterlist-for-AdGuard/blob/master/USAGE.md) - Setup and usage

## Credits ☺️

Full credit for the actual blocking ability goes to original list creators and maintainers.

Thanks so much for their tireless work! 😃

## Filter Lists 🗂️

The included lists are listed:
[here](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_list_URLs.txt).
