pyramid_translogger
========================================

development.ini

::

   # add pyramid_translogger
   pyramid.includes = pyramid_translogger


access log is shown

::

   serving on http://0.0.0.0:6543
   127.0.0.1 - - [01/Nov/2014:14:21:56 +0900] "GET / HTTP/1.1" 200 - "-" "curl/7.33.0"
   127.0.0.1 - - [01/Nov/2014:14:22:07 +0900] "GET / HTTP/1.1" 200 - "-" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10.8; rv:32.0) Gecko/20100101 Firefox/32.0"
   127.0.0.1 - - [01/Nov/2014:14:22:07 +0900] "GET /static/theme.css HTTP/1.1" 200 - "http://localhost:6543/" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10.8; rv:32.0) Gecko/20100101 Firefox/32.0"
   127.0.0.1 - - [01/Nov/2014:14:22:07 +0900] "GET /static/pyramid.png HTTP/1.1" 200 - "http://localhost:6543/" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10.8; rv:32.0) Gecko/20100101 Firefox/32.0"
   127.0.0.1 - - [01/Nov/2014:14:22:07 +0900] "GET /_debug_toolbar/static/css/toolbar.css HTTP/1.1" 304 - "http://localhost:6543/" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10.8; rv:32.0) Gecko/20100101 Firefox/32.0"
   127.0.0.1 - - [01/Nov/2014:14:22:07 +0900] "GET /_debug_toolbar/static/img/pdtb.png HTTP/1.1" 304 - "http://localhost:6543/_debug_toolbar/static/css/toolbar.css" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10.8; rv:32.0) Gecko/20100101 Firefox/32.0"
