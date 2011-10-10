==========
webload-go
==========

experiments with concurrency and Go.

* http://golang.org/

----
Info
----
 
 * http://golang.org/doc/codewalk/sharemem/
 * http://golang.org/doc/codewalk/urlpoll.go

--------
Build Go
--------

::

    $ hg clone -u release https://go.googlecode.com/hg/ go
    $ cd go/src
    $ ./all.bash

see: http://golang.org/doc/install.html

------------------
Compile webload-go
------------------

use the included Makefile to compile and link webload-go::

    $ gomake
    
this will produce an executable name 'webload'::

    $ ./webload
