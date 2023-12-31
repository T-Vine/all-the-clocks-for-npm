# all-the-clocks-for-npm
Digital clocks to add that fizz to your website! Future functionality includes analogue clocks, differing styles, etc.

Web-development can be tricky - but you don't always want full frameworks or CSS libraries in order to simplify it. All-The-Clocks adds a simple way to add local-time clocks to your website - adding that extra 'fizz'!

A simple EcmaScript 6 module that allows for simple clocks to be added (with one line!) to a web page. Current capabilities include:
- Digital Clock
- Digital Clock With Date
- Stopwatch

Future Functionality planned includes:
- Analogue Clocks
- Timers

## Usage
Install using 'npm i all-the-clocks'. 
Import into your website using 'import {[wanted clock]} from "./node_modules/all-the-clocks/index.js" or the path that it leads to where you are in your folder. The import statement should be within a '<script type="module"></script>' tag, otherwise it will not work.
Types of clocks you can import include:
-'clock': a normal digital clock.
- 'clockWithDate': a digital clock with date.
- 'stopWatch': a stopwatch.
To initialise these clocks have a Javascript line of 'new [type of clock]()'. E.g. if a new stopwatch is wanted, do 'new stopWatch()'. Variable assignment isn't required and clocks will function independently. Note that for the base clock (plain digital) it must be initialised with 'new clock().init()' as it provides the templates for the others.

This is based off of my original 'all-the-clocks' repository on Github - see there the coding journey that occurred!
See the Package Readme on NPM for more information.