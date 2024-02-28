---
hide: navigation
---

# Fingerprint Tools

[Download :material-download:](https://github.com/regorxxx/Fingerprint-Tools-SMP){ .md-button }

## Overview

[Spider Monkey Panel](https://theqwertiest.github.io/foo_spider_monkey_panel) Script for [foobar2000](https://www.foobar2000.org), built within a button. [ChromaPrint](https://acoustid.org/chromaprint) and [fooID](https://hydrogenaud.io/index.php/topic,65185.0.html) tools to compare fingerprints, search on library or tagging.

![Timeline UI](../images/tl_ui.jpg)

### Features
- [ChromaPrint](https://acoustid.org/chromaprint) support: tagging (with fpcalc) and full processing without binaries.
- [fooID](https://hydrogenaud.io/index.php/topic,65185.0.html) support: tagging (with original plugin) and full processing without binaries.
- Tagging: tag your files with any of the supported fingerprint methods.
- Read from files: fingerprints may be read from library (provided by foobar2000 cached tags values) or directly from files (using ffprobe) to minimiz RAM usage.
- Searching on library: find similar tracks by fingerprint on your library.
- Fingerprint comparison: report the similarity between the selected tracks.
- Fast processing: fingerprint processing is entirely done within he script files, without other dependencies, and heavily optimized to be as fast as possible.
- AutoPlaylist and Playlist creation on click over a point.
- Fully Wine - Unix - non IE SOs compatible.

![Timeline usage](../images/tl.gif)

!!! question
	Compatible with (toolbar):  
    - [Device Priority](../../scripts/device-priority-smp): Automates foobar2000's output devices.  
    - [Search by Distance](../../scripts/search-by-distance-smp): Creates intelligent "spotify-like"
	playlist.
    - [Playlist Tools](../../scripts/playlist-tools-smp): Offers different pre-defefined examples for 
	intelligent playlist creation.  
	- [ListenBrainz](../../scripts/listenbrainz-smp): Integrates Listenbrainz's feedback and recommendations.  
	- [Last.fm](../../scripts/lastfm-smp): Integrates Last.fm playlists, recommendations, ...  
	- [AutoBackup](../../scripts/autobackup-smp): Automatic backups of configuration files.  
	- [Wrapped](../../scripts/wrapped-smp): User listening statistics and recommendations.  