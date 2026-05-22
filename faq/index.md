---
layout: default
title: FAQ
permalink: /faq/
---
# General questions

<div class="faq_item">

My OpenLieroX will not start, it terminates with a message "Could not load fonts"?
{:.question}

This is because OpenLieroX cannot find its data files. If you are running OpenLieroX via a shortcut (for example an icon on your desktop), make sure the Working directory field in Shortcut properties points to the directory where you unpacked the game.
{:.answer}

</div>

<div class="faq_item">

Where do I find the "standard output" on my Windows machine?
{:.question}

Navigate to OpenLieroX directory and open the file **stdout.txt**.
{:.answer}

</div>

<div class="faq_item">

Where do I put new mods, levels and skins?
{:.question}

<div class="answer">

There are more places where you can put the files. The most recommended way is to put everything in so-called Home folder, which is located as follows:

- **Windows:** My Documents\OpenLieroX
- **Mac OS X:** ~/Library/Application Support/OpenLieroX
- **Linux/Unix/BSD:** ~/.OpenLieroX

A mod consists of a folder with contents, and it is placed directly in your Home folder. Levels are placed in the "levels" folder, while skins are placed in the "skins" folder. If these folders do not exist yet, you can create them.

</div>

</div>

<div class="faq_item">

How do I take a screenshot?
{:.question}

Press the Take Screenshot button (default F12, can be set in Options).
{:.answer}

</div>

<div class="faq_item">

Where do I find the screenshots I take in-game?
{:.question}

<div class="answer">

The screenshots are stored to *scrshots* folder in your Home folder:

- **Windows:** My Documents\OpenLieroX\scrshots
- **Mac OS X:** ~/Library/Application Support/OpenLieroX/scrshots
- **Linux/Unix/BSD:** ~/.OpenLieroX/scrshots

</div>

</div>

<div class="faq_item">

How do I kick a player in game?
{:.question}

<div class="answer">

There are three ways to achieve this:

1. Press ESC in game to open Game Menu and click the tiny blue button next to the player you want to kick. A menu with the kick option will appear.
2. Open console (F1 in beta8 and lower, F3 in beta9), and type *kick "Worm Name"*, where Worm Name is the name of the worm you want to kick. If the name is too long or complicated you might prefer kicking a worm by its ID: *kickid ID*. The worm ID can be found in the scoreboard or Game Menu (press ESC).
3. Open chat (default key is i) and type: */kick "Worm Name"* or */kick id ID*

</div>

</div>

<div class="faq_item">

I found a bug in the game, where to report it?
{:.question}

Please [fill a bug report in our tracker](https://sourceforge.net/tracker/?func=add&group_id=180059&atid=891648).
{:.answer}

</div>

<div class="faq_item">

I miss something in the game, how do I tell you?
{:.question}

Please [fill a feature request](https://sourceforge.net/tracker/?func=add&group_id=180059&atid=891651).
{:.answer}

</div>

# Hosting a server

<div class="faq_item">

How do I make my own Internet/LAN server?
{:.question}

Navigate to Net Play &ndash; Host, choose a player to play with and click OK.
{:.answer}

</div>

<div class="faq_item">

My server does not appear in the server list, why?
{:.question}

Make sure you tick the "Register server" checkbox when starting the server.
{:.answer}

</div>

<div class="faq_item">

My server has a blue icon in the serverlist, or the server is not visible at all, why?
{:.question}

Most probably your NAT/Firewall is blocking your server. If you are on a shared network, you probably will not be able to host. If you have your personal Internet connection (such as ADSL), you have to set up your router. An information on how to do this is available at [www.portforward.com](http://portforward.com/). OpenLieroX uses port 23400 (same as LieroX).
{:.answer}

</div>

# Creating levels, mods and skins

<div class="faq_item">

The built-in level editor sucks, how do I create a better level?
{:.question}

Follow the [tutorial at our Wiki](http://www.lxalliance.net/wiki/index.php/Level_Making).
{:.answer}

</div>

<div class="faq_item">

How do I create a new weapon mod?
{:.question}

Follow the [tutorial at our Wiki](http://www.lxalliance.net/wiki/index.php/Scripting).
{:.answer}

</div>

<div class="faq_item">

How do I create a new worm skin?
{:.question}

Follow the [tutorial at our Wiki](http://www.lxalliance.net/wiki/index.php/Skin).
{:.answer}

</div>

<div class="faq_item">

I created a mod and when I compile it with Game Compiler it's not working, why?
{:.question}

The original Game Compiler from Jason Boettcher is broken. Please use [LMS](http://lxalliance.net/forum/index.php?action=mgallery;sa=item;id=5470) instead.
{:.answer}

</div>

<div class="faq_item">

Where do I upload my finished masterpiece?
{:.question}

Please use our [FileBase](http://lxalliance.net/forum/index.php?action=mgallery;sa=album;id=12), it serves as a central place for keeping OpenLieroX files.
{:.answer}

</div>

# Developing OpenLieroX

<div class="faq_item">

What programming language is OpenLieroX written in?
{:.question}

The game core is written in C++. The scripts for dedicated server are written in Python.
{:.answer}

</div>

<div class="faq_item">

I want to join the development, where do I start?
{:.question}

First download and compile OpenLieroX from our Subversion repository at https://openlierox.svn.sourceforge.net/svnroot/openlierox openlierox. You will find some information about compiling in the forums: [Windows](http://lxalliance.net/forum/index.php/topic,6444.0.html), [Mac OS X](http://lxalliance.net/forum/index.php/topic,12367.0.html), [Linux](http://lxalliance.net/forum/index.php/topic,5158.0.html).<br />
Also don't forget to visit our [Sourceforge site](https://sourceforge.net/projects/openlierox/) and [join our development mailing list](mailto:openlierox-devel@lists.sourceforge.net) where you will be provided with more information.
{:.answer}

</div>

<div class="faq_item">

I would like to help but I don't know how much time I have, is it a problem?
{:.question}

Not at all. We all are doing this in our free time. Even a little help is better than none!
{:.answer}

</div>
