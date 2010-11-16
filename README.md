Haybase
=======
**Makes developing WordPress plugins and themes infinitely more easy**

If you have ever written a WordPress theme or plugin you probably noticed that
a lot of the code seems repetitive and alike. Of course, you can copy-paste
stuff from the standard themes, but is that really the right way to write a theme?

Haybase provides an easy interface to many features of WordPress. Writing very 
simple, nice object-orientated PHP5, you can add stuff like post thumbnails, 
Facebook Open Graph data, or a list of recent comments.

Features
--------
* Timthumb image resize script for post thumbnails (or any other image)
* Simple way to get an array with your
    * Recent posts
    * Recent comments
* Easy ways to access common variables in your theme (such as the theme directory)
* Helper scripts for adding CSS styles and Javascript
* Get the page type
* Lightweight template functionality
* Easy adding of Facebook Open Graph metadata to your page
* Utility functions for commonly used stuff
* Open source, GPL licensed. Just like WordPress itself.
* Clean, object-orientated, PHP5 code with classes instead of
  endlessly_long_function_names_with_lots_of_underscores_and_prefixes

Requirements
------------
* PHP 5.2 or higher
* WordPress 2.7 or higher

Documentation
-------------
Learn more about Haybase: http://www.haykranen.nl/projects/haybase

Fork it on github: http://www.github.com/hay/haybase

Mail me: hay@bykr.org

FAQ
---
*What's this `$T` i see everywhere in the code?*

`$T` is the global variable that has the instance of the current theme class.
You use this to access all the public methods and variables of Haybase and your
derived theme class. Read the [docs] for an overview of all available
options.

*Why can't i use kubrick, twentyten or (insert other theme here) as a starting
point for my own theme?*

I did that for years, but all themes include lots of stuff you don't need and
many things you do need, but not in the way you want it. The best way to start a
new theme is to start from scratch. However, many lower-level functions are
very common amongs themes, and Haybase provides a nice interface and starting
point for those functions.

*Why bother with WordPress at all? Why not use a proper coded CMS such as
(insert name here)?*

Many people know WordPress, and the ui is pretty nice. There are thousands of
plugins available, and it runs on virtually any web host.

*What's wrong with the current way of using the WordPress API?*
If you're like me, you like clean object-orientated modern PHP5 code.
Unfortunately 99% of all WordPress themes and plugins (including the core
itself) is not OO at all, in fact, it's a mess. Mixing of code and HTML, using
endless functions instead of classes, repetition of large blocks of code. Does
this sound familiar to you? It makes developing a clean theme a lot of work,
because there is no good foundation.

*Are there any examples of (free) themes using Haybase i can download, study
and use?*

Haybase is very new software, so no themes that i know of have been built.
If you have build a theme using Haybase that is free, please let me know so i
can add it to a list in this file and on the website!

*I build a theme using Haybase, what do you think of it?*

See previous question :)

TODO
----
Cool stuff in the near feature (fork on Github and contribute if you want!)

* Configuration of theme options page (easily create a theme options page for
  your theme.
* Support for Haybase addons / extensions
* Let Haybase make coffee and do your dishes (nah, not really ;)

Thank you
---------
Haybase includes code from:

* timthumb: http://code.google.com/p/timthumb/

[docs]: http://www.haykranen.nl/projects/haybase
[jsonlint]: http://www.jsonlint.com