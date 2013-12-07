Block Holiday Snow
==================

Author: Josh Eaton [@jjeaton](https://twitter.com/jjeaton)  
Version: 0.1

Chrome Extension to block the falling snow effect on any site using the WordPress Jetpack plugin. [For more info on why it should be blocked read this.](aftergadget.wordpress.com/2013/01/23/waspish-wednesday-how-autoplays-let-it-snow-disable-visitors-to-your-website/)

The extension works by preventing any web request from downloading a file called snowstorm.js. If you depend on a site that has mission-critical code in snowstorm.js, you probably don't want this extension.

If you're a WordPress site admin and want to add the falling snow effect to your site in a responsible way, check out my WordPress plugin: [Jetpack Holiday Snow Opt-In](https://github.com/jjeaton/jetpack-holiday-snow-opt-in).

## Installation

1. Download a [zip of the master branch](https://github.com/jjeaton/block-holiday-snow/archive/master.zip).
2. In Chrome go to Tools > Extensions or [chrome://extensions/](chrome://extensions/).
2. Open the build directory from the zip, and drag the `.crx` file onto the Extensions page in Chrome. The extension should now be installed.
