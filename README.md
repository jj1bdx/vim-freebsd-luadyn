# This archive is historic: please use FreeBSD official Ports

3-JUL-2015: I will not delete and keep this archive for historic reference purpose, but I will no longer maintain this archive either.

## For historic purpose only: FreeBSD vim experimental port for adding if\_lua

*Note: this archive is no longer maintained*

* _Note well:_ Since 28-FEB-2014, the contents of this repository are the same as the original `editors/vim` Port. If any Lua plugin related bug happens again, editing this repository will be reactivated.  Always try the FreeBSD Port `editors/vim` first, and do not forget to send the problem reports by `send-pr`.

## Updating notes

* 31-DEC-2014: updated to editors/vim 7.4.560 port r375580.
* 18-DEC-2014: updated to editors/vim 7.4.542 port r374629.
* 9-DEC-2014: updated to editors/vim 7.4.540\_1 port r373973.
* 25-NOV-2014: updated to editors/vim 7.4.518 port r373363.
* 15-OCT-2014: updated to editors/vim 7.4.430\_2 port r367751.
* 5-SEP-2014: updated to editors/vim 7.4.430 port r367261.
* 9-AUG-2014: updated to editors/vim 7.4.398 port r364341.
* 4-AUG-2014: updated to editors/vim 7.4.389 port r363785.
* 15-JUL-2014: updated to editors/vim 7.4.364 port r361806.
* 25-JUN-2014: updated to editors/vim 7.4.334 port r358979.
* 2-JUN-2014: updated to editors/vim 7.4.316 port r356001.
* 30-MAY-2014: updated to editors/vim 7.4.307 port r355254.
* 23-MAY-2014: updated to editors/vim 7.4.295 port r354670.
* 10-MAY-2014: updated to editors/vim 7.4.281 port r353246.
* 28-APR-2014: updated to editors/vim 7.4.265 port r352302.
* 16-APR-2014: updated to editors/vim 7.4.256 port r351136.
* 10-APR-2014: updated to editors/vim 7.4.240 port r350691.
* 4-APR-2014: updated to editors/vim 7.4.229\_1 port r349847.
* 24-MAR-2014: updated to editors/vim 7.4.205\_1 port r348181.
* 28-FEB-2014: updated to editors/vim 7.4.192\_1 port r346444.

## Past problems

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
