---
layout: post
title: Random Thoughts
tags: misc
---

I haven't had much motivation to focus on a single topic in recent days, so here are an assortment of random thoughts instead.

## Working from Home

These principles are particularly useful when working from home:
* Define your work hours, but also build in breaks for food, etc.
* Plan ahead and make timelines for your deliverables. Set a reasonable pace for yourself, just as if you were in the office.
* Don't overwork yourself! For some people, it is easy to overwork and "burn out" when working from home.
* Follow a healthy regimen. Go outside at least 1-2 times during the day to help set your circadian rhythm and maintain a healthy, consistent sleeping schedule. Exercise and exposure to sunlight are vital to your mental health.

## Video Games: Diablo 2

Have some buddies you want to game with? Why not play the legendary classic Diablo 2? The atmosphere and gameplay are unparalleled by modern titles, and the entire game can be played with up to 8 players in a party! On top of that, the game is approachable to new and veteran gamers alike: it's easy to play and hard to master.

Even if you use a non-official copy of the game, players can connect directly to each other over the internet, directly using the TCP/IP option in "Other Multiplayer". The host just needs to forward port 4000 on their router. Then, everyone else can connect directly to the host's external IP. It's fairly painless! I got this idea from [this Reddit post](https://www.reddit.com/r/Diablo/comments/2opcg3/help_setting_up_hamachi_for_diablo_2_tcpip_game/cmpe15w/). 

If you are playing with someone on your LAN (i.e. on the same router), you can skip that step completely! The host's local IP will be shown on TCP/IP multiplayer screen in-game.

## Software Development: JS Modules

Everyone working in JavaScript should check out [JavaScript modules]([https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)). This feature is much better than past hacks using anonymous functions, and is well supported on modern web browsers. It's positively delightful. (And I don't use that word lightly.)

## Game Development: Virtual Private Servers

If you are working on a multiplayer game, at some point you will probably need a server for players to connect to. In development, running the server on your local computer is more than adequate. However, for deployment of a hobby-level game, I would recommend considering a virtual private server from companies like Vultr, Linode, or DigitalOcean. Running a VPS will give you hands-on experience with setting up databases, scripts, and programs.

The alternative cloud-based solutions are better when scaling up is needed — but there will be more initial setup cost and the solution may be less portable between providers.
