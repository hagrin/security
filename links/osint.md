# Links

It all starts here -<br />
OSINT Framework - https://osintframework.com/<br /><br />

Bellingcat's Online Investigation Toolkit - https://docs.google.com/spreadsheets/d/18rtqh8EG2q1xBo2cLNyhIDuK9jrPGwYr9DI2UncoqJQ/edit?gid=930747607#gid=930747607<br />
osintui - https://github.com/wssheldon/osintui - Open Source Intelligence Terminal User Interface (requires Rust)<br />

## Email / Phone

Predict A Search - https://www.predictasearch.com/ - get the digital footprint from an email or phone number<br />

## Geolocation

Bellingcat ShadowFinder - https://github.com/bellingcat/ShadowFinder - use shadows in photos to geolocate if you know time of photo<br />
GeoSpy - https://geospy.ai/ - ($$$)<br />
Overpass Turbo - https://overpass-turbo.eu/ - can write scripts against Open Street Map data<br />

## Reverse Image Search

EagleEye - https://github.com/ThoughtfulDev/EagleEye - "You have at least one image of the person you are looking for and a clue about their name. You enter this data into EagleEye and it tries to find Instagram, Youtube, Facebook, and Twitter Profiles of this person."<br />
PimEyes - https://pimeyes.com/ - Face Search Engine Reverse Image Search ($$$)<br />

## Threat Hunting

mihari - https://github.com/ninoseki/mihari - A query aggregator for OSINT based threat hunting.<br />

## Website History / OSINT

BuiltWith - https://builtwith.com/ - Technology used on site<br />
CompleteDNS - https://completedns.com/ - Research domain nameserver changes and drops ($$$)<br />
ViewNDS.info - https://viewdns.info/dnsreport/ - DNS / IP history for a website, has Reverse Whois (has many other tools)<br />
WHOXY - https://www.whoxy.com/ - Domain Search Engine (very basic info)<br />


# Techniques

This is going to be an evolving write-up, I will store it down here for now, but this will get broken out to a more official document later.

## Recon

* Combing through data breaches to take control of email accounts
* Combing through LinkedIn for corporate structure and potential attack list
* Confirming emails exist for a service both through the reset password functions as well as the register new account function
* If Gmail breached, log into Gmail then go to password.google.com to see what passwords the user has saved and what sites they are using
