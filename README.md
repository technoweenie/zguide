
<A name="toc1-4" title="ØMQ - The Guide" />
ØMQ - The Guide
===============

Written by Pieter Hintjens <ph@imatix.com>, CEO iMatix Corporation.

A ØMQ socket is what you get when you take a normal TCP socket, inject it with a mix of radioactive isotopes stolen from a secret Soviet atomic research project, bombard it with 1950-era cosmic rays, and put it into the hands of a drug-addled comic book author with a badly-disguised fetish for bulging muscles clad in spandex.  Yes, ØMQ sockets are the world-saving superheros of the networking world.

<center>
<img src="https://github.com/imatix/zguide/raw/master/images/README_1.png" alt="1">
</center>

<A name="toc2-34" title="Contents" />
Contents
--------

&emsp;<a href="#toc2-40">License</a>
&emsp;<a href="#toc2-46">Thanks</a>
&emsp;<a href="#toc2-52">General</a>
&emsp;<a href="#toc2-60">Examples</a>
&emsp;<a href="#toc2-70">Guidelines</a>
&emsp;<a href="#toc2-82">Build Process</a>

<A name="toc2-40" title="License" />
License
-------

The text of "ØMQ - The Guide" is copyright (c) 2010 Pieter Hintjens, and is licensed under the Creative Commons Attribution-Share Alike 3.0 License.  The source code examples are licensed under MIT/X11.  `z2w` is placed into the public domain.

<A name="toc2-46" title="Thanks" />
Thanks
------

Thanks to Bill Desmarais, Brian Dorsey, CAF, Daniel Lin, Eric Desgranges, Gonzalo Diethelm, Guido Goldstein, Hunter Ford, Kamil Shakirov, Martin Sustrik, Mike Castleman, Naveen Chawla, Nicola Peduzzi, Oliver Smith, Olivier Chamoux, Peter Alexander, Pierre Rouleau, Randy Dryburgh, and Zed Shaw for their contributions, and to Stathis Sideris for [Ditaa](ditaa.org).

<A name="toc2-52" title="General" />
General
-------

The Guide is a general introduction to ØMQ, and covers version 2.0.x.  It will be updated to cover 2.1.0 as soon as that is formally released.

To submit an errata use the [issue tracker](http://github.com/imatix/zguide/issues).  All discussion of the contents or examples happens on the zeromq-dev list or #zeromq IRC channel.

<A name="toc2-60" title="Examples" />
Examples
--------

The examples from the Guide help people to learn and use ØMQ.  While we wrote most of the examples in C, we welcome translations into other languages. All example code is licensed under MIT/X11.

Languages with a 100% translation of examples get their own version of the Guide. So far, only the PHP community have managed this. To send us a translation, please clone this git and make a pull request, following the process explained here: <http://www.zeromq.org/docs:contributing>.

If you don't want to use git, you can email us entire examples but only if the code was empty before.  If you want to update or change an example you MUST use git pull requests.

<A name="toc2-70" title="Guidelines" />
Guidelines
----------

Please:

* Stick to identical functionality and naming used in examples so that readers can easily compare languages.
* You MUST place your name as author in the examples so readers can contact you.
* You MUST state in the email that you license your code under the MIT/X11 license, or else use git's signoff feature as explained on this page: http://www.zeromq.org/docs:contributing

Thanks!

<A name="toc2-82" title="Build Process" />
Build Process
-------------

To rebuild the Guide from this git repository you need z2w and Ditaa (included in the bin directory), ImageMagick, perl. Run the command: "z2w chapter*.txt".  The result is a series of files named `chapter1.wd`, `chapter2.wd`, etc.  Paste these into a Wikidot site appropriately.

Images and source examples are hosted here at github.com and to modify an image or example we commit it to this repository.

This document is originally at README.txt and is built using [gitdown](http://github.com/imatix/gitdown), a great little tool by the same author.
