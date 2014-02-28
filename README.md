# FreeBSD vim experimental port for adding if\_lua

* 28-FEB-2014: updated to editors/vim 7.4.192\_1 port r346444.

* 25-FEB-2014: PR 186917 merged to editors/vim 7.4.182\_1 by Sunpoet Po-Chuan Hsieh. Thank Sunpoet! The master branch is a copy of 7.4.182\_1 port r345889.

* 20-FEB-2014: editors/vim 7.4.182 *broke* the Lua dynamic code loading *again*. Fix included in the master branch. See also PR ports/186917 <http://www.freebsd.org/cgi/query-pr.cgi?pr=ports/186917>

* 12-FEB-2014: PRs 185650 and 184588 merged by Martin Wilke, as editors/vim 7.4.169\_1. Thanks Martin!
    * See also <http://docs.freebsd.org/cgi/getmsg.cgi?fetch=2591121+0+current/svn-ports-head>

* 10-FEB-2014: FreeBSD Port editors/vim 7.4.169 still fails to dynamic-load Lua 5.2. Use vim-shlib-name.patch.txt to fix the bug.

* 11-JAN-2014: FreeBSD Port editors/vim 7.4.110\_3 tries to dynamic-load Lua 5.2, but fails to do so. Use vim-shlib-name.patch.txt to fix the bug.
    * See PR ports/185650 <http://www.freebsd.org/cgi/query-pr.cgi?pr=ports/185650>
    * Also see PR ports/184588 <http://www.freebsd.org/cgi/query-pr.cgi?pr=ports/184588>

* Name of the branches:
    * dev-dynamic-lua51: OLD, dynamically linking lua 5.1 (lang/lua)
    * dev-static-lua51: OLD, statically linking lua 5.1 (lang/lua)
    * dev-static-lua52: OLD, statically linking lua 5.2 (lang/lua52)
    * master: dynamically linking lua 5.2 (lang/lua52, following Port vim-7.4.182)
