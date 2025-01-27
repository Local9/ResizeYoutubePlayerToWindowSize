# Suggestions

* The `w` key will toggle the script in the current tab.
* Use [Resize Video To Window Size](https://greasyfork.org/en/scripts/10815-resize-video-to-window-size) for Crunchyroll, Vimeo, and a few other sites.

# Screenshots

**After loading the video webpage you will see:**

[![](https://i.imgur.com/GDeEDPA.png)](https://i.imgur.com/GDeEDPA.png)

**It appears above the rest of the site, so you can scroll down for the description, related links, etc.**

[![](https://i.imgur.com/uVDKPUp.jpg)](https://i.imgur.com/uVDKPUp.jpg)

# Changelog

https://github.com/Zren/ResizeYoutubePlayerToWindowSize/blob/master/changelog.md

## v132 - June 29, 2023

* Fix video container getting shifted after YT update (Issue #77)
* Fix nav moving around when guide is open.
* Added `background-color: black` to `#movie_player` so it looks better in light mode.

## 131 - March 11, 2023

* Fix theater mode toggle. `ytd-watch-flexy` DOM is weird. (Issue #75)
* Listen for `yt-navigate-start` and `yt-navigate-finish` events.
