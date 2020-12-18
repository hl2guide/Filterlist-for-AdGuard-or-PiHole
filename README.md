# Filterlist for AdGuard 2.4 🖥💟🛡

💚 This repo is actively maintained

![Logo](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/Logo_AG.png)

## About ℹ

An aggressive filter-list that consolidates over __120 lists__ for use in AdGuard Home (https://github.com/AdguardTeam/AdguardHome).

* Includes the official **AdGuardSDNSFilter**
* The final blocklist is cleaned, sorted and then duplicates have been removed

It blocks:

* ads, affiliates, analytics, enrichments, widgets and trackers
* crypto-locker, shock, drug, fake, fake news, and ransomware websites
* scam, spam, suspicious, and typosquatting websites
* data miners, invasive telemetry, and phishing websites
* social media junk and various CDNs

> VITAL: The list is very aggressive so please ensure that you add your own "Custom filtering rules" for domains you want to allow.
e.g: `@@||nexusmods.com^$important`

As of version 2.4 the list is more cleaned up, optimized and better than ever.

## News 📰

* Version 2.5 is under development
  * Will integrate a Python script to solve slow AIO list generation (down to a very reasonable 3 minutes, in early tests)
  * Having it be much faster to generate will encourage me to update this repo more often
  * [2.5 Alpha 1 is live](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/2.5%20ALPHA%201/filter_blocklist.txt), contains over 205 block lists and weighs around 83MB (only use it as an early tester who wants to report issues)
  
* Version 2.4 is released and stable

_The PowerShell generator script now uses a maximum of 7GB of RAM for a duration of 50 minutes (thanks to https://github.com/tamada/uniq2)_

## Usage 📐

Check that you are using __AdGuard Home v0.104.3__ or later (hotfixes vital functionality).

Once you have __AdGuard Home__ ready and are logged in, use its main menu to add one __blocklist__ and one __allowlist__.

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/example%20menu.PNG "Menu")

### Blocklist 🛑

https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_blocklist.txt

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/blocklist.JPG "Blocklist")

### Allowlist ✅

https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_whitelist.txt

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/allowlist.JPG "Whitelist")

### Filters Update Interval ⏱

You can modify how often filter lists are updated within Adguard Home in the __Settings__ > __General Settings__ page.

Set "Filters update interval" to 1 hour and click the green "Save" button. This list updates sporadically.

## Suggestions 📌

Do you have a new host list you'd like to suggest?

Please first check that the list does not already exist in : https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_list_URLs.txt

Then create a new GitHub issue with the prefix "[add host list]" if it's new.

## Credits ☺️

Full credit for the actual blocking ability goes to original list creators and maintainers.

Thanks so much for their tireless work! :D

## Filter Lists 🗂️

The included lists are:

<https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_list_URLs.txt>
