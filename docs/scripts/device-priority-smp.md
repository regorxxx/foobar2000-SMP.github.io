---
hide: navigation
---

# Decice Priority

[Download :material-download:](https://github.com/regorxxx/Device-Priority-SMP){ .md-button }

## Overview

[Spider Monkey Panel](https://theqwertiest.github.io/foo_spider_monkey_panel/) script
 for [foobar2000](https://www.foobar2000.org/), built within a button. 
 Automate foobar2000's output without having to select devices manually every time one
 is disconnected/connected. Wireless, headphone, and server devices auto-switch made easy.

- Export Device List: after connecting all devices desired to be used at some point,
 the list can be exported to be able to set them at a later point as prioritized devices
 (even if they are not connected).
- 1-5 slots for prioritized devices: set the order in which the devices must be set as output.
 Device 1 would be used (if available) before Device 2 and so on...
- Server friendly: some wireless devices pause playback when they are disconnected, 
thus requiring to manually start playback again even if the device has been changed 
(manually or automatically). The script checks if playback is paused after swapping 
devices and will continue it automatically in those cases for a seamless change 
between devices when you switch them off/on.
- Fully Wine - Unix - non IE SOs compatible.

The button can be loaded within a toolbar or as an independent button. 
It's fully compatible with my other scripts which also use a toolbar (see at bottom), 
so the button can be simply merged with your already existing toolbar panel easily.
	
![Device Priority](../images/dp.gif)

!!! question
	Compatible with (toolbar):  
    - [Search by Distance](scripts/search-by-distance-smp): Creates intelligent "spotify-like"
	playlist using high-level data from tracks and computing their similarity using genres/styles.  
    - [Playlist Tools](scripts/playlist-tools-smp): Offers different pre-defefined examples for 
	intelligent playlist creation.  
	- [ListenBrainz](scripts/listenbrainz-smp): Integrates Listenbrainz's feedback and recommendations.  