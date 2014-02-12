# FreeBSD vim experimental port for adding if\_lua

* 12-FEB-2014: PRs 185650 and 184588 merged by Martin Wilke, as editors/vim 7.4.169_1. Thanks Martin!
    * See also <http://docs.freebsd.org/cgi/getmsg.cgi?fetch=2591121+0+current/svn-ports-head>

* 10-FEB-2014: FreeBSD Port editors/vim 7.4.169 still fails to dynamic-load Lua 5.2. Use vim-shlib-name.patch.txt to fix the bug.

* 11-JAN-2014: FreeBSD Port editors/vim 7.4.110\_3 tries to dynamic-load Lua 5.2, but fails to do so. Use vim-shlib-name.patch.txt to fix the bug.
    * See PR ports/185650 <http://www.freebsd.org/cgi/query-pr.cgi?pr=ports/185650>
    * Also see PR ports/184588 <http://www.freebsd.org/cgi/query-pr.cgi?pr=ports/184588>

* Name of the branches:
    * dev-dynamic-lua51: OLD, dynamically linking lua 5.1 (lang/lua)
    * dev-static-lua51: OLD, statically linking lua 5.1 (lang/lua)
    * dev-static-lua52: OLD, statically linking lua 5.2 (lang/lua52)
    * master: dynamically linking lua 5.2 (lang/lua52, following Port vim-7.4.169)
