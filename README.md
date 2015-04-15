Stormpath ID Site
========

Stormpath ID Site is a set of hosted and pre-built user interface screens that
take care of common identity functions for your applications — login,
registration, and password reset. ID Site can be accessed via your own custom
domain like id.mydomain.com and shared across multiple applications to create
centralized authentication if needed.

All ID Sites are sourced from Github repositories and cached within our
infrastructure.  If you are using our default ID Site, then your ID Site is
sourced from this repository.  The assets in this repository are minified for
performance.

If you want to customize your ID Site you will need to host it in your own
Github repository, please read [Customizing ID Site].
That document explains the process of forking the [ID Site Source Repository]
and generating your own minified ID Site.

If you don't want to use our source project, you can use [Stormpath.js] to
build your own ID Site application from scratch.

This repository contains a branch named **debug** which contains a non-minified
version of the default application.  If you need to make simple modifications
and don't mind using un-minified assets in your ID Site, you can fork this
branch, modify it, and use it for your custom ID Site.



[Customizing ID Site]: http://docs.stormpath.com/guides/using-id-site/#customizing-the-default-id-site

[ID Site Source Repository]: https://github.com/stormpath/idsite-src

[Stormpath.js]: https://github.com/stormpath/stormpath.js "Stormpath.js"
