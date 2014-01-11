# FreeBSD vim experimental port for adding if\_lua

* 11-JAN-2013: FreeBSD Port editors/vim 7.4.110\_3 tries to dynamic-load Lua 5.2, but fails to do so. Use vim-shlib-name.patch.txt to fix the bug.
    * See PR ports/185650 <http://www.freebsd.org/cgi/query-pr.cgi?pr=ports/185650>
    * Also see PR ports/184588 <http://www.freebsd.org/cgi/query-pr.cgi?pr=ports/184588>
