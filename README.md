Länkar
======

Länkar is two things :

* a project to (re)learn and test PHP. I'm trying Silex to not starts from scratch but without a _big_ framework
* a link manager. I use [shaarli](http://sebsauvage.net/wiki/doku.php?id=php:shaarli) but want to add some features **I** need so as I want to learn PHP this is IMO a good reason to start a new project

Technologies
------------

List of technologies or programs or libraries in Länkar :

* [Silex](silex.sensiolabs.org) : server side of the project, REST api
* [Doctrine](http://www.doctrine-project.org/) : database storage management
* [AngularJS](http://www.angularjs.org) : client side, web interface
* [Bootstrap](http://twitter.github.com/bootstrap/) : default style
* [PageDown](http://code.google.com/p/pagedown/wiki/PageDown) : markdown javascript library


ToDo
----

* improve debug mode using coffeescript and less js compiler
* tags (model, db, ui)
 * auto complete (bootstrap)
* install/migrate
* display a link details
* use hash to edit existing link instead of add a new one
* use AngularJS resources
* add functionnalities on 'go' to add some url shortner functions (clicks, referer, etc)
* use twig to render html/partial pages
 * and add localisation
* install documentation
* migration
 * from bookmarks
 * from shaarli

Done
----

**2012/06/25**

* use real date

**before**

* paginate with doctrine
* save links
* toolbar shortcut (bookmark)
* implement 'go' to redirect from hash in url
