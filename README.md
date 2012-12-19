Firefeed
========

Firefeed is a web app that lets users post small messages called *sparks* to
their stream. You can follow other users, and their sparks will appear on your
stream.

The unique property of this application is that it is built entirely using
client side logic - no server neccessary - other than to serve the static
HTML/CSS/JS files, of course.

This is made possible by Firebase. A detailed explanation of how the app
was built is [available here](http://firefeed.io/about.html).

Layout
------

The core application logic is in www/js/firefeed.js. It is hooked up to the
UI in www/index.html via www/js/firefeed-ui.js.

If you'd like to embed a stream like Firefeed into your app, we recommend
import firefeed.js and hooking it up to your own UI.

License
-------
No part of this project may be copied, modified, propagated, or distributed
except according to terms in the accompanying LICENSE file (MIT licensed).
