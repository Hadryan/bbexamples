<h1>Simple Simple Backbone</h1>

These examples came about because I had to learn Backbone.js for my job.
From the start, I had a problem with it; why do we need all this complexity?
All of the examples, even the <i>simple</i> ones, seemed to have dozens of files and several other technologies that I'd never seen before, often with some sort of server application in whichever language/technolgy the author wrote in.
These are fine for the project they were intended for; just not good for beginning learners.

Meanwhile, Backbone.js as of the start of 2013, can be described as 'testy', meaning, you have to test after each change you make to be sure you didn't break anything.  My attempts to start from an empty file and make a BB app were desperate and brutal.  Unless I can type in a 'hello world' program from memory, I don't really believe that I 'know' a system.

Some of these are based (loosely) on the 'very simple backbone application' by 
<a href=mailto:lostsoul&#64;beyondtheclouds.net>lostsoul&#64;beyondtheclouds.net</a>.
Indeed, I made it simpler as it pulled in other pagckages and XHR, which I thought distracted from the main lesson, despite the fact that a real program would use them.  In fact, at first I couldn't get any BB app to work and so I started with lostsoul's app and a chainsaw.

apps: each has an 'index.html' file that runs the app; put them anywhere a server serves and surf there.  In many cases it'll work with the file: protocol so you can just drag the file into a browser window.

The first example is <b>helloworld</b>; as its name says it's the good old minimal page that uses Backbone.js.
Totally useless itself, but it shows the bare bare minimum BB stuff you need for every page/panel.  Plus some gotchas.
It uses backbone's Router and View classes, no others.


The second example is <b>carnac</b>.  This shows some slightly more involved View and Router code, actually having something like a purpose.

The third example, <b>jrivers</b>, is a small app using nothing but a Model class.  Not even routers or views!  everything else done in regular html and js.


I'm assuming that you're a web programmer familiar with current JavaScript, and with jQuery, as I was, too, when I started.
<a href=http://backbonejs.org>Backbone</a> also uses 
<a href=underscore.js>underscore.js</a> .  

