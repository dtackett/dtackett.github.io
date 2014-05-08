---
layout: post
title: "An Indirect Journey"
date: 2014-05-08 07:48:41 -0700
comments: false
categories: project
---

Several months ago I had the notion that I should expand my horizons and learn a bit of Javascript. <!-- more --> I have quite a few years of experience with Java so the basic language constructs did not seem alien. There were a few key differences here and there but nothing so wild as to make it inaccessible.

After a few building a few toy examples I decided it was time to try something larger. Rather than doing something reasonable like building an application I might encounter in my day to day work I chose to go back to why I started programming in the first place. I decided to take a go at making a game.

Now I have a long and distinguished history of starting side game projects and never completing them. Something always comes up in life or I get away from it too long and jump down some other rabbit hole. In this latest effort I must admit that I haven't been the most consistent. However I have managed to keep dabbling on again and off again for several months.

Shortly after I started toying with a project I became enamored with the idea of functional programming. Now it is entirely possible to do functional programming in Javascript. There is even an [excellent book](http://funjs.herokuapp.com/) on the matter. However since Clojure is what caught my eye I jumped straight into ClojureScript.

Now I don't have much of a game to show at this moment. The basics of a 2d platformed are there. It isn't exciting or novel in any way but I have made progress. I decided to follow a [Component Entity System](http://www.chris-granger.com/2012/12/11/anatomy-of-a-knockout/) and I've been enjoying it. I know there are several Component Entity Systems out there. Even a few of them are in Clojure. In my defense I could not find a Clojure based solution when I first started. Granted there are some out now that are certainly more complete than what I have written. Even if my solution will not be used (or even seen) by anyone else I am getting value out of building it for myself. My end goal wasn't so much to make the game as much as it was to gain some experience in building a functional project. Quite the departure from where I originally started.

I have broken down my work into the game itself [Sivinolk](http://github.com/dtackett/sivinolk), my Component Entity System [Vyrlynd](http://github.com/dtackett/vyrlynd) and a crude input library [Clinp](http://github.com/dtackett/clinp). I intend to reflect a bit on my tilts at the windmills on these efforts in the future. For now it seems worth noting that they exist.
