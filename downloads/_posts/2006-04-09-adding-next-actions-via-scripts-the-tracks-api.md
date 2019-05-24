---
layout: post
date: 2006-04-09 
author: bsag 
title: "Adding next actions via scripts: the Tracks API" 
categories: [downloads] 
comments: true
sharing: true
footer: true
---

Version: API Applescripts

[File URL](/assets/code/CombinedAPIApplescripts.zip)

The Subversion trunk version of Tracks now has a nice API, provided by [Luke Melia](http://www.lukemelia.com/). This means that it's possible to communicate with Tracks via scripts to add next actions without using the browser interface. This is all exciting stuff, and I decided to knock up a couple of AppleScripts for the Mac OS X users to take advantage of this. One (NewTodoAPI.scpt) is a fairly simple thing that pops up a dialog box asking for a description, and then sends that to your Tracks installation to a hard-coded context. The other, NewTodoMailAPI.scpt takes the sender and subject of the selected email(s) in Mail and creates a new action for each one, with the description, "Email [sender] about [subject]". The description gets truncated to 100 characters (the validation limit for the field) if it's longer than that. It also has Growl notifications if you've got Growl installed.

Luke then took my scripts and raised me a Quicksilver: his lovely script (quicksilver_add_to_tracks.zip) can be used very smoothly from Quicksilver. His instructions are as follows.

# Download the AppleScript.
# Edit the script to include your own username, token, context id, and url
# Compile and save the script
# Copy the script to ~/Library/Application Support/Quicksilver/Actions/ (you may need to create the Actions directory)
# Restart Quicksilver
# Activate Quicksilver (Ctrl+Space by default)
# Press "." to put quicksilver into text mode
# Type the description of the next action you want to add
# Press tab to switch to the action pane.
# By typing or scrolling, choose the "Add to Tracks" action.

For both scripts, you need to edit them to include your username, your token (check the feed links for a long string of letters and numbers and copy that), the id of the context you want the actions to go into, and the URL for your installation. The comments should make it all fairly self explanatory. Have fun!
 
