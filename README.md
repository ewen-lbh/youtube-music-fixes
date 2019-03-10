# youtube-music-fixes
Various userscripts for YouTube Music. Currently avaible: 
- Tab title fix \[[download](https://github.com/ewen-lbh/youtube-music-fixes/raw/master/tab-title.user.js)\]

## Installing

You'll need an extension for your browser to use these scripts.
### Prerequisites
- [Tampermonkey(Chrome)](https://tampermonkey.net)
- [Greasemonkey(Firefox)](http://www.greasespot.net)
- [Violent monkey(Opera)](
   https://addons.opera.com/sk/extensions/details/violent-monkey/)
- [Greasemonkey Port(SeaMonkey)](https://sourceforge.net/projects/gmport/)

**Note: on chrome and chromium version 4 and higher, userscripts are supported by default**


## Contributing
Feel free to open issues for suggestions, and create pull requests to implement a feature.

Note that the file should be named (in dash-case) using the following pattern:

`script-name.user.js`

The files should begin with this:

```

// ==UserScript==

// @name YTM <Script Name> Fix

// @namespace https://github.com/ewen-lbh/youtube-music-fixes/

// @version 0.1

// @description <Short description>

// @author Mx3

// @match *://music.youtube.com/*

// @grant none

// ==/UserScript==

```

Of course, you can adjust `@match`, `@grant` or `@version` accordingly. 

The `@match` should remain in the *music.youtube.com* domain tho.

