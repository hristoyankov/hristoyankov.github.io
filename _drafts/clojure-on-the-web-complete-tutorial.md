---
layout: post
title: Clojure conquers the web complete tutorial - Part 1
---

Prologue
========

I've been playing with Clojure for a little less than an year now... *"Playing"* is the best word for what I've been doing all this time - solve a 4Clojure problem, explore framework presented in a talk, hack along a tutorial, etc. Not that this is so bad but is not [deliberate practice](https://en.wikipedia.org/wiki/Practice_(learning_method)#Deliberate_practice). Everytime I returned to my [favourite Clojure tutorial site](https://purelyfunctional.tv/) after long pause I started from the beginning. And although reimplementing *reduce* for nth time is generally a good exercise it didn't improved me in anyway. What I need is some challenging task to push myself. At some point I was really close yet so far from reaching this goal. I've started a [hoby project](https://github.com/hristoyankov/table-soccer) that would make table soccer tournaments easier. There're tons of future functionalities in my head but the base idea was dead simple CRUD app yet I failed to finish it.

Why?
Because of me being a maximalist ... again.

I wanted to do **everything** from the beginning! I wanted to do TDD although I've never really practiced it. I definitely needed automated testing on every push and integrate all this with Trello and Slack. Did I mentioned I was just starting with the language and basically have never done a single CRUD app from end to end? Combined with another self challenge of waking up early and working for half an hour every morning on my project - complete disaster. But, you know, [*"Failure is growth. Failure is success."*](http://siliconvalleyism.com/silicon-valley-quote.php?id=133)! Doing too many new things at the same time simply evaporated all of my enthusiasm and energy. What I find intriguing is my own, maximalist, approach is the opposite of *the Clojure philosophy* I'm embracing! **Create small and simple functions that could be easily combined with one another**. And as I'm learning through failure I'll simply try the new approach - do one little thing with every step, do stuff manually, do write down the progress. Combine all of the above when it feels like it and I'll have my dream fully automated project setup ... with a bit of luck a nice tutorial too! So grab a cup of coffee and ...

Let's get started!
==================

Note that I'm starting this as a personal know-how log and I have no experience in writing tutorial despite the name of the post. Therefore it'll be specific to my dev setup - Arch Linux, Emacs & zsh.
