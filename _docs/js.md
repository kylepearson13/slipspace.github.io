---
layout: docs
title: JavaScript Documentation
---

##JavaScript

We provide support for tracking errors that occur in your JavaScript code inside the user's browser.

##Getting started

You can manually download the JavaScript file for your project. We have both a [minified production version](https://github.com/slipspace/slipspace.js/blob/master/build/slipspace-1.0.0.min.js) and [development version](https://github.com/slipspace/slipspace.js/blob/master/build/slipspace-1.0.0.js) available.

Or you can install the library using the NuGet package manager

<pre class="prettyprint">

    PM> Install-Package slipspace.js


</pre>

The library has no dependencies so you can install it on any old website.
 
##Usage instructions

In your webpage just reference the library and supply your API Key.


<pre class="prettyprint">

  &lt;script data-apikey="{YOUR API KEY}" src="/Scripts/slipspace-1.0.0.min.js"&gt;&lt;/script&gt;


</pre>