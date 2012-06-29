# WebGameStub

WebGameStub helps you get a quick and easy start on writing an HTML5 game with 2D canvas with a simple template and a few tools.
It offers a good starting point for the game itself and smoothes off a variety of the rough edges associated with writing and publishing a Web app.

WebGameStub is about saving you time and effort so that you can focus on writing your game.
It's about not having to write the most basic game infrastructure pieces, like canvas setup and an update/render loop.
It's about having an easier starting point than a blank canvas.
It's about not having to spend your time stitching together the usual cross-browser bits associated with bootstrapping an app on the web.

### What WebGameStub 0.1 Gets You

* A simple update/render loop and canvas.
* A copy of an example game that you can inspect and extend.
* Links to helpful game docs, API docs, and open art resources so you don't have to hunt for them.
* HTML & CSS based on HTML5 Boilerplate for speed, robustness, and futureproofing.
* (Optional) Using node.js: automated optimization, deployment to github pages, and library installation using volo.

## Getting started

* Download the current version of this project from
[the downloads page](https://github.com/mozilla/WebGameStub/downloads)
* Open the index.html file in the www folder in a web browser
* Edit the application in www/js/app.js and then reload the index.html file to see how your changes affect the game

#Extra Features (requires node.js)

The extra features of WebGameStub allow you to easily add libraries, build a
minified and optimized version of your game, and then easily deploy it to github
pages

## Prerequisites for extras

* Be sure that [node.js and npm](http://nodejs.org/) are installed and in your PATH
* (optional) If you wish to deploy to github pages, ensure that
 [git](http://help.github.com/set-up-git-redirect) is installed and configured
* Use npm to install volo into your path, if it's not there already:

    > sudo npm install -g volo

## Simple library installation

Add any libraries that you intend to use.  volo uses github's search API to
find them and grabs the latest released version.

    > volo add three.js
    Using github repo "mrdoob/three.js" for "three.js"...
    Downloading: https://raw.github.com/mrdoob/three.js/master/build/Three.js
    Installed github:mrdoob/three.js/master at js/three.js

    > volo add stats.js
    Using github repo "mrdoob/stats.js" for "stats.js"...
    Downloading: https://raw.github.com/mrdoob/stats.js/master/build/Stats.js
    Installed github:mrdoob/stats.js/master at www/js/lib/stats.js

## Optimize for high performance

Build a minified version complete with an appcache file:

    > volo appcache
    (...)

## Deploy to github pages

Deploy the built version to the gh-pages branch of suitably named repo:

    > volo ghdeploy
    Log in to GitHub to complete action (your password is not saved. It is sent over SSL to GitHub and converted to an OAuth token)
    GitHub user name: dmose
    GitHub password:
    Contacting GitHub...
      (...)
    To git@github.com:dmose/monkeyGame.git
    e5dbfd4..1296c81  gh-pages -> gh-pages
    GitHub Pages is set up. Check http://dmose.github.com/monkeyGame/ in about 10-15 minutes.

# More Resources

## Game APIs

* [Pointer Lock API](https://developer.mozilla.org/en/API/Pointer_Lock_API)
* [Fullscreen API](https://developer.mozilla.org/en/DOM/Using_full-screen_mode)

## 2D Art

* [Danc's Miraculously Flexible Game Prototyping Tiles](http://www.lostgarden.com/2007/05/dancs-miraculously-flexible-game.html) (see bottom of post for download link)
* [Open Game Art 2D Art](http://opengameart.org/art-search-advanced?keys=&field_art_type_tid[]=9&field_art_tags_tid_op=and&field_art_tags_tid=&name=&sort_by=count&sort_order=DESC&Collection=)

If you know of any other good sources of free reusable art please let us know by
filing a [github issue](https://github.com/mozilla/WebGameStub/issues)

# Feedback and helping out

If you run into something that's missing or that is getting in your way when using WebGameStub, please help us out by opening a [github issue](https://github.com/mozilla/WebGameStub/issues) (or even a pull request!) to discuss it.
We're often available in [#games on irc.mozilla.org](irc://irc.mozilla.org/#games) for questions.

# More Info

* [WebGameStub's Github repo](https://github.com/mozilla/WebGameStub/)
* [Frequently Asked Questions](https://github.com/mozilla/WebGameStub/wiki/Frequently-Asked-Questions), including info about what this means for the Minimalist Template
* Lost Decade's [excellent tutorial](http://www.lostdecadegames.com/how-to-make-a-simple-html5-canvas-game/) on how they built the  simple canvas game
* [HTML5 Boilerplate](http://html5boilerplate.com/)

