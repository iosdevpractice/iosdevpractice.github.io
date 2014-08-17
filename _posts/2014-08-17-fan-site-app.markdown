---
layout: post
title:  "Fan Site App"
categories: practice
comments: true
---

This practice exercise will explore accessing the network, parsing XML and JSON. Build the following simple fan site app using this rough design.

## Basic Functionality

* use a tab bar for different sections
* responsive UI (don't block the UI when making network requests)
* show network usage in status bar
* check for network availability and show message if not available

## First Tab
* get posts from RSS feed - (Use http://www.iosdevpractice.com/feed.xml or
  substitute any site you want.)

### Posts Screen
* table view in navigation controller
* table view cells show post title and date
* tapping on a cell pushes post detail screen

### Post Detail Screen

* web view loaded with post url

## Second Tab
* get tweets for user (@iosdevpractice)

### Tweets Screen
* table view in navigation controller
* table view cells show tweet and date
* tapping on a cell launches twitter app with tweet if available
* tapping on a cell pushes tweet detail screen if twitter app not
  available

### Tweet Detail Screen
* web view loaded with tweet url

## Wireframes
* [Feed Main Screen](/images/fan-site-feed-main.jpg)
* [Feed Detail Screen](/images/fan-site-feed-detail.jpg)
* [Tweets Main Screen](/images/fan-site-tweets-main.jpg)
* [Tweets Detail Screen](/images/fan-site-tweets-detail.jpg)

## Example Implementation
* Coming Soon
