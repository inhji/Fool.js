# Fool.js

## What the heck is this?

This is a jQuery plugin that lets you play one or more fun practical jokes on an unsuspecting visitor. 


## How do I use it?

The easiest way is by calling a single prank like this:

    $(document).ready(function() { //  When the document is ready
    	$.fool('rick'); //  Run the Rick Astley prank
    });

Or if you really hate your users, call multiple pranks for even more fun:

    $(document).ready(function() { //  When the document is ready
        $.fool({
            hiddenVideos: true, // Show some wonderfully annoying videos
            vanishingElements: true, // Hide random elements as they interact
        });
    });


## What pranks are available?

$.fool('fallingScrollbar');   //  Want the scrollbar to fall over?
$.fool('rick');               //  The synonymous Rick Astley video, hidden off-screen
$.fool('hiddenVideos');       //  Show some wonderfully annoying videos
$.fool('vanishingElements');  //  Hide random elements as they interact
$.fool('questionTime');       //  Sing Spongebob with your browser!
$.fool('upsideDown');         //  Flip the page upside down!
$.fool('h4xx0r');             //  Make the page 100% editable
$.fool('wonky');              //  Make the page a little bit crooked
$.fool('flash');              //  Makes the site flash on and off
$.fool('crashAndBurn');       //  Runs an endless loop. This will kill your browser!
$.fool('shutter');            //  Forces a shutter on the screen
$.fool('unclickable');        //  Makes the page unclickable


## Who created it?

Fool.js was originally created by [VisualIdiot](http://visualidiot.com/) and is available here: [Original Homepage](http://fooljs.com/).