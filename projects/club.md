---
id: 3
name: Club
orbitSpeed: 30
color: #FF00FF
radius: 5
orbitCCW: false
category: IllyaDrop
---

# CLUB

<a href="https://club.illya.ca" target="_blank" class="buttonLink">Go to club.illya.ca</a>

Club is another installment in my collection of website "art pieces" which is meant to challenge the concept of FOMO and inflated value on meaningless things.

The website keeps track of all users that have entered the website using a simple IAAS API and calculates what percentage of the world has gone on the website with a static constant of approximately how many people exist in the world. It then allows the users to generate a ostentatious certificate to display how special they are for being in the top percentage of people to enter.

| ![Signature Look of Superiority](https://i.kym-cdn.com/photos/images/original/002/008/781/65d.png) | 
|:--:| 
| *Every user after generating a meaningless certificate that says they're special* |



It would be funny if someone botted the site to have a very large amount of people that have visited it... but the integer is accessed via a CORS gateway, so any spam on the website will also spam the CORS service. Maybe you could just take the direct link and spam it on your end, but I'm pretty sure the provider limits how much activity is allowed. And using proxies to spam requests is... you know... illegal.

<img style="max-height: 50vh;" src="../images/noooaha.png" alt="Nooo don't ddos my provider your so sexy aha">

## Features
- Certificate images are stored on the [IPFS](https://ipfs.tech/).
- Utilizes jsPDF to generate certificates.
- Makes people feel better about themselves?

## Status
Finished!