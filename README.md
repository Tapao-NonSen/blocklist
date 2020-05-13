# Blocklist For Pi Hole
I find the ads list and add them together for easy to add to pi-hole and use less time to update gravity all becuase all url is in the one file

Blocklist: porn, ads, youtube ads, malware, tracking, ads server, and much more

if this list blocklist block some service please let me know just open the issuse

### This code had been archived you can pull request for edit it thank you :3
# Recommend Blocklist
This is list add cant make them with my own 

Ads Server Block: https://raw.githubusercontent.com/EnergizedProtection/block/master/ultimate/formats/hosts.txt

Ads Block: https://hosts-file.net/ad_servers.txt

Youtube Ads Block: https://github.com/kboghdady/youTube_ads_4_pi-hole

# How to install?
1. copy the raw url of blocklist 
```
https://raw.githubusercontent.com/outapzaza/blocklist/master/list.txt

https://raw.githubusercontent.com/outapzaza/blocklist/master/fingerprintblock.txt 

https://raw.githubusercontent.com/outapzaza/blocklist/master/serverblocklist.txt

https://raw.githubusercontent.com/outapzaza/blocklist/master/regex.txt
```

2. open your pi hole admin panel -> click settings -> Blocklist

3. Paste the raw url to the input box then click save and update


# How to update?

**Website**

admin panel -> settings -> blocklist then click `save and update`


**Commands line**

open you terminal then put `pihole -g` for update
