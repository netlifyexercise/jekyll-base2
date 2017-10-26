---
layout: post
title:  "DNS Configuration Problems for New People"
date:   2017-10-26 13:46:40
categories: jekyll update
---
First and foremost, I think the most challenging part of trying to configure a DNS is knowing the terminology. I think the way the different components interact is pretty intuitive and straightforward. For example, the slave name servers will have to increment the serial number on their zone files every time it is edited so that ideally it the same as the zone file on the master server. I think a lot of what throws people off is trying to keep all the terminology straight. This was the best article I found on DNS configuration: https://www.digitalocean.com/community/tutorials/an-introduction-to-dns-terminology-components-and-concepts. I think a better way of communicating this info is making gifs of what's going on behind the scenes of the internet. 

Another challenge I think strictly front-end internet users typically face is not having enough time and energy to trouble-shoot their DNS server issues. It's easy to make a silly mistake in the world of electronics and computing like putting a number in the wrong place or making a simple syntax error. 

Personally, I'm trying to turn my old phone into a DNS server so that I can use it instead of calling upon Google servers since I don't want Google to know ALL of my private information. I hit a deadend when I was trying to figure out the DHCP  range of my router. I'm still looking into this as we speak. 
