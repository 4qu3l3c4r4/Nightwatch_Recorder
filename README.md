Nightwatch.js test recorder extension for Google Chrome
===========

[RUS](README-RUS.md) | Based on [Ressurectio](https://github.com/ebrehault/resurrectio.git)

Installation
============

1. Clone repo or [download](https://github.com/JyotiShir/nightwatchjs-test-recorder/archive/master.zip) and extract
1. Go to Chrome **Tools / Extensions**
1. Expand **Developer mode**
1. Click **Load unpacked extension...**
1. Select folder with repo
1. Use extension!

Usage
=====

Click on the extension icon, optionally enter the start URL, and **click Go**.

Then execute your usage scenario, all the events will be recorded.

By right-clicking on the page, you might also record some assertion (about the
current url, about existing text, etc., depending on clicked element).

You can request a **screenshot** at any moment (they will be produced everytime
you run the resulting test).

You might also record some comments (click again on the extension icon, and
click **Add comment**).

When you are done, click again on the extension icon, and
click **Stop recording**.

Now, generate the test template script by clicking **Export Nightwatch.js**.

When running in Nightwatch.js, it should play your entire scenario and generate the screenshots.

Future features
===============

Implement more mouse events, like drag & drop and mousewheel.

