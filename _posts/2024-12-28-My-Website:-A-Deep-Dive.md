---
layout: post
title: "My Website: A Deep Dive"
date: 2024-12-28
categories: blog
---
  I guess the first order of business is to talk about this website I've made, and all of the fun issues I faced before I started posting...

  This here was a long process, and the seed was planted a last year when I finally got my first PC. Over the summer of 2024, I got my first job as an Electronics Repair Technician, and with the first paycheck I made, I bought myself a used gaming PC so I could finally **GAMEEE**! This started my foray into the world of PC's, and eventually, around September of this year, I started thinking about servers and hosting a couple services for myself. After buying another used PC, I decided to make a NAS (network attached storage), a small backup system for my notes, and also self host a website. Homelabs for the win! I'll get into the NAS and my server stuff as a whole in a different post, but for now, the main point was I wanted a website for myself.

  Now, let me come clean about something. I don't know how to code. Scandalous, I know! I have taken classes which have taught me to use C, C++, and Java, and I learned to code a microcontroller for a lab last year, but man, coding is just not my favorite thing to do. 

  And so, because of my dislike for coding, I feel like I've been missing out. I'm starting to learn C, with a little (a lot) of help from the web over my Winter Break because I understand how important it is. Also, making this website definitely required me to learn a bit about some coding languages (html and css), and a bit about my worst enemy.

***Git.***

  I have done some stuff with Git in the past, but for the life of me, I just couldn't wrap my head around it. Push, pull, commits? A whole lot of gibberish to my past self. Just to be clear, I'm not claiming to fully understand it now, but I will say that I have some working knowledge(?) because of how I use it for my website.

My initial plan was to just fully self-host my website. I was going to buy a domain, use a Docker container on my Proxmox machine to run a web server, and create a static site that served up my projects and my blog. I got as far as making the web server and creating an index page, but I decided that commiting to self hosting the website was just not feasible. Between my powerhungry server and the sheer unfamilliarity I had with the tools I was using, I deemed the project just a touch out of my current scope. So what was next?

Wordpress to the rescue! My next attempt at making my website landed me in the realm of website makers like Wordpress, Wix, and Squarespace. I wanted my own domain, so at first, I went with Wordpress.org and chose Hostinger as my web host. Then, I realized just how much it would cost to keep my website running, and I decided to go for a little more budget friendly option. Wordpress.com was what I fired up next, and I just could not configure the website how I wanted to on their free plan. I fought with it for what must've been four hours, but the editor and lack of customization options just made me give up on it. Off to the next one, I guess.

After researching for a while and looking for free blog sites, I eventually found GitHub pages! It was free and inherently customizable, which was exactly what I was looking for! The thing is, it require me to use Git, and that's what made me hesitate to settle on this option. I knew very little about it, and I'm no Computer Science major, so everything I've done with Git has been on my own. 

After looking up a bunch of tutorials on how to deploy a website using GitHub pages, I got my first site up, and it's been relatively smooth sailing from there! I'll be the first to say that my repositories for my sites are a mess, but it's been working pretty well so far and I can't complain. ChatGPT helped me with the layout, custom theming, and providing the skeleton of my website.

I'll probably make another post about just how much I appreciate having ChatGPT. Man, having AI as a tool is so incredible. It takes so much of the struggle out from what I've needed to do and allowed me to focus on working and creating. I've used it as a wall to bounce ideas off of, a code generator, a study device, you name it. It has made me question whether I'm using it too much, but those thoughts are for another day.

Now we're here! I love the way my site looks, and I love the features I've implemented. It'll change, I'll make it better and probably break it a few times, but it feels... good. It feels so nice to just write and have somewhere to post and have it all just *work*. 

signing off for now! -Niles

