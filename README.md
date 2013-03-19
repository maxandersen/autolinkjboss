Autolink for JBoss
==================

Simple userscript to enable automatic linking of email and plain text urls and more importantly JBoss jira links.

This allows you to just refer to Jira bugid's and not full urls in things like Github, like below:

![Example](https://raw.github.com/maxandersen/autolinkjboss/master/example.png)

How to install
==============

This is an userscript so any form of Greasemonkey browser variation should work.
Generic instructions for installing userscripts can be found at: https://github.com/p2k/GLaDOS-Enhancer-Plus/wiki/Installing-Userscripts

What I currently use is Chrome and here the steps are:

   1) Download https://github.com/maxandersen/autolinkjboss/raw/master/autolinkjboss.user.js
   
   2) Open Chrome Extension Page (chrome://chrome/extensions/) via Window -> Extensions.

   3) Drag autolinkjboss.userscript.js to this page

   4) Approve the dialog 

   5) Done!

Steps for Safari:

   1) Install NinjaKit from https://github.com/os0x/NinjaKit

   2) Restart Safari

   3) Click https://github.com/maxandersen/autolinkjboss/raw/master/autolinkjboss.user.js and confirm installation

   4) Done!

Steps for Firefox:

   1) Install the Greasemonkey add-on

   2) Restart Firefox

   3) Simply open the autolinkjboss.user.js file in Firefox.  Greasemonkey will automatically ask to if the extension should be installed.

   4) Done!

Got instructions for another browser or want to improve/extend the list of jira's it supports fork this repo and send a pullrequest :)

Tests
=====

If you have the plugin correctly installed these text links should be automatically linked:

Twitter: @maxandersen @jbosstools

Jira's: JBIDE-234, FORGE-24, AS7-66, ARQGRA-23, RF-334, HHH-234, METAGEN-3, JDF-211



