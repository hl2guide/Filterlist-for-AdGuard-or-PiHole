# Filterlist for AdGuard 2.45 🖥💟🛡

💚 This repo is actively maintained and updates about twice per day

![Logo](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/Logo_AG.png)

## About ℹ

An very aggressive filter-list that consolidates over __205 lists__ for use in
AdGuard Home (https://github.com/AdguardTeam/AdguardHome).

* Includes the AdGuard's official **AdGuardSDNSFilter**
* The final blocklist is cleaned, sorted and then duplicates have been removed

### VITAL NOTES 👀

* The list is very aggressive so before using this list please ensure that you add your own
"Custom filtering rules" for domains you want to allow
e.g: `@@||nexusmods.com^$important`
* The blocklist is around 80MB so if you're internet plan is data limited please account for
about 2400MB (2.4GB) per month, if AdGuard Home is set to update once per day
* As of __version 2.45__ the list is more cleaned up, optimized and better than ever
* Version __2.45__ is a preparation release before version __2.5__

It's a BIG change so please report any false positives for domains

### What it Blocks 👁‍

* ads, affiliates, analytics, enrichments, widgets and trackers
* crypto-locker, shock, drug, fake, fake news, and ransomware websites
* scam, spam, suspicious, and typosquatting websites
* data miners, invasive telemetry, and phishing websites
* social media junk and various CDNs

## News 📰

* Version 2.5 is under development
  * Will complete integration of a Python script to solve slow AIO list generation
  (down to a very reasonable 3 minutes, in early tests)
  * Having it generate much more quickly, will encourage me to update this repo more often

* Version 2.45 is released, now uses a hybrid Python/PowerShell generator script that generates within 3 minutes

## Usage 📐

Check that you are using __AdGuard Home v0.104.3__ or later
(vital functionality was hotfixed).

Once you have __AdGuard Home__ ready and are logged in, use its main menu to add
one __blocklist__ and one __allowlist__.

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/example%20menu.PNG "Menu")

### Blocklist 🛑

https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_blocklist.txt

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/blocklist.JPG "Blocklist")

### Allowlist ✅

https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_whitelist.txt

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/allowlist.JPG "Whitelist")

### Filters Update Interval ⏱

You can modify how often filter lists are updated within Adguard Home in the
__Settings__ > __General Settings__ page.

Set "Filters update interval" to 12 hours _(recommended)_ and click the green "Save" button.
This list updates around twice per day.

## Suggestions 📌

Do you have a new host list you'd like to suggest?

Please first check that the list does not already exist in the
[list file](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_list_URLs.txt)
then create an issue.

## Request Forms

* [Blacklist Request Form](https://docs.google.com/forms/d/1NrlR3yddEWhIkmKXV8VamBVka6SX7DLHX_WgpsqrtbE)
* [Whitelist Request Form](https://docs.google.com/forms/d/1mobsqVCIky61tHy13fFyGZBxdbjUmTi3EFkvvhoGIHg)

## Credits ☺️

Full credit for the actual blocking ability goes to original list creators and maintainers.

Thanks so much for their tireless work! :D

## Filter Lists 🗂️

The included lists are listed
[here](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_list_URLs.txt).
