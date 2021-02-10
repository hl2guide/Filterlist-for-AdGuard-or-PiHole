# Filterlist for AdGuard 2.50 🖥💟🛡

💚 This repo is actively maintained and updates about twice per day

![Logo](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/Logo_AG.png)

VITAL NEWS (6 Feb 2021): BE SURE TO UPDATE THE ITEMS IN ADGUARD HOME

* My solution is to split the blocklist text file into [three parts](#lists-).
* 2.60 is in early development and will use more regular expression rules

## About ℹ

A very aggressive filter-list that consolidates over __310 lists__ for use in
AdGuard Home (https://github.com/AdguardTeam/AdguardHome).

* Includes the AdGuard's official **AdGuardSDNSFilter**
* Is cleaned, sorted, with duplicates removed

### VITAL NOTES 👀

* Please learn AdGuard Home's interface before using this list
* The list is very aggressive so before using this list please ensure that you add your own
"Custom filtering rules" for domains you want to allow
e.g: `@@||nexusmods.com^$important`
* Since everyone uses the internet differently please be aware that some initial
manual whitelisting is required
* The blocklist is around 120MB so if you're internet plan is data limited please account for
about 3000MB (3GB) per month, if AdGuard Home is set to update once per day
* The list is more cleaned up, optimized and better than ever

It's a BIG change so please report any false positives for domains.

### What it Blocks 👁‍

* advertisements, affiliates and analytics
* botnets, crypto-lockers and data miners
* drug sales, enrichments and fake sites
* fake news, invasive telemetry and phishing sites
* ransomware websites, scam and shock sites
* social media junk, spam and suspicious sites
* trackers, typosquatting, some CDNs and widgets

### Focus 🔍

This repo focuses on the following overall tenants:

* Blocks distractions, timewasters and nonsense on the internet
    * _Blocks Social Media_
* Blocks privacy invading aspects of major services
    * _Blocks Trackers and Ads_
* Blocks some corporation domains (adobe, xiaomi etc)
    * _Blocks Security Concerns_
* Does not block websites of an "adult nature"
    * _Provides Personal Freedom_

## Usage 📐

For more information view the [wiki](https://github.com/hl2guide/Filterlist-for-AdGuard/wiki).

Check that you are using __AdGuard Home v0.104.3__ or later
(vital functionality was hotfixed).

Once you have __AdGuard Home__ ready and are logged in, use its main menu to add
multiple __blocklists__ and one __allowlist__ (below).

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/example%20menu.PNG "Menu")

### Lists 📓

Type | Link (URL)
--------- | -----
📗 Allowlist | [filter_whitelist.txt](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_whitelist.txt)
🛑 Blocklist (1 of 3) | [filter_blocklist1.txt](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist1.txt)
🛑 Blocklist (2 of 3) | [filter_blocklist2.txt](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist2.txt)
🛑 Blocklist (3 of 3) | [filter_blocklist3.txt](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist3.txt)

### Filters Update Interval ⏱

You can modify how often filter lists are updated within Adguard Home in the
__Settings__ > __General Settings__ page.

Set "Filters update interval" to 12 hours _(recommended)_ and click the green "Save" button.
This list updates around twice per day.

## Credits ☺️

Full credit for the actual blocking ability goes to original list creators and maintainers.

Thanks so much for their tireless work! 😃

## Filter Lists 🗂️

The included lists are listed
[here](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_list_URLs.txt).
