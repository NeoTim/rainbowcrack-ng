Upstream
========

* https://packages.gentoo.org/package/app-crypt/rainbowcrack

* Based on "rainbowcrack-1.2-r2.ebuild" file

Changes
-------

* "rainbowcrack-1.2-share.patch" is omitted (see patches/ folder)

* CRLF to LF changes

* Fix whitespace, and indentation errors

* Disabled "MD2" for good

Why?
----

FOSS software packages to generate rainbow tables do not exist.

rracki_mt (freerainbowtables), and RainbowCrack (project-rainbowcrack.com),
both went closed source, for the table generation part.

TODO
----

* Pull in changes from https://github.com/kost/drcrack project
