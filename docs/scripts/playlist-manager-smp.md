---
hide: navigation
---

# Playlist Manager

[Download :material-download:](https://github.com/regorxxx/Playlist-Manager-SMP){ .md-button }

## Overview

A playlist manager for foobar2000 and Spider Monkey Panel to save and load
(auto)playlists on demand, synchronizing, ... along many more utilities.

- Manages Playlist files and AutoPlaylists.
- AutoPlaylists: contains all functionality on Auto-playlist Manager by marc2003 plus more.
- Smart Playlists: contains all functionality found on XBMC or Kodi:
- Complete documentation, FAQ and step by step guide (see 'readmes\playlist_manager.pdf').
- Loads .m3u8, .m3u and .pls playlists x100 times faster than standard foobar.
- Multiple exporting options: compatible with Foobar2000 mobile, Kodi and XBMC systems, etc.
- Playlist Tags and actions. Track Auto-tagging.
- Filters & Sorting.
- Configurable UI.
- Fully Wine - Unix - non IE SOs compatible.
- Other scripts integration:
	- Playlist-Tools-SMP: Pools may use tracks from playlists files.
    - ajquery-xxx: Online controller fully compatible with the manager.
    - SMP Dynamic menus: Playlist actions are also available as main menu
	entries, which allows to bind them to keyboard shortcuts, toolbar buttons
	or executing them using command line.

!!! note
	.fpl playlists (native format) are read only and can not be auto-saved since
	the format is closed source and there are no methods on Spider Monkey Panel
	to save them on a path (without showing the 'save as' window), neither load
	them as handle lists.

	Tracking playlists within a network drive requires additional steps to make use
	of the Recycle Bin. See Readme (pdf).