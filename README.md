Ampache Doped
=======

Basics
------

Ampache Doped is a web based audio/video streaming application and file
manager allowing you to access your music & videos from anywhere,
using almost any internet enabled device.
Ampache Doped is a fork of Ampache project.

Ampache's usefulness is heavily dependent on being able to extract
correct metadata from embedded tags in your files and/or the filename.
Ampache is not a media organiser; it is meant to be a tool which
presents an already organised collection in a useful way. It assumes
that you know best how to manage your files and are capable of
choosing a suitable method for doing so.

Recommended Version
-------------------

Currently, the recommended version is [git HEAD](https://github.com/ampache-doped/ampache/archive/master.tar.gz).
[![Build Status](https://api.travis-ci.org/ampache-doped/ampache.png?branch=master)](https://travis-ci.org/ampache-doped/ampache)

Requirements
------------

* A web server. All of the following have been used, though Apache
receives the most testing:
    * Apache
    * lighttpd
    * nginx
    * IIS

* PHP 5.3 or greater.

* PHP modules:
    * PDO
    * PDO_MYSQL
    * hash
    * session
    * json

* MySQL 5.x

Installation
------------

Please see [the wiki](https://github.com/ampache-doped/ampache/wiki/Installation)

Upgrading
---------

If you are upgrading from an older version of Ampache we recommend
moving the old directory out of the way, extracting the new copy in
its place and then copying the old config file into config/. All
database updates will be handled by Ampache.

License
-------

Ampache is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License v2
as published by the Free Software Foundation.

Ampache includes some external modules that carry their own licensing.

* [getID3](http://getid3.sourceforge.net): GPL v2
* [Horde_Browser](http://www.horde.org): LGPL v2.1
* [PHP-gettext](https://launchpad.net/php-gettext): GPL v2
* [MusicBrainz](https://github.com/mikealmond/MusicBrainz): MIT
* PHP MPD interface: GPL v2
* [PHPMailer](https://github.com/PHPMailer/PHPMailer): LGPL v2.1
* [jQuery](http://jquery.org): MIT
* [Requests](http://requests.ryanmccue.info): ISC Licensed
* [Whatever:hover](http://www.xs4all.nl/~peterned): LGPL v2.1
* [xbmc-php-rpc](https://github.com/karlrixon/xbmc-php-rpc): GPL v3
* [Dropbox SDK](https://github.com/dropbox/dropbox-sdk-php): MIT
* [jPlayer](http://jplayer.org): MIT
* [prettyPhoto](http://www.no-margin-for-errors.com/projects/prettyphoto-jquery-lightbox-clone): GPL v2
* [unofficial-google-music-api-php](http://code.google.com/p/unofficial-google-music-api-php): GPL v3
* [Tag-it!] (http://aehlke.github.io/tag-it): MIT
* [PHP Echo Nest API] (https://github.com/bshaffer/php-echonest-api): MIT
* [Noty] (http://ned.im/noty): MIT
* [jScroll] (https://github.com/pklauzinski/jscroll): MIT
* [jquery.qrcode] (http://jeromeetienne.github.io/jquery-qrcode): MIT
* [PHP OpenID] (https://github.com/openid/php-openid): Apache License
* [Ratchet] (http://socketo.me): MIT
* [ReactPHP] (https://github.com/reactphp/react): MIT
* [Guzzle] (https://github.com/guzzle/guzzle): MIT
* [Symfony Components] (https://github.com/symfony): MIT
* [Evenement] (https://github.com/igorw/evenement): MIT
* [RhinoSlider] (http://rhinoslider.com): MIT
* [MediaTable] (https://github.com/edenspiekermann/MediaTable): MIT
* [Responsive Elements] (https://github.com/kumailht/responsive-elements): MIT


Translations
------------

Ampache is currently translated (at least partially) into the
following languages. If you are interested in updating an existing
translation or adding a new one please see /locale/base/TRANSLATIONS
for more instructions.

* English	(en_US)
* German	(de_DE)
* Spanish	(es_ES)
* Dutch		(nl_NL)
* Norwegian	(nb_NO)
* UK English	(en_GB)
* Italian	(it_IT)
* French	(fr_FR)
* Swedish	(sv_SE)
* Japanese	(ja_JP) 
* Catalan	(ca_ES)
* Russian	(ru_RU)
* Czech (cs_CZ)

Credits
-------

Thanks to all those who have helped make Ampache awesome: [Credits](docs/ACKNOWLEDGEMENTS)


Contact Us
----------

Hate it? Love it? Let us know. Also let us know if you think of any
more features, encounter bugs, etc.

* [Public Repository](http://github.com/ampache-doped)
* IRC: chat.freenode.net #ampache
* [Issue Tracker](https://github.com/ampache-doped/ampache/issues)
* [Documentation](https://github.com/ampache-doped/ampache/wiki)

