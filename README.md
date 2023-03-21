POCO DNS-SD (Zeroconf) Wrapper Library for Bonjour and Avahi
============================================================

**This library has been moved to main [proco libraries](https://github.com/pocoproject/poco), and this place is only for archived.**
**All contrinution are welcome in main [proco libraries](https://github.com/pocoproject/poco)**

This is a POCO-based wrapper library providing an easy-to-use and
unified programming interface to Apple Bonjour and Avahi libraries
implementing DNS Service Discovery (DNS-SD, also known as Zeroconf).

Prerequisites
-------------

The [Apple Bonjour SDK](https://developer.apple.com/bonjour/) is needed on Windows (and OS X, of course). The Avahi client libraries are needed on Linux.

Getting Started
---------------

Clone into the root of an existing POCO source tree. The POCO Foundation and Net 
libraries are required.


    $ git clone https://github.com/pocoproject/poco-dnssd.git DNSSD

On Windows, build the included Visual C++ solution. On Linux/OS X, build with POCO_BASE environment variable set to the root of
the POCO source tree.

    $ export POCO_BASE=`pwd`
    $ cd DNSSD
    $ make -s -j8
    $ make -s -j8 -C Default

See the [doc](https://github.com/pocoproject/poco-dnssd/tree/master/doc) directory for documentation and the samples directory for sample 
applications.


License
-------

Boost Software License 1.0
