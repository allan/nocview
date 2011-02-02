nocview
=======

A single html file that uses the Opsview API to display all
unhandled problems nicely.

### Installation

  * Clone the repository

        $ git clone http://allan.de/src/nocview

    Put `unhandled.html` in your Nagios share directory, for example
    `/usr/local/nagios/share/`.  It should now be accessible via browser
    with `http://your.opsview.webserver/unhandled.html`.  If you haven't
    already logged in to Opsview, you will be redirected to the login,
    after which you can return to unhandled.html with the proper rights
    to access the Opsview JSON API.

  * If you haven't installed Opsview under `/` of your webserver, you
    can edit line 7 of unhandled.html and adjust the `nv.URL` property.

### Screenshot

![screenshot](http://allan.de/nocview.jpg)

