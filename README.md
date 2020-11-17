# Galopp-Scraper
### Horse racing history scraper for the webpage galopp-statistik.de

Galopp-Scraper is a script build with [BeautifulSoup] that scrapes all the races that are in their database on https://www.galopp-statistik.de/DisplayErgebnis.php?id= ,where at the end is an ID for the corresponding race (rangin from 0 up to 9214, resulting in 9215 races).

It is meant to be used later on in an machine learning program for ranking horses in a race. But for further usability i also scrape more information that ar enot explicitly necessarry for my (direct) goals.

### Contents
The contents of this repository are organized as...:

  - Galopp-Scraper.py: The entry point of the script
  - Notes: My plans and notes of developing this script

### Installation

The script requires Python3 to run.
Install additional dependencies from the requirements.txt file and run galopp-scraper.py

```sh
$ pip3 install -r requirements.txt
$ python3 galopp-scraper.py
```

### Donations

BTC: 1DixZsj9HdRMCD16co1BbhXfJoaUrEptcE

ETH: 0xf5d23ad5b592a6f078ca18aa5eecc55edb1ce532


[//]: # (These are reference links used in the body)
   [BeautifulSoup]: <https://www.crummy.com/software/BeautifulSoup/>