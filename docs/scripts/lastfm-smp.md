---
hide: navigation
---

# Last.fm

[Download :material-download:](https://github.com/regorxxx/Playlist-Tools-SMP){ .md-button }

## Overview

An implementation of [Last.fm](https://www.last.fm/) for [foobar2000](https://www.foobar2000.org)
 using [Spider Monkey Panel](https://theqwertiest.github.io/foo_spider_monkey_panel),
 which allows to find matches on library or YouTube from artist's pages, playlists, recommendations,
 stations...

![ListenBrainz](../images/lf.gif)

### Features
- Integrates original [L3v3L's script](https://github.com/L3v3L/foo-last-list-smp) into Playlist Tools's toolbar (design and features may differ).
- Gets top tracks by: Artist, Artist's radio, Similar Artist, Genre, Style, Folksonomy tags, Date, Moods, ...
- Supports multi-values (i.e. if a track has 4 moods, allows to search for each individual value).
- Covers most standard tags: GENRE, STYLE, MOOD, Picard tags,...
- Integrates tags from [WilB's Biography](https://github.com/Wil-B/Biography) (all) and [World-Map-SMP](../../scripts/world-map-smp) (locale).
- Creates playlist from User's library, loved tracks or custom URLs.
- Matches are retrieved from library and, optionally, from YouTube if [plugin](https://fy.3dyd.com/home/) is installed.
- Does not require an user token or API.

### Buttons bar
The button can be loaded within a toolbar or as an independent button. 
It's fully compatible with my other scripts which also use a toolbar (see at bottom), 
so the button can be simply merged with your already existing toolbar panel easily.

!!! question
	Compatible with (toolbar):  
	- [Device Priority](../../scripts/device-priority-smp): Automates foobar2000's output devices.  
    - [Search by Distance](../../scripts/search-by-distance-smp): Creates intelligent "spotify-like"
	playlist using high-level data from tracks and computing their similarity using genres/styles.  
    - [Playlist Tools](../../scripts/playlist-tools-smp): Offers different pre-defefined examples for 
	intelligent playlist creation.  
	- [ListenBrainz](../../scripts/listenbrainz-smp): Integrates Listenbrainz's feedback and recommendations.  
	- [AutoBackup](../../scripts/autobackup-smp): Automatic backups of configuration files.  