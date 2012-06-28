# WebGameStub

WebGameStub helps you get a quick and easy start on writing an HTML5 game with 2D canvas with a simple template and a few tools.
WebGameStub  offers a good starting point for the game itself and smoothes off a  variety of the rough edges associated with writing and publishing a Web game.

WebGameStub is about saving you time and effort so that you can focus on writing your game.
It's about not having to write the most basic game infrastructure pieces, like canvas setup and an update/render loop.
It's about having an easier starting point than a blank canvas.
It's about not having to spend your time stitching together the usual cross-browser bits associated with bootstrapping an app on the web.
And once you've got a game you're proud of, it's about making it easy to publish into the app stores on the web, including the new Mozilla Marketplace.

## Getting started

* Download the current version of this project from
[the downloads page](https://github.com/mozilla/WebGameStub/downloads)
* Open the index.html file in the www folder in a web browser
* Edit the application in www/js/app.js and then reload the index.html file to see how your changes affect the game

#Extra Features (requires node.js)

<Start by explaining what the extra features are. Then elaborate on how to use them and what the prerequisites are.> <Don't really have the knowledge needed to write this section>

### Install node.js first

* Go to [nodejs](http://nodejs.org/)
* Download and install whatever package is appropriate for your platform

## Optimize for high performance

volo build+minify

## Deploy to github pages

volo ghdeploy

## Simple library installation

volo add
<The instructions for using the extra features needs more detail, and probably some concrete examples.> <Yeah, I know. I don't know how to use these tools, so the descriptions here could probably be done much more quickly by someone else>

## Publishing your game

Once your game is finished, you can publish it to a number of web marketplaces in order to reach your audience.

### Mozilla Marketplace

To publish your game to the Mozilla Marketplace:
1. Edit the application manifest template `www/game.webapp` in your project directory and fill in the required fields. Additional documentation for the mainfest file format is available [here](https://developer.mozilla.org/en/Apps/Manifest). Note that you are free to rename `game.webapp` to something else.

2. Check that your manifest is correct using the [App Manifest tool](http://appmanifest.org/).

3. Visit the [Mozilla Marketplace](https://marketplace.mozilla.org/en-US/developers/) and follow the instructions for submitting your application.

### Chrome Web Store

To publish your game to the [Chrome Web Store]():
1. Edit the application manifest template `www/manifest.json` in your project directory and fill in the require fields. Additional documentation for the manifest file format is available [here](https://developers.google.com/chrome/apps/docs/developers_guide#manifest).
2. Follow the instructions in the [developer tutorial](https://developers.google.com/chrome/web-store/docs/get_started_simple).

# More Resources

## Game APIs

* [Pointer Lock API](https://developer.mozilla.org/en/API/Pointer_Lock_API)
* [Gamepad API](https://developer.mozilla.org/en/API/Gamepad/Using_Gamepad_API)
* [Fullscreen API](https://developer.mozilla.org/en/DOM/Using_full-screen_mode)

## 2D Art

* [Danc's Miraculously Flexible Game Prototyping Tiles](http://www.lostgarden.com/2007/05/dancs-miraculously-flexible-game.html) (see bottom of post for download link)
* [Open Game Art 2D Art](http://opengameart.org/art-search-advanced?keys=&field_art_type_tid[]=9&field_art_tags_tid_op=and&field_art_tags_tid=&name=&sort_by=count&sort_order=DESC&Collection=)
If you know of any other good sources of free reusable art please let us know by
filing a [github issue](https://github.com/mozilla/WebGameStub/issues)

# Getting involved

Join us on #games on irc.mozilla.org and message dmose, ack, or dperit if you want to get involved and contribute to Webgamestub. We also welcome any feedback and input that you have to offer!
Issues can be filed on https://github.com/mozilla/WebGameStub/issues
