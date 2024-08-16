---
id: 5
name: Manticore Interactive
orbitSpeed: 20
color: #FF0000
radius: 30
category: Business
orbitCCW: true
---

# Manticore Interactive

<a href="https://manticoreinteractive.com" target="_blank" class="buttonLink">Go to manticoreinteractive.com</a>

Manticore Interactive is a company I started way back in my first year of university. It had a focus on everything from app/game development to providing VPS hosting for developers. The idea which spawned the company was to force every developer to follow the *"Rapid Deployment Architecture" (RDA)* idea I came up with.

| ![Logo](https://manticoreinteractive.com/src/ico.svg) | 
|:--:| 
| *The logo I came up with. Can you see the Manticore?* |

## The Idea

What kills projects? Difficulty? Cost? Gremlins? No, it's Time.

| ![Thyme](https://upload.wikimedia.org/wikipedia/commons/e/ea/Thyme-Bundle.jpg) | 
|:--:| 
| *Thyme - so NOT this* |

The point of the RDA was to restrict developers and artists to projects which groups could do in a short amount of time, then quickly deploy each project on our servers. 

> *"What a good idea! This will fix all our problems."*  
> — Every producer who will "fix it in post"

### How does it work?

Developers can essentially create "forum posts" of ideas they have, and others (developers or artists) who are perusing can *opt-in* to working on the project. Once the project has garnered enough attention, higher-ups will negotiate a time frame, and everyone gets to work completing the project within that specified limit. These posts are not generic back-of-the-napkin ideas. In order to submit something, you must develop a full plan and show a genuine interest in doing it. Also, not everyone is allowed in, you have to be manually proved (based on capability) and show that you have an interest in this form of development.

Once time is up, unless discussed otherwise, the closest functional build gets deployed to our servers. We also advertise the project throughout to give it a standing chance. If the project is not performing well, it is slowly phased out with lower and lower resources until it gets a *rock bottom* server, which still works, but supports very few users based on its requirements. If the project takes off, we can allocate more and more resources to it, and continue its development.

### "Money, money, money!!" - Tax Auditor, Gazillionaire

| ![Tax Auditor](https://lparchive.org/Gazillionaire-Deluxe/Update%2011/10-TAX.gif) | 
|:--:| 
| *This guy* |

We take a fixed amount from profits relative to the resource allocation to keep the servers afloat, then a small percentage after that, but the developers and artists get dividends based on their contribution amount. This is negotiated dynamically as development continues, but is effectively the amount of work they contributed to the project as reviewed by higher ups.

The reason we take percentages is to keep the company alive and to offer the opportunity for more projects to prosper. The developers and artists only invest their time, while we take on all the financial risk. Your project failed? No biggie. In fact, it'll exist on a low-resource server for as long as the company stays alive, despite offering us no money. Is it getting some attention a few years later? After it gets out of the red, you get very fair percentages of the profits.

## Project: *Click*

I wanted to start off my crew with a simple idea I had a while back... a global clicker game!

<a href="https://click.manticoreinteractive.com" target="_blank" class="buttonLink">Go to click @ manticoreinteractive</a>

A webapp which has the simple premise of users being able to either increase a global value, or decrease it.

<img style="max-height: 50vh;" src="../images/pp_or_mm.png" alt="Which side are you on?">

I learned a lot from implementing this concept and also the account system. I also designed the website and was very satisfied with how I implemented the *neumoprhic* style I wanted one of my sites to have. As someone who isn't satisfied until things are juuuust right, you can imagine how much time I spent on the design aspects. It's also all in VanillaJS.

The only thing lacking from the webapp is the implementation of global upgrades and a functional chat, both of which would have required more than just the Firebase backend I was using to fulfill my requirements.

## What Happened?

> *"Did it work? Ehhhhhh..."*  
> — Every producer after they "fixed it in post"

Many developers do not support this type of work. Most who go into software development typically only do so with the prospect of making money, whereas this is mostly about learning and developing projects with minimal losses on the end of the users. 

In essence, it's what I would have wanted when I was a kid making software projects for the first time... but that's not what the majority wants.

I can only blame myself for thinking anyone would have wanted something like this, or that it would have been remotely profitable if not supported by others. This relies on a high hit-rate of successful projects, which is unlikely given the restrictions of the company.

## Post Mortem?

Although the company is not dead, it's not active in any meaningful way either. Attempts have been made to try to revive it, but it is simply not feasible with my current situation.

That being said, the page for the company was entirely my idea, and was executed how I had envisioned from the start. By implementing the design exactly how I wanted I learned a lot about front-end development.

**... Also, I pivoted to supplying users with VPS services!**

## Servers!

I got into personally hosted servers because I was experimenting with fulfilling the requirements of *click*. If it weren't for this simple idea, it could have taken me much more time to get into linux, high-uptime server management, homelabs, and general system admin stuff.

<img style="max-height: 50vh;" src="../images/homelabwalksin.png" alt="We decided to pivot...">

I even wrote my own software to handle network security (*Sentinel*). It works pretty well, and runs on a DMZ behind a firewall. I route most traffic through a Cloudflare proxy which adds that additional layer of security, but I have been able to expose some servers without a proxy to the public with my software actively mitigating attacks. It's been... alright... but I fear that experienced attackers would be able to get through.

As of right now, I rent out the little server rack I built in my living room to folks for a very reasonable rate. This service isn't even advertised on the website since it's more of an informal arrangement. I offer resource rates better than you can find anywhere else... if you're okay with the only backup during an outage being a single UPS... which supports all my servers and network hardware.

<font size="1">  
<p style="font-style: italic;">No, this isn't advertising for this service. This is probably not compatible with you. I can't guarantee an uptime of above 99%, and everyone I work with understands these risks. I also can't offer huge bandwidth. It's mostly for learning on the cheap without having to worry about keeping a server online in your house.</p>
</font> 

## Outcome
- Learned a lot about management.
- Developed multiple websites and whitepages for ideas regarding the project.
- Worked with Firebase to implement user account functionality and Firestore real-time databases to handle project-specific tasks.
- Worked a lot with Linux servers, developed a firm understanding of networking and system administration.
- Successfully implemented many design ideas I came up with. 

## Status
Halted - though the project may resume in the future.