# Protocol amplification attacks

#### What is this repo?
This is a repo of daily, weekly, and monthly reports I'm generating based on ongoing protocol amplification attacks.


#### Which protocols does this track?:
1. DNS
2. NTP
3. Chargen
4. QoTD
5. SSDP

#### How is the data being collecting?
Honeypots. Currently I'm running 6 honeypots that appear to be offering vulnerable versions of the abovementioned protols. These honeypots end up in lists of open XXX (where XXX is the protocol in question) servers -- i.e. open DNS recursors, open NTP servers, etc. Bad people then try to abuse these honeypots to attack websites/servers/etc. Of note: these honeypots are **heaily* rate limited, and as such will not actually contribute in any meaningful way to an attack that is leveraging these protocols.

#### How much data do have so far?
As of April 24th, 2016 -- roughly 1.4 **billion** rows of data where one row equals a single amplification event. I've been collecting data since mid-February 2016. The 6 honeypots currently add roughly 25 **million** new rows per day.
