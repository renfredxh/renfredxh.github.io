---
layout: post
title: "Open Source Changelog"
date: 2014-11-16 03:13:28 +0000
comments: true
categories: 
---

In addition to maintaining [my own personal open source projects](https://github.com/renfredxh), I've made a few contributions to several other repositories. Here is where I keep track of them.

<!-- more -->

### 2014-10 **Lychee** - _Add Dockerfile_ - [#236](https://github.com/electerious/Lychee/pull/236/commits), [#252](https://github.com/electerious/Lychee/pull/252)
Lychee is a self-hosted photo management tool. I added a Dockerfile which containerized the application so users could easily deploy the application using Docker.

### 2014-06 **Backbone.localStorage** - _Remove isNew check on store.destroy_ - [#133](https://github.com/jeromegn/Backbone.localStorage/pull/133)
Backbone.localStorage is a popular local storage implementation plugin for Backbone.js. I fixed a minor bug that prevented Backbone collections from properly being removed from local storage.

### 2014-02 **twitch-chat-filter** - _Add "wait" command to array of blocked words_ - [#34](https://github.com/jpgohlke/twitch-chat-filter/pull/34)
Made a small improvement to a Twitch chat browser plugin made for the massive multiplayer internet phenomenon, [_Twitch Plays Pokémon_](https://en.wikipedia.org/wiki/Twitch_Plays_Pok%C3%A9mon).

### 2014-01 **dogetipbot** - _Remove inaccurate fiat display from message_ - [#6](https://github.com/mohland/dogetipbot/pull/6)
[Dogetipbot](https://dogetipbot.com/) is an infamous bot that at various point processed cryptocurrency transactions on between users on reddit. I fixed a minor bug which caused the bot to periodically fail to display correct fiat conversion rates to users.

### 2013-11 **PRAW** - _Remove depreciated method from documentation_ - [#257](https://github.com/praw-dev/praw/pull/257)
Made a minor clarification for a method in the excellent reddit python API wrapper, PRAW.
