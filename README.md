There are a lot of obstacles involved in building and deploying a canvas game.

WebGameStub bypasses them for you, allowing you to start writing a game immediately.

It includes a simple working canvas game with a tutorial, and is based on [HTML5 Boilerplate](http://html5boilerplate.com/)

WebGameStub

* Lets you get started writing & deploying a web game without lots of papercuts
* It has a simple working canvas game (with tutorial) as starting point
* Provides a solid cross-browser, cache-optimized template based on html5boilerplate
*  Allows for easy build/deployment to github pages & marketplaces (optional, requires node.js)

Getting started

* Download the current version of this project from
[the downloads page](https://github.com/mozilla/WebGameStub/downloads)
* Open the index.html file in the www folder in a web browser
* add background image so that you've got something that looks cooler (doesn't appear to be anything pointing at a background image right now?)
* (deploy)
* edit mozilla & chrome json files
* (submit to web stores)

Extra Features (requires node.js)

* (install node)
* optimize for fast perf: volo build+minify
* deploy to github pages: volo ghdeploy
* simple library installation: volo add
* (submit to web stores)

More Resources

* FAQ
* MDN game / API docs (What/where would these be?)

Maybe these?

* [Pointer Lock API](https://developer.mozilla.org/en/API/Pointer_Lock_API)
* [Gamepad API](https://developer.mozilla.org/en/API/Gamepad/Using_Gamepad_API)

Here are a couple of good sources of freely reusable 2D art for games:

* [Danc's Miraculously Flexible Game Prototyping Tiles](http://www.lostgarden.com/2007/05/dancs-miraculously-flexible-game.html) (see bottom of post for download link)
* [Open Game Art 2D Art](http://opengameart.org/art-search-advanced?keys=&field_art_type_tid[]=9&field_art_tags_tid_op=and&field_art_tags_tid=&name=&sort_by=count&sort_order=DESC&Collection=)
If you know of any other good sources of free reusable art please let us know by
filing a [github issue](https://github.com/mozilla/WebGameStub/issues)

## Publishing your game

Once your game is finished, you can publish it to a number of web marketplaces in order to reach your audience.

### Mozilla Marketplace

To publish your game to the Mozilla Marketplace:

1. Edit the application manifest template `www/game.webapp` in your project directory and fill in the required fields. Additional documentation for the mainfest file format is available [here](https://developer.mozilla.org/en/Apps/Manifest). Note that you are free to rename `game.webapp` to something else.

2. Visit the [Mozilla Marketplace](https://marketplace.mozilla.org/en-US/developers/) and follow the instructions for submitting your application.

### Chrome Web Store

To publish your game to the [Chrome Web Store]():

1. Edit the application manifest template `www/manifest.json` in your project directory and fill in the require fields. Additional documentation for the manifest file format is available [here](https://developers.google.com/chrome/apps/docs/developers_guide#manifest).

2. Follow the instructions in the [developer tutorial](https://developers.google.com/chrome/web-store/docs/get_started_simple).
