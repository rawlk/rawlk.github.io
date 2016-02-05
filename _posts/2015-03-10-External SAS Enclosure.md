---
layout: post
section-type: post
title: External SAS Enclosure
category: tech
tags: [ 'projects','personal' ]
---
As yet another test post, I've decided to post about a quick little project that I've been planning on doing for a while :) <br>

SO! The idea is to take this thing -> [Mercury Rack Pro Quad](https://a248.e.akamai.net/f/1949/3326/8/www.blogcdn.com/www.engadget.com/media/2009/01/ces09-mercury_rack_pro_quad_interface.jpg) and make it into an external hdd controller that DOESN'T use esata, usb or firewire.

I popped it open several months ago and with great suprise I was greeted with a 'stand alone' sort of hardware raid card. The raid card just had 4 sata cables coming off of it to a really basic backplane that the drives slid into. AWESOME. Since the power supply was completely independant, the whole thing <i>should</i> work whithout the raid card.
<img src='/img/74499e38069c5853.jpg' alt='Opened Mercury Rack Pro Quad' style='width: 250px;'/>

SO, I hit up the guys on the freenas forums to see if I could somehow use my internal raid card on my storage box out and over to this thing. Since its mini sas inside, I decided through a few adapters I could get it out, over, back in and broken out to sata... relatively easily. :)

That particular slot adapter just had two independant cards that would pass mini sas out.. It was going to almost double the price to get two singles, so I decided to just opt for one double for like 7$ more, and just take the card out. Ended up using a dremel to cut a square out the back and mounted the card with hotglue - - Thanks @ira787!

<img src='/img/eeabd44cc3_200x166.jpg' alt='Breakout built in' style='width: 250px;'/>
Low and behold, it worked. I now have 4 more full speed drives at my disposal. MUAHAHA

<img src='/img/c45173638c_200x160.jpg' alt='Array Under Couch' style='width: 250px;'/><img src='/img/9157b10968f4a5e7.png' alt='14Drives' style='width: 250px;'/>
Now.. I just have to get rid of the rest of my seagates....
