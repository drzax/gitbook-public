---
description: >-
  A short description of the setup I use and some notes on things I haven't been
  able to automate.
---

# Computer setup

My primary work machine is a MacBook Pro and I try to keep the settings in order with [a fork](https://github.com/drzax/dotfiles) of [cowboy's dotfiles](https://github.com/cowboy/dotfiles).

Some of the software I use.

* I use [Alfred](https://www.alfredapp.com/) as a quick launcher and helper. Other options I've seen in this space include [Raycast](https://www.raycast.com/).



### Migrating to a new machine

Things to consider:

* Non-synced files
* Little Snitch rules
* `mas` list of apps
* backup atom config
* backup ssh keys
* OneTab list?

## Missing tools

### History search

I want a full text search of all pages I've ever visited. It should provide weighting signals based on:

* relevance
* time spent on page
* recency of last visit
* frequency of visits

The data to enable this will contain sensitive data, therefore should not be a hosted service but an app that lives on an individual machine or stores data in encrypted synchronised storage such as iCloud.

Potentially enabling technologies:

* [ArchiveBox](https://archivebox.io/)

### Bookmark search

Simple keyboard access to all browser bookmarks.

