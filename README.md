# Filterlist for AdGuard 2.3

💚 This repo is actively maintained

![Logo](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/Logo_AG.png)

An aggressive filter-list that consolidates over 90 lists for use in AdGuard Home (https://github.com/AdguardTeam/AdguardHome).

* Includes the official **AdGuardSDNSFilter**
* The final blocklist is cleaned, sorted and then duplicates have been removed

It blocks:

* ads, affiliates, analytics, enrichments, widgets and trackers
* crypto-locker, shock, drug, fake, fake news, and ransomware websites
* scam, spam, suspicious, and typosquatting websites
* data miners, invasive telemetry, and phishing websites

_Please Note: The list is very aggressive so please ensure that you add your own "Custom filtering rules" for domains you want to allow.
e.g: @@||nexusmods.com^$important_

As of version 2.3 the list is more cleaned up, optimized and better than ever.

## News

Version 2.3 is out.
* Added a few new lists
* Additional cleanup done

_The PowerShell generator script now uses a maximum of 11.2GB of RAM for a duration of 50 minutes, yikes!_

## Usage 📐

Check that you are using __AdGuard Home v0.103.3__ or later (hotfixes vital functionality).

Once you have __AdGuard Home__ ready and are logged in, use its main menu to add one __blocklist__ and one __allowlist__.

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/example%20menu.PNG "Menu")

### Blocklist 🛑

https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_blocklist.txt

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/example%20blocklist.PNG "Blocklist")

### Allowlist ✅

https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_whitelist.txt

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/example%20whitelist.PNG "Whitelist")

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
