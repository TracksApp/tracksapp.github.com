 
---
layout: post
date: 2007-03-10 
author: bsag 
title: "A really easy installation for MacOS X users" 
categories: [news] 
comments: true
sharing: true
footer: true
---

I've been playing around with Locomotive recently, and I'm really impressed how easy the whole process is now. I've altered the [zip package](http://www.rousette.org.uk/projects/files/tracks-1.043.zip) of Tracks 1.043 to make it as easy as possible for MacOS X users. I've pre-configured the package to use the SQLite3 database, which is included in the package, and also set up the logs and environment.rb file so that all you need to do is download Locomotive, point it at your Tracks folder and go! The full instructions are in the tracks-1.043 folder in <code>installation.html</code>.

As a side effect, the process of installation should be a little easier for Windows and Linux users too, because you no longer need to do the tedious copying of the *.tmpl files and folders. I've also included a security patch (details [here](http://dev.rousette.org.uk/changeset/475)). If you're using Tracks on a public server, I would install the new version, but if it's on your own machine with no public access, you should be fine.

I'm going to radically overhaul both the installation method and instructions for the next release, because I know that people get put off by the installation process.

**Update 2007-03-25:** A few users bumped into a problem with using newer versions of the Locomotive bundles (see explanation [here](http://www.rousette.org.uk/projects/forums/viewreply/413/)), so I've updated the tracks-1.043.zip package to fix the problem, and updated the installation.html to explain the importance of using the 'Standard Rails March 2007' bundle. 

 
